# Substratum Database

This is a collection of XML files and tools used by the Substratum team to keep supported ROMs and themes documented. There are two ways to get into this repo as a ROM developer and themer.

## 1. Pull requests

If you need some help starting a pull request, see [this article](https://help.github.com/articles/creating-a-pull-request/).

### For themers

Add your theme to the appropriate XML file. Please use the following template:

```xml
<theme id="THEME NAME">
    <author>YOUR NAME AS YOU WANT IT TO APPEAR</author>
    <link>DIRECT LINK TO YOUR THEME</link>
    <package>YOUR THEME'S PACKAGE IDENTIFIER</package>
    <pricing>Paid|free</pricing>
    <support>overlays|fonts|sounds|bootanimations|wallpapers</support>
    <backgroundimage>https://raw.githubusercontent.com/substratum/database/master/images/IMAGE_NAME.ext</backgroundimage>
    <image>DIRECT LINK TO PLAY STORE IMAGE</image>
</theme>
```
+ For the support tag, delete the ones that you do not support (do not reorder them).
+ For the backgroundimage tag, add your hero image from the Play Store into the Images folder and update the ending to be what your image is named.
+ For the image tag, open your theme in the Play Store on a computer, right click on the app icon, and open it in a new tab. Use that link.

Keep the themes in alphabetical order. Any themes NOT following these guidelines will be rejected.

### For ROM developers

Please add your ROM name (as you want it to appear) and identification prop (it MUST be unique, ro.cm.version, ro.mod.version, ro.rom.version are not acceptable) into the [Supported ROMs XML file](supported_roms.xml). If you have no unique prop (I'd recommend making one), please include a keyword (again, unique to you) that we can pull from your /system/build.prop. Keep the list alphabetical and format the commit message as "ROMs: Add <your_rom_name>". Any issues with this and your pull request will be rejected.

## 2. Showcase submission forms

For ROM devs, use [this form](https://docs.google.com/forms/d/1hMTzKPLCfcPiyXu-vjd6v5cY3bIf9cOOFEHGk4H6nWs/viewform).

For themers, use [this form](https://docs.google.com/forms/d/1nN84W00jLUuJpTN5BWsEWZjCjLdyy2I3zaLSCVqu_C4/viewform).

If the questions are not answered properly and correctly, your application will be disregarded.

# Questions?

Fill out [an issue](https://github.com/substratum/database/issues) or post in [the Substratum community](https://plus.google.com/communities/102261717366580091389) and tag Nathan Chancellor.
