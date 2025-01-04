# Solin - No Recoil Application

**Solin** is a versatile no recoil and rapid fire application that enhances your gaming experience by reducing recoil and providing various customization options. Whether you’re playing FPS games or other types of action games, Solin gives you the flexibility to adjust and fine-tune recoil settings, toggle rapid fire, and more.



<img src="https://i.imgur.com/OEr9ucS.png">

## Features

- **No Recoil Adjustment**: 
  - Adjust the strength of no recoil by modifying an integer value to find the perfect balance for your gameplay.
  - Toggle the **No Recoil** feature only when aiming down sights (ADS), for a more realistic experience.

- **Rapid Fire for Pistols**:
  - Activate rapid fire functionality for pistols with a simple toggle. This makes semi-automatic pistols fire like automatic weapons for enhanced speed.

- **Preset Configurations**:
  - Save custom presets for your favorite guns, settings, or playstyles. Easily switch between your preferred configurations with just a few clicks.

- **Customizable GUI**:
  - Change the color theme of the user interface to match your personal preference or the aesthetics of your system.
  - Built using the powerful **ImGui** GUI library, ensuring smooth performance and ease of use.

## Installation

1. **Download** the latest version of Solin from the releases section (or from the link provided).
2. Extract the files to a desired location on your computer.
3. Launch `Solin.exe` (or the equivalent for your platform).

**Note**: Ensure that you are using the application legally and ethically in accordance with the game's Terms of Service.

## Usage

### Key Features

- **Toggle No Recoil**:
  - You can enable/disable the no recoil feature using the GUI.
  - Adjust the recoil strength by modifying the **No Recoil Strength** integer slider. Higher values result in more recoil reduction.
  - Enable **No Recoil while ADS'ing** if you prefer recoil control only when aiming down sights.

- **Toggle Rapid Fire**:
  - Rapid Fire can be toggled specifically for pistols. This will simulate automatic fire for semi-automatic pistols.
  
- **Save and Load Presets**:
  - You can save your favorite settings and configurations for different guns or playstyles.
  - Presets can be loaded quickly through the **Config** menu.

- **Customize GUI**:
  - Open the **Settings** tab and use the color picker to change the GUI theme to your liking.

### Example Use Case

- **Adjusting Recoil**:
  - Open the Solin application.
  - Select your game from the list (if applicable).
  - Adjust the No Recoil Strength slider to your desired level.
  - Toggle the option to have no recoil only while ADS'ing.
  - Press "Save Preset" to save your custom settings for future use.

- **Enabling Rapid Fire for Pistols**:
  - In the application, simply toggle the **Rapid Fire** option for pistols.
  - Adjust the rate of fire if required.
  - This will affect your gameplay the next time you use pistols in supported games.

## Configuration File

- Solin allows you to configure and save presets for different weapons, recoil strengths, and gameplay preferences.
- The **config.json** file can be manually edited to fine-tune settings, or you can use the in-app options for easy access to saving/loading configurations.

Example of a saved configuration:

```json
{
  "preset_name": "AK47_NoRecoil",
  "no_recoil_strength": 5,
  "rapid_fire_enabled": false,
  "no_recoil_while_ads": true
}
