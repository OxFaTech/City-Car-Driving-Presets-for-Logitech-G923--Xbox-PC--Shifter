![](https://storage.ko-fi.com/cdn/useruploads/display/8baf1134-a01a-442a-b47e-ab78c9171c4d_sttfahrtenmitlogitechg923undschaltknauf.png)
# City Car Driving Presets for Logitech G923 (Xbox/PC) + Shifter 🚗

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Version](https://img.shields.io/badge/Version-1.0-blue.svg) [![Steam Store](https://img.shields.io/badge/Steam-Store%20Page-blue?logo=steam)](https://store.steampowered.com/app/493490/City_Car_Driving/) [![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-orange?logo=kofi)](https://ko-fi.com/oxfatech) [![PayPal](https://img.shields.io/badge/PayPal-Donate-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=DX93QEVJU725U)

Version: 1.0 (Initial Release)
Created by: OxFaTech (LufatZ)

## Description

This repository provides optimized control preset files for **City Car Driving (Home Edition)** specifically designed for the **Logitech G923 Racing Wheel (Xbox/PC Version)** combined with the **Logitech Driving Force Shifter**.

These presets aim to fix common issues like inverted pedals and provide sensible button mappings, utilizing the G923's unique features like the rotary dial. Two main presets are offered depending on your preferred shifting method.

**Key Features:** ✨

* Correct axis assignment and pedal inversion for G923 (Gas, Brake, Clutch).
* Includes mappings for the Logitech Driving Force Shifter (H-Shifter Preset).
* Alternative preset optimized for Paddle Shifting.
* GPS Zoom and Mode mapped to the G923's rotary dial and enter button.
* Automatic turn signal cancellation enabled.
* Clear alias names used for easier understanding and customization (requires the included alias file).

## Files Included

* **`presets/City Car Driving Home Edition/Logitech_G923_Xbox_HShifter_GPSDial.xml`**: Preset optimized for using the H-pattern shifter for gears 1-6 + R ⚙️. Turn signals are mapped to the paddles. `UsePressedButtonsForGearBox` is set to `true`.
* **`presets/City Car Driving Home Edition/Logitech_G923_Xbox_PaddleShift_GPSDial.xml`**: Preset optimized for using the wheel paddles for sequential shifting 🕹️. Turn signals are mapped to the +/- buttons. H-Shifter positions are *not* bound by default in this preset. `UsePressedButtonsForGearBox` is set to `false`.
* **`aliases/Logitech_G923_TRUEFORCE_Racing_Wheel_XBOX_USB.xml`**: The necessary alias definition file that translates raw inputs into readable names used by the presets. **This file MUST be installed correctly.**

## Installation 🔧

1.  **Download Files:** Download the `.xml` files from this repository (you can clone it or download a ZIP).
2.  **Locate CCD Config Folder:** Find your City Car Driving installation directory. Inside, navigate to the configuration folder. The typical path for Steam installations is:
    * `C:\Program Files (x86)\Steam\steamapps\common\City Car Driving\data\config\bindings`
    * *(This path might differ based on your installation location or game version.)*
3.  **Copy Alias File:** Place the `Logitech_G923_TRUEFORCE_Racing_Wheel_XBOX_USB.xml` file into the `aliases` subfolder within the `bindings` folder.
    * Example full path: `...\bindings\aliases\Logitech_G923_TRUEFORCE_Racing_Wheel_XBOX_USB.xml`
4.  **Copy Preset Files:** Place the two preset files (`Logitech_G923_Xbox_HShifter_GPSDial.xml` and `Logitech_G923_Xbox_PaddleShift_GPSDial.xml`) into the correct subfolder within `presets`. Based on the structure provided, this is likely `presets/City Car Driving Home Edition`.
    * Example full path: `...\bindings\presets\City Car Driving Home Edition\Logitech_G923_Xbox_HShifter_GPSDial.xml`
5.  **Launch City Car Driving:** Start the game.
6.  **Select Preset:** Go to the control settings menu. You should now be able to select either `"Logitech G923 Xbox + H-Shifter (GPS Dial)"` or `"Logitech G923 Xbox + Paddle Shift (GPS Dial)"` from the list of available presets. Choose the one that matches your preferred shifting style.
7.  **Verify Settings:** Briefly check the axis assignments (Gas, Brake, Clutch, Steering) and test them. They should now respond correctly (0% when released, 100% when pressed) thanks to the inversion parameters in the files. While the XML *should* handle inversion, double-checking the "Invert Axis" checkboxes within the game's UI for the pedals is always a good final step. Assign any remaining unbound actions as desired.

## Feedback and Issues

If you encounter problems or have suggestions for improvement, please open an issue on this GitHub repository.

## Support the Creator (OxFaTech) ⭐

A lot of trial and error went into figuring this out! If you find these presets helpful, consider supporting the creator:

* **Ko-fi:** [https://ko-fi.com/oxfatech](https://ko-fi.com/oxfatech)
* **PayPal:** [https://www.paypal.com/donate/?hosted_button_id=DX93QEVJU725U](https://www.paypal.com/donate/?hosted_button_id=DX93QEVJU725U)

## Check Out LufatZ's Projects! ⭐

These presets were created by LufatZ (OxFaTech). Check out his projects:

* **DayOfMind (Minecraft Modpack):** [Modrinth Page](https://modrinth.com/modpack/dayofmind)
* **DayOfMind-Additions (Minecraft Mod):** [Modrinth Page](https://modrinth.com/mod/dayofmind-additions)

## Hosting Partner Recommendation ⭐

Need reliable game server hosting? Consider checking out **BisectHosting**!
Use the code DAYOFMIND [check it out](https://www.bisecthosting.com/clients/aff.php?aff=3251)
[![](https://wsrv.nl/?url=https%3A%2F%2Fwww.bisecthosting.com%2Fimages%2FCF%2FDayofMind_revamp%2Fbh_promo.png&n=-1)](https://www.bisecthosting.com/clients/aff.php?aff=3251)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
