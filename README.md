# Reid Sutherland

[LinkedIn](https://www.linkedin.com/in/reiddsutherland/)

## Professional Experience

Resume

## Graduate Research

I received my M.S. in Computer Science from the University of Arkansas in May 2020.

**Masters Thesis**: [Link](https://scholarworks.uark.edu/etd/3686/)

While I was a graduate student there I worked on many research projects and papers in the following fields:
- Machine Learning and AI
- Image and Gesture Recognition
- Wearable Technologies
- Embedded Systems

I was also a Teaching Assistant and taught labs for the following courses:
- Digital Design
- Programming Foundations I
- Embedded Systems

## Hobby Projects

### SCP-SL Plugins

Here are all of the plugins I have created, contributed to and/or maintain for the game: `SCP: Secret Laboratory`.

These plugins are mostly created in C# using the .NET 4.8 framework. They use UnityEngine, [LabApi](https://github.com/northwood-studios/LabAPI), and other code/libraries provided by the [Northwood Studios](https://github.com/northwood-studios) developer team.

#### [Boombox](https://github.com/reid-sutherland/Boombox)

This plugin offers a Radio-based CustomItem (The JBL Speaker a.k.a. "Boombox") that plays music or other audio for players within proximity to enjoy.
- This was entirely my own idea and creation, it is probably the favorite plugin of players on my and my friends' server.
- Users can upload their own audio files for use with the Boombox.
- Utilizes Server-Specific Settings keybinds as well as overriding the build-in radio controls for operation.
- Can also be controlled with client-console commands.

#### [VendingMachine](https://github.com/reid-sutherland/VendingMachine)

This plugin spawns an interactable SCP-294 (Vending Machine).
- Coins can be placed in the machine to receive SCP drinks and other custom drinks!
- These drinks provide a variety of whacky effects with advantages, and also some disadvantages.
- The vending machine also plays ambient music and has sound effects.
- Sometimes players might get lucky and find a Coin With A String for extra uses!

#### [AdvancedMERTools](https://github.com/reid-sutherland/AdvancedMERtools)

I am not the original author of this plugin, but it was not compatible with the newer SCP-SL versions (14.1+) or the EXILED updates (9.6.0+).
So, I overhauled the plugin to use LabApi entirely instead of EXILED for stability, and updated it with some new features.
- Essentially the plugin provides UnityEditor scripts to enable advanced features for MER ([MapEditorReborn](https://github.com/Michal78900/ProjectMER)) Unity schematics, as well as an in-game plugin for loading and managing the behavior and effects of these schematics.
- Currently I am the primary maintainer of the plugin, and many server-owners still use it for their custom schematics and map features.
- Includes features like Custom Colliders, Interactable Objects and Pickups, destoryable Health Objects, and many more.

#### Other plugin contributions

- [Common-Utils](https://github.com/mjacobfahr/Common-Utils)
  - This started as a fork that my friend made so I could fix some bugs.
  - Then I added more features and re-organized the plugin into a Server-Config plugin.
  - Additionally I added a Core plugin that my other plugins can use for commonly shared utility code.
