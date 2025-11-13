---
title: Avatar project files and references
description: Download various character-related project files and reference files.
---

<Alert severity = 'info'>
See [Resources](../../avatar/resources.md) for a complete list of avatar-related downloadable content.
</Alert>

## Project files

The following `.fbx`, `.blend`, and `.ma` project files are available to use as examples, boilerplate, or reference:

<Tabs>
  <TabItem label="Models">
  <table>
<thead>
  <tr>
    <th>Filename</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><a href="../../assets/modeling/skinned-meshes/Lola.fbx" download>Lola.fbx</a></td>
    <td>A skinned R15 character created from the <a href="../../art/modeling/skin-a-humanoid-model.md">Skin a humanoid model</a> guide. Since this reference model doesn't yet have [inner and outer cage mesh data](../../art/characters/specifications.md#inner-and-outer-cages), this model can't equip layered clothing or accessories.</td>
  </tr>
  <tr>
    <td><a href="../../assets/avatar/dynamic-heads/reference-files/Fish-Person.zip" download>Fish-Person.zip</a></td>
    <td>A rigged and skinned humanoid character model with a full body cage, facial animation rig, and associated PBR texture maps.</td>
  </tr>
    <tr>
    <td><a href="../../assets/avatar/dynamic-heads/reference-files/BlockyCharacter.fbx" download>BlockyCharacter.fbx</a></td>
    <td>A Blocky character model with an [animatable head](../../art/characters/facial-animation/index.md) and a full body cage.</td>
  </tr>
    <tr>
    <td><a href="../../assets/avatar/dynamic-heads/reference-files/GoblinCharacter.zip" download>GoblinCharacter.zip</a></td>
    <td>A Goblin character model with an [animatable head](../../art/characters/facial-animation/index.md) and a full body cage.</td>
  </tr>
    <tr>
    <td><a href="../../assets/art/reference-files/ClassicMannequin.fbx" download>ClassicMannequin.fbx</a></td>
    <td>A [classic body](../../art/characters/specifications.md#classic) type blank mannequin to use in Studio or your modeling application.</td>
  </tr>
  <tr>
    <td><a href="../../assets/art/reference-files/ClassicMannequin_With-Cages.fbx" download>ClassicMannequin_With-Cages</a></td>
    <td>A [classic](../../art/characters/specifications.md#classic) body type blank mannequin with **body cages** to use in Studio or your modeling application for clothing design. Due to unconfigured cage objects, this file may not import correctly into Studio until modified.</td>
  </tr>
  <tr>
    <td><a href="../../assets/art/reference-files/RthroMannequin.fbx" download>RthroMannequin.fbx</a></td>
    <td>An [Rthro Normal](../../art/characters/specifications.md#normal) body type blank mannequin to use in Studio or your modeling application.</td>
  </tr>
  <tr>
    <td><a href="../../assets/art/reference-files/RthroMannequin_With-Cages.fbx" download>RthroMannequin_With-Cages.fbx</a></td>
    <td>An [Rthro Normal](../../art/characters/specifications.md#normal) body type blank mannequin with **body cages** to use in Studio or your modeling application for clothing design to use in Studio or your modeling application. Due to unconfigured cage objects, this file may not import correctly into Studio until modified.</td>
  </tr>
  <tr>
    <td><a href="../../assets/art/reference-files/RthroSlenderMannequin.fbx" download>RthroSlenderMannequin.fbx</a></td>
    <td>An [Rthro Slender](../../art/characters/specifications.md#slender) body type blank mannequin to use in Studio or your modeling application.</td>
  </tr>
  <tr>
    <td><a href="../../assets/art/reference-files/RthroSlenderMannequin_With-Cages.fbx" download>RthroSlenderMannequin_With-Cages.fbx</a></td>
    <td>An [Rthro Slender](../../art/characters/specifications.md#slender) body type blank mannequin with **body cages** to use in Studio or your modeling application to use in Studio or your modeling application for clothing design. Due to unconfigured cage objects, this file may not import correctly into Studio until modified.</td>
  </tr>
</tbody>
</table>
  </TabItem>
  <TabItem label="Blender">
  <table>
  <thead>
  <tr>
    <th><b>File</b></th>
    <th><b>Description</b></th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Rig_and_Attachments_Templates.zip" download>Rig_and_Attachments_Template.blend</a></td>
    <td>Starting armature rig template for Blender. Contains an armature with correct R15 naming conventions and attachment points. Use this template for rigging bodies and clothing items.</td>
  </tr>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Body_Cage_Templates.zip" download>Body_Cage_Template.blend</a></td>
    <td>Starting template for Blender, includes individual body part cages for each 15 humanoid parts. Use this template for caging your avatar bodies. <br /> <br /> <Alert severity='info'>To save time, edit the full-body `std_cage_deformable` mesh to automatically apply vertex changes to the individual body-part meshes. When importing the `.fbx` into Studio, you can remove this helper mesh.</Alert></td>
  </tr>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Combined_Templates.zip" download>Combined-Template.blend</a></td>
    <td>Template file containing all content from previous templates, includes rig skeleton, body cages, attachment points. Use this template to rig and cage bodies and accessories.</td>
  </tr>
</tbody>
</table>

  </TabItem>
  <TabItem label="Maya">
  <table>
<thead>
  <tr>
    <th><b>File</b></th>
    <th><b>Description</b></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Rig_and_Attachments_Templates.zip" download>Rig_and_Attachments_Template.ma</a></td>
    <td>Starting armature rig template for Maya. Contains an armature with correct R15 naming conventions and attachment points. Use this template for creating bodies and clothing items.</td>
  </tr>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Body_Cage_Templates.zip" download>Body_Cage_Template.ma</a></td>
    <td>Starting template for Maya, includes individual body part cages for each 15 humanoid parts. Use this template for caging your avatar bodies. <br /> <br /> <Alert severity='info'>To save time, edit the full-body `std_cage_deformable` mesh to automatically apply vertex changes to the individual body-part meshes. When importing the `.fbx` into Studio, you can remove this helper mesh.</Alert></td>
  </tr>
  <tr>
    <td><a href="../../assets/modeling/meshes/reference-files/Combined_Templates.zip" download>Combined-Template.ma</a></td>
    <td>Template file containing all content from previous templates, includes rig skeleton, body cages, attachment points. Use this template to rig and cage bodies and accessories.</td>
  </tr>

</tbody>
</table>

  </tr>

</tbody>
</table>
  </TabI
</Alert>


  <figure>ature-Templates.png"/><figcaption><center>Caricature</center></figcaption></figure>
  <figure>
  Single body: <a href="../../assets/art/reference-files/Caricature.zip">Caricature.zip</a>
  </figure>
  </GridContainer>
  </TabItem>
</Tabs>
