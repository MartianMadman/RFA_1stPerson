My own personal attempt at making a 1st person mod for RFA. Makes a few other changes as well to aid in the 1st person experience.

\Changelog v1/
-Set vertical fov to 75. Horizontal fovs will differ depending on aspect ratios. Horizontal fovs are |5:4 = 87|4:3 = 90|16:10 = 101|16:9 = 107|21:9 = 121|.
-Add casts_shadows flag to almost all of items_3d.xtbl and gameplay_properties.xtbl.
-Remove melee finisher animations because they do not work well with 1st person cam.
-Fix potential startup crash on publicbeta version of RFA.
-Prevent npcs disappearing when near camera.
-Increase draw distance of lights and lods.
-Remove dodge forward animation.
-Remove melee auto-targeting.
-Remove player jumping delay.
-Add 1st person to turrets.

\Changelog v2.0.0/
-Change many player animations to make better use of player model in view.
-Adjust lod_properties.xtbl to potentially fix more lights not working.
-Fix many missing visual features.
-Restore melee auto-targeting.
-Adjust turret view.

\Changelog v2.1.0/
-Remove melee auto-targeting due to issues with it causing players head in view.
-Change shotgun, dual pistols, and charge launcher player animations.
-Slightly increase crouch to stand view switch speed.
-Slightly reduce large light draw distance.
-Improve player model clipping.
-Increase fov for walkers.
-Adjust camera positions.

\Installation/NOT FOR GITHUB!
Open the folder titled Packed and copy misc.vpp_pc along with table.vpp_pc to the build/pc/cache directory of your RFA installation. Replace existing files when asked.

Advanced users can pack the .vpp_pc files themselves for use with other mods or personal tweaks. The folder titled Source contains the modified .xtbl files of this mod.

\Issues/
-Unwanted fov scaling for 4:3/5:4 aspect ratio. To prevent this, launch game in 16:9 and then switch to 4:3 resolutions.
