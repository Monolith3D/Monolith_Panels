# parametric monolith panels with annex clips
a few files for adding annex clips to the monolith panels. 

![1](Images/corner.jpg)

## files:
### STLs/monolithStock_annex
- **STLs/monolithStock_annexCorner.step**
- **STLs/monolithStock_annexKey.3mf**

premade files for the stock monolith panel dimensions. you'll still need everything from the original monolith panels, except the corner body. 

print 2x keys for each corner.

### CAD/monolith_annex_mashup_variable_height
- **CAD/monolith_annex_mashup_variable_height.f3d**
- **[key_asymmetric_10.STEP](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/All_Printers/annex_dev-Panel_2020_Clips_and_Hinges/panel_clips_and_corners/key/CAD)** (or another size)

the full f3d file with parametric history, so that you can custom make your own panel thickness, foam thickness, etc. 
includes corner body, and edge body. does ***not*** include support for hinges, or doors. 
for the key to be the right size, you'll need to download the key from the annex panels repo, split the key in the middle, then lengthen the middle by (panel_height_total - panel_height_outside - key_height - 0.1). where key_height would be 10 for key_asymmetric_10.STEP. 

be warned, I haven't updated the file in a minute, and it might have funny behaviour on large or small heights. I've been meaning to get around to this mod and clean it up, but life happens. 

### credits
[monolith panels by cloakedwayne](https://github.com/Monolith3D/Monolith_Panels)

[annex clips by annex engineering](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/All_Printers/annex_dev-Panel_2020_Clips_and_Hinges)
