# My Visual Studio Code settings

These few files are capturing my Visual Studio Code settings.
They help a lot to code, manage repo, interact with Azure, develop PowerShell and bash scripts, Azure Pipelines, Kubernetes YAML, Terraform plans, etc. on Windows 11 (but works with Windows 10 also).

## Installation steps

1. Install Visual Studio Code

   Installation comes in few flavors. They all start from here: <https://code.visualstudio.com/Download>

2. Launch a cmd/Command Prompt

   Copy/Paste the commands that installs the extensions you want to get in your context, from the file named `VSCode-Extensions.cmd`.

   It is not formatted as a batch/bat script that can be run directly. I recommend starting with Copy/Paste to see how it gradually changes your Visual Studio Code environment.

3. Edit Visual Studio Code user' settings

   VS Code stores your user settings by default in this location: `C:\Users\<your user name>\AppData\Roaming\Code\User\settings.json`.

   Open this file and edit it adding the settings from the `VSCode-settings.json` file.
   The VS Code settings UI can also be used `File > Preferences > Settings`.

4. Optional: Install 'Fire Mono' font

   In the settings file, to get a beautiful look with the **Atom One Dark Theme**, I install the **Fira Mono** font and reference it in the `"editor.fontFamily"` setting.

   To install the Font, visit the [Fira](https://github.com/mozilla/Fira) github repo and download the TTF version of the Regular font, which is here: <https://github.com/mozilla/Fira/blob/master/ttf/FiraMono-Regular.ttf>

   Once downloaded, double-click on it, it opens the Font display windows, Font name being "Fira Mono". Click on "Install".

   I also added the TTF file in this directory.
