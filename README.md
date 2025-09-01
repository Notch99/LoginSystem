# Minecraft Forge Mod

This repository contains the source code for a Minecraft Forge mod.

## Installation Instructions

This mod follows the Minecraft Forge installation methodology. Please refer to the official Minecraft Forge documentation for detailed setup instructions.

### Setup Process:

**Step 1:** Open your command-line and browse to the folder where you extracted the mod files.

**Step 2:** Choose your preferred IDE:

*   **If you prefer to use Eclipse:**
    1.  Run the following command: `./gradlew genEclipseRuns`
    2.  Open Eclipse, then go to `Import > Existing Gradle Project > Select Folder`.
    *Alternatively, you can run `gradlew eclipse` to generate the project.*

*   **If you prefer to use IntelliJ:**
    1.  Open IDEA and import the project.
    2.  Select your `build.gradle` file and import it.
    3.  Run the following command: `./gradlew genIntellijRuns`
    4.  Refresh the Gradle Project in IDEA if required.

**Troubleshooting:**
If you are missing libraries in your IDE or encounter any problems, you can run:
*   `gradlew --refresh-dependencies` to refresh the local cache.
*   `gradlew clean` to reset everything (this does not affect your code), then restart the process.

## Mapping Names
By default, the MDK is configured to use the official mapping names from Mojang for methods and fields in the Minecraft codebase. These names are covered by a specific license. All modders should be aware of this license. If you do not agree with it, you can change your mapping names to other crowdsourced names in your `build.gradle` file. For the latest license text, refer to the mapping file itself, or the reference copy here: [Mojang Mapping License](https://github.com/MinecraftForge/MCPConfig/blob/master/Mojang.md)

## Additional Resources:
*   Community Documentation: [https://docs.minecraftforge.net/en/1.20.1/gettingstarted/](https://docs.minecraftforge.net/en/1.20.1/gettingstarted/)
*   LexManos' Install Video: [https://youtu.be/8VEdtQLuLO0](https://youtu.be/8VEdtQLuLO0)
*   Forge Forums: [https://forums.minecraftforge.net/](https://forums.minecraftforge.net/)
*   Forge Discord: [https://discord.minecraftforge.net/](https://discord.minecraftforge.net/)

## Changelog
For a detailed list of changes and updates, please refer to the [changelog.txt](changelog.txt) file.

## License
This project is licensed under the terms of the LGPL 2.1. For full details, please see the [LICENSE.txt](LICENSE.txt) file.

