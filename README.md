# ObsidianPlugin
A Template Repository for building [Obsidian](https://github.com/Naamloos/Obsidian) plugins. Make sure to rename the assemblies to ensure compatibility with other plugins.

## How to use
1. Go to the Code tab and click Use This Template and select Create a New Repository.
2. Rename the assemblies to match your plugin name.
3. Delete the ServerFiles directory.
4. Clone your repository to your computer, then open GitBash and run this command: `git submodule add --name Obsidian https://github.com/ObsidianMC/Obsidian ./submodules/ServerFiles`
  * This command should be run in the same directory as your .sln file.
6. Open the solution in your preferred IDE, such as Visual Studio or Rider.

Obsidian.API.dll should now automatically be loaded by your IDE, and debugging with the server _should_ work now.
