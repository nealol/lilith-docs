## Optional Enhancements

### Free

<!--- Hypixel Mods Enable --->
<details>
  <summary>
    Enable Hypixel Mods</summary>


  1. Ensure Lilith, Lunar, and all files relating to Minecraft are closed. Also ensure the Lunar Enable bypasses are off. You can do this by settings `lunar = true` to `lunar = false` in your config, if it isn't already `false`. 
  Note: If you need to use Lunar Enable we reccomend using [Lunar Client QT][LunarClientQT], an open source custom launcher for Lunar. It lets you add custom mods to Lunar called agents that are similar to forge mods in nature. Please note most forge mods won't work with it, as the only agents that will work with it are specially written ones made in [Java Byte Code][JavaByteCode]. Popular agents include an unlocker for Lunar+, every emote, and every cosmetic, similar Lunar bypasses to the ones Lilith offers, and a customizable hurtcamera.
  2. Find the search icon/bar at the bottom of your screen and type Notepad into the searchbar; you should see the Notepad app pop up as an option. DO NOT open it yet.
  3. Right-click on it ad select Run as Administrator. Youll be asked if you want to "allow this app to make changes to your device?". Click Yes.
  4. Now that you are running Notepad as an admin, in the top right of the window click File then Open.
  5. Navigate to `C:` -> `Windows` -> `System32` -> `drivers` -> `etc`. This folder may appear blank at first. To show all files, click the dropdown box in the bottom-right of file explorer titled `Text Documents .txt`, then select `All Files`.
  6. Double-Click on hosts to open it. You may see several lines starting with `#`. Create a new line at the very bottom of the file below all of the lines starting with `#`.
  7. Paste the following into that bottom line: `127.0.0.1 hypixel.net.hypixel.io`. Next, save your hosts file and close it.
  8. Relaunch Lilith and Lunar like normal.
  9. Change Your Lilith/localhost server address from `localhost` to `hypixel.net.hypixel.io` before connecting.

</details>

<br/>

<!--- Adding Alts --->
<details>
  <summary>
    Add Alts</summary>


  Note: Lilith WILL NOT support Mojang accounts in 1.0.
  1. Ensure Lilith and Lunar are closed.
  2. Navigate to the TOML file in your Lilith folder where you previously entered the details of your main minecraft account. Scroll down to the `[server.authentication]` portion of your TOML file. You should see the place where you entered you main's details. You are going to enter your alt's details following the exeact same formatting you used for your main.
  3. Copy the entire line with your main's details to your clipboard by pressing `ctrl` + `c`
  4. Create a new line right underneath the line with your main's details. Paste the line you just copied into this new line.
  5. Replace the ign and email portions in this new line with your alts details following the same formatting rules as you did with your main.
  6. Save your toml file and close it. Launch Lilith and Minecraft.In Minecraft, sign into your alt and connect to the Lilith localhost server.
  7. Just like you did with your main, authenticate with Microsft with the email associated with the ign you are trying to log in with. You may have to click on `sign in with a different microsoft account` to choose the right email to sign in with.
  8. To add more alts just follow the above steps to add a new alt on each line and authenticating each one with microsoft one by one.

</details>

### Requires Premium

<!--- Aquiring Premium --->
<details>
  <summary>
    How to Get Premium</summary>


  If you would like to purcahse premium please DM an admin or developer. You can contact us via the [Lilith Discord Server][LilithDiscord]. Licenses are $10 for lifetime access to all Lilith premium updates and features. Server boosters will also receive 1 month of premium for each month they boost the server.

</details>

<br/>

<!--- One-line Stats --->
<details>
  <summary>
    Custom Queuestats</summary>

  Note: This feature has been temporarily DISABLED until 1.0 releases.

</details>

<br/>

<!--- Autododge --->
<details>
  <summary>
    Autododge</summary>
  

  Note: This feature has been temporarily DISABLED until 1.0 releases.

</details>