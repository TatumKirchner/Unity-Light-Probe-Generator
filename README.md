# Unity-Light-Probe-Generator
Generate light probes within a volume in Unity.

Supports Move, Scale, Rotation, and Bounding box handles.

## Importing into Unity

Place LightProbeGenerator.cs into your scripts folder. LightProbeGenEditor.cs must be placed into an editor folder (make a folder named Editor if you do not have one) within your asset directory

## Setting up Light Probe Generator

1. First, create your light probe group (GameObject -> Create Empty, then Component -> Rendering -> Light Probe Group)
2. Attach the LightProbeGenerator component (Component -> Light Probe Helper -> Light Probe Generator)
3. Set how you want the placement algorithm to work (Grid or Random)

## Manipulate volume

Move, Scale, and Rotate with the normal unity gizmos. To edit the volume with the bounding box handles, click the edit bounds button in the inspector. Click it again to return to the normal gizmos.

## Generating Light Probes

1. ALWAYS remember to delete light probes before generating new ones (Select All -> Delete Selected or the Clear Button)
2. Set the volume you want the light probes to occupy (as well as either subdivisions or the number of light probes within the volume, depending on the selected placement algorithm).
3. Hit 'Generate'
4. Bake your lightmap

---

Original by http://forum.unity3d.com/members/51935-PhobicGunner

Edited By Svetoslav Iliev (http://www.fos4o.net)
