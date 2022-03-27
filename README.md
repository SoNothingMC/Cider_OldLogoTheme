# Old Logo Theme

A theme for [Cider], featuring the old logo because they look nice too.

![Screenshot of the modified logo inside the Cider interface](https://raw.githubusercontent.com/SoNothingMC/Cider_OldLogoTheme/main/docs/screenshot.png)

## Limitations

The theme only applies the old logo in the following place:

* Main menu button  
⚠ It clips the "Cider" text when you zoom in/out at 80%, 110%, 150% and 200%. I have no idea why, so just avoid those zoom levels.

Where it does not change the logo:

* Splash Screen
* About screen (due to forced inline CSS)
* Outside the app (e.g. App Icons)

## (Very Slight) Differences

Due to how the old/new logo is made, there are some differences on how the logo in this theme is displayed.

The old logo is made in Photoshop, while the new logo is made in Affinity Designer.

The old logo could not be completely displayed inside Affinity's suite of products (missing bevel effects), but since Photoshop exports everything as bitmap, the effects has to go.

<img src="https://raw.githubusercontent.com/SoNothingMC/Cider_OldLogoTheme/main/docs/psd_af_comparison.png" alt="A comparison between the original logo and one without layer effects." width=300px>

## Copyright

There are files with different copyrights in this repository.  
LICENSE files are included inside directories that does not fall under the root license.

### `/` (root directory)

* All files, except subfolders  
*Description:* Code files for the theme.  
© 2022 SoNothing, licensed under the [WTFPL].

### `/docs/` directory

* `screenshot.png`  
*Description:* Screenshot of the Cider app.  
Cider UI © 2022 Cider Collective, licensed under the [AGPLv3].  
Apple Music is a trademark of Apple Inc.

* All other files  
*Description:* Unmodified Cider logos.  
© 2021 Cider Collective, licensed under the [GPLv3].

### `/assets/modified_sources/` directory

* All files  
*Description:* Modified Cider logos.  
© 2021 Cider Collective, licensed under the [GPLv3].

### `/assets/sources/` directory

* `cider_newLogo_AppChromeBtn.afdesign`  
*Description:* Source files for the modified logos.  
© 2022 Cider Collective, licensed under the [AGPLv3].

* All other files  
*Description:* Source files for the modified logos.  
© 2021 Cider Collective, licensed under the [GPLv3].  

[Cider]: https://cider.sh/
[WTFPL]: https://github.com/SoNothingMC/Cider_OldLogoTheme/blob/main/LICENSE/
[AGPLv3]: https://github.com/ciderapp/Cider/blob/2804de5f15824ea13c6f64430f828cb665e1dfe9/LICENSE/
[GPLv3]: https://github.com/ciderapp/Cider/blob/37e9c8276ed2cd38c6a12cb12645bb36ced4a441/LICENSE/
