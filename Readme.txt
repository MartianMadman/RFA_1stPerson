My own personal attempt at making a 1st person mod for RFA. Makes a few other changes as well to aid in the 1st person experience.

\Changelog v1/
-Set vertical fov to 75. Horizontal fovs will differ depending on aspect ratios. Horizontal fovs are |5:4 = 87|4:3 = 90|16:10 = 101|16:9 = 107|21:9 = 121|.
-Add casts_shadows flag to almost all of items_3d.xtbl and gameplay_properties.xtbl.
-Remove melee finisher animations because they do not work well with 1st person cam.
-Fix potential startup crash on publicbeta version of RFA.
-Increase draw distance of lights and lods.
-Fix npcs disappearing when near camera.
-Remove dodge forward animation.
-Remove melee auto-targeting.
-Remove player jumping delay.
-Add 1st person to turrets.

\Changelog v2/
-Change many player animations to make better use of player model in view.
-Fix many missing visual features.
-Restore melee auto-targeting.
-Adjust turret view.

\Issues/
-Unwanted fov scaling for 4:3/5:4 aspect ratio. To fix this, launch game in 16:9 and then switch to 4:3 resolutions.
