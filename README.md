# Utilities Function CommandletPlugin

Unreal Engine 4 commandlet plug-in contain utilities to query and wrangle assets.

## Usage

You can use this plug-in as a project plug-in, or an Engine plug-in.

If you use it as a project plug-in, clone this repository into your project's
*/Plugins* directory and compile your game in Visual Studio. A C++ code project
is required for this to work.

If you use it as an Engine plug-in, clone this repository into the
*/Engine/Plugins/Media* directory and compile your game. Full Unreal Engine 4
source code from GitHub is required for this.

After compiling the plug-in, you have to **enable it** in Unreal Editor's
plug-in browser.

Use the *-run* command line parameter to run one of the commandlets in this
plug-in, i.e. *YourGame.exe -run=Utils*
