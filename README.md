# ME-Mod-Additional-Item-Tags
This repo is a mod for Medieval Engineers that aims to be a global library for custom item tag definitions that other mods can refer to (i.e. for crafting recipe dependencies).

If you want to add your own tags, please refer to this scheme (example):

  <Definition xsi:type="MyObjectBuilder_ItemTagDefinition">
    <Id Type="ItemTagDefinition" Subtype="YourUniqueTagName" />
    <DisplayName>Display name of your Tag</DisplayName>
    <Description>Description of your tag</Description>
    <Icon>Textures\GUI\Icons\Materials\StoneLarge.dds</Icon>
  </Definition>
  
Also add the information, to what item in which mod your tag refers, to give modders more transparency.
