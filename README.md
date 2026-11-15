# Digimon PS2 Mobile Launcher v1.1
Open this project in Android Studio with JDK 17; wait for Gradle sync; choose Build > Build APK(s).

The launcher can select a PS2 game document (.iso/.chd), persist its URI, and try direct launch with the commonly documented AetherSX2 contract: package `xyz.aethersx2.android`, activity `.EmulationActivity`, action MAIN, extra `bootPath` containing the document URI. It falls back to opening emulator home if direct launch is unavailable. Some emulator forks use a different package/activity and may require editing the candidate list in MainActivity.java.

Install and configure a compatible NetherSX2/AetherSX2 build first, import your own PS2 BIOS, then choose a game image made from a disc you own. This launcher is not an emulator and includes no BIOS or game. Vulkan + 1x Native is a suggested starting point, not an FPS guarantee.
