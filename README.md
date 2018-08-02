# macOS Dvorak keyboard layout for typing St. Lawrence Island Yupik in IPA

## Files

1. `Dvorak Yupik IPA.keylayout`

   XML file that specifies the actual keyboard layout.

2. `Dvorak Yupik IPA.psd`

   Original Adobe Photoshop file from which the icon was generated. This image was created by taking a screenshot of [this map from OpenStreetMap](https://www.openstreetmap.org/export#map=9/63.3416/-170.2984&layers=T), and then editing the file in Photoshop to remove lakes and lagoons.

3. `Dvorak Yupik IPA.iconset`

   Directory containing scaled images exported from the Photoshop file, following the instructions from [here](https://blog.macsales.com/28492-create-your-own-custom-icons-in-10-7-5-or-later).
   
4. `Dvorak Yupik IPA.icns`

   Mac icon file, created from the directory of scaled images using this command:
   
   ```bash
   iconutil -c icns Dvorak\ Yupik\ IPA.iconset
   ```


## How to install

1. Copy the `Dvorak Yupik IPA.keylayout` and `Dvorak Yupik IPA.icns` files to either `~/Library/Keyboard Layouts` (to enable for one user) or to `/Library/Keyboard Layouts` (to enable for all users). This can be done using the Finder, or using the Terminal as described below:

   * For one user:

       ```bash
          cp Dvorak\ Yupik\ IPA.keylayout ~/Library/Keyboard\ Layouts/
          cp Dvorak\ Yupik\ IPA.icns ~/Library/Keyboard\ Layouts/
       ```

   * For all users:

       ```bash
          sudo cp Dvorak\ Yupik\ IPA.keylayout /Library/Keyboard\ Layouts/
          sudo cp Dvorak\ Yupik\ IPA.icns /Library/Keyboard\ Layouts/
       ```

2. Log out and log back in again. If that doesn't work try restarting.

3. Enable the keyboard layout:

   * Under the Apple menu, select System Preferences, then select Keyboard Preferences. 
   * Select the Input Sources tab
   * Click on the + button
   * Select "Others"
   * Select "Yupik (IPA, Dvorak)", and click Add.
   * In the Input Sources tab or in the Input Sources menu, select the "Yupik (IPA, Dvorak)" layout. The St. Lawrence Island icon should appear beside this input source.
   
   
## How to use

* Install, enable, and select the keyboard layout as described above.
* The keyboard layout is a standard Mac Dvorak keyboard layout.
* If the CAPS LOCK key is pressed, the keyboard switches to an alternative layout designed to produced IPA for St. Lawrence Island Yupik by typing in the St. Lawrence Island Yupik Latin orthography. The layout uses [dead keys](https://en.wikipedia.org/wiki/Dead_key) to accomplish this.


## Modifying and reinstalling

If you want to modify the keylayout and then reinstall it, do the following:

* In the Input Sources tab of the macOS Keyboard Preferences, use the - sign to remove "Yupik (Dvorak IPA)".
* Make any edits you desire to the `Dvorak Yupik IPA.keylayout` file
* Follow the instructions listed above for installing the modified file.


## License

* The image files were created by Lane Schwartz using data from [OpenStreetMap](http://www.openstreetmap.org), and are therefore licensed under the [Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/odbl).

* The keylayout file was created by Lane Schwartz using [Ukelele](https://scripts.sil.org/Ukelele), and may be copied under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/).

   ![Creative Commons Attribution-ShareAlike 4.0 International license](https://i.creativecommons.org/l/by-sa/4.0/88x31.png "Creative Commons Attribution-ShareAlike 4.0 International license")
   
