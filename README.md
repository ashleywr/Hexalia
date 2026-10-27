![Hexalia Logo](https://cdn.modrinth.com/data/cached_images/2b1665e3b0004e479a5ac6476a61e12d31ab6271_0.webp)
<hr>

### **About**

Hexalia is a nature-bound magic mod centered on rituals, herbal alchemy, and living flora.

Gather wild herbs and cultivated crops, refine them through simple tools, and shape their essence using salt and elemental forces. Awaken enchanted plants that breathe life into your surroundings, brew potent mixtures with layered effects, and craft idols capable of bending weather or cleansing what has been corrupted.

From transmuting the world through Mutavis and Morphora, to flowing through water with the Kelpweave Blade or unleashing volatile herbal concoctions, Hexalia offers a grounded yet expressive form of magic—one that grows alongside survival, exploration, and the world itself.

Make sure to check out our [Wiki](https://github.com/GrapeStudios/Hexalia/wiki) to know more about the features.

## Additional Information

Hexalia is a work in progress. More features will be added over time. Follow our development journey on Discord and GitHub.

[Discord](https://discord.gg/fcbH6BqW3X) | [GitHub](https://github.com/GrapeStudios/Hexalia)

<!-- ashley-release-information -->

## My builds

This is an unofficial maintenance fork. Original authors retain ownership and credit. See the [upstream project](https://github.com/AstralyaStudios/Hexalia) for the original mod. Local changes do not imply upstream endorsement.

Licensing: **MIT**. Existing license files, copyright notices, attribution and any separate asset terms remain in force. This fork does not relicense upstream work.

Provided **AS IS**, without warranty of any kind. Maintenance, updates and support are best effort; compatibility with every modpack is not guaranteed.

### Downloads and installation

Download a runtime `.jar` from [GitHub Releases](https://github.com/ashleywr/Hexalia/releases). Use the Minecraft version and loader named in that release and install its required dependencies. Do not install `-sources`, `-dev`, `-slim`, `-common` or test JARs as the mod.

Close Minecraft, back up your world, and place the matching runtime JAR in the instance's `mods/` directory. Replace older versions of this same mod rather than loading duplicates. For content mods, install matching versions on the server and its clients unless the release explicitly says client-only or server-only.

### Building and reporting problems

Use Java 21 and the checked-in Gradle wrapper:

```powershell
.\gradlew.bat :neoforge:build
```

Build outputs are under `build/libs/` or each loader subproject's `build/libs/`. Some projects require the local development dependencies described above; those dependencies are not included in the download.

For a problem report, include the exact release filename, Minecraft and loader versions, relevant mod versions, `logs/latest.log`, and a crash report if one was written. Remove private information before sharing logs. Remove the JAR to uninstall; worlds containing this mod's blocks, entities or world generation may require restoring a backup.
