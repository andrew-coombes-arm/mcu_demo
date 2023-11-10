# What have I done so far?
* Created github repo (mcu_demo)
* Installed GitHub codespaces in Visual Studio
* Logged in, selected repo mcu_demo
* [Visual Studio] Install **Arm Virtual Hardware** into my codespace
* [Visual Studio] Install ~~Arm Remote Build~~ into my codespace
  * From Arm Remote Build, select "Extension Resources" &gt; Repository
  * BUT: documentation in the repo doesn't tell us anything useful
  * *Uninstalled this*
* [Visual Studio] Install **Keil Studio Pack** into my codespace
  * Activate license `>keil-studio.activate-tools-license`
  * Follow https://developer.arm.com/documentation/108029/0000/Get-started-with-an-example-project
    * This leads to the file being built, but is built for a specific hardware target. Not a virtual one.
