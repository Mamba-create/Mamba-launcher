# Mamba Launcher (Java + Bedrock)
Not affiliated with or endorsed by Mojang.

- `start.bat` - run the launcher (installs dependencies on the first run)
- `create-shortcut.bat` - desktop shortcut "Mamba Launcher" with the snake icon
- `build-installer.bat` - builds `dist\Mamba Launcher Setup x.x.x.exe` (Start menu + desktop shortcut)

Java is downloaded automatically for each Minecraft version (Settings -> Java executable: leave empty).

Data (every instance is its own isolated folder, Prism-style):
- Java:    %APPDATA%\.minecraft_java\instances\<id>\minecraft   (libraries/assets/versions/runtime shared in %APPDATA%\.minecraft_java)
- Bedrock: %APPDATA%\.minecraft_bedrock\instances\<id>\com.mojang
- Config:  %APPDATA%\.minecraft_launcher\launcher.json
