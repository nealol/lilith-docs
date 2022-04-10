## Troubleshooting
- If none of the solutions below work for you, please create a ticket in the [Lilith Discord Server][LilithDiscord] or ask in #support.

<!--- Lilith Not Running --->
<details>
  <summary>
    Java.net connection excpetion In Game</summary>


   When you connected to localhost you didn't make sure to have Lilith running while you were doing so. Please launch Lilith and keep it running while you are connected to localhost.

</details>

<br/>

<!--- Socket Closed --->
<details>
  <summary>
    End, SocketClosed</summary>
  

  You have not added your details to your TOML file, or if you have, they were added improperly. Please see the examples above in the `Inserting Your Credentials` section of this guide to ensure you entered your details properly.


  Note: If you are changing your TOML file, be sure to save it and relaunch Lilith to load your changes properly. 

</details>

<br/>

<!--- TOML Syntax Error --->
<details>
  <summary>
    Bad Atom Value at line ___</summary>
  

  You didn't format your TOML file properly according to the `Inserting Your Credentials` section in the guide and Lilith is rejecting the improper formatting. Please see the examples above to ensure it is formatted correctly.


  Note: If you are changing your TOML file, be sure to save it and relaunch Lilith to load your changes properly.

</details>

<br/>

<!--- TOML Syntax Error --->
<details>
  <summary>
    Unexpected token in JSON at position ___</summary>
  

  You didn't format your TOML file properly according to the `Inserting Your Credentials` section in the guide and Lilith is rejecting the improper formatting. Please see the examples above to ensure it is formatted correctly.


  Note: If you are changing your TOML file, be sure to save it and relaunch Lilith to load your changes properly.

</details>

<br/>

<!--- Wrong Account Authentication Fix --->
<details>
  <summary>
    Lilith Is Logging In to the Wrong Account</summary>
  

  When you were authenticating either a main or an alt with Microsoft you accidentally signed in with a Microsoft account that was not associated with the ign you were trying to log in with.


  1. Close Lilith and Minecraft
   

  2. Navigate to your .Minecraft folder


  3. Find the JSON cache files that start with a bunch of random characters and delete them. There should be 3 of these per account you use.


  4. Relaunch both Lilith and Minecraft and reauthenticate with Micorosft on each account. Remember to authenticate each ign with the proper Microsoft account associated with it. You may have to click `sign in with a different Microsoft account` to do so.

</details>

<!--- Links --->
[LilithDownload]: https://github.com/GhqstMC/LilithReleases/releases/download/0.6.0-alpha.3/lilith-win-0-6-0-alpha-3.exe
[LunarClientQT]: https://github.com/Nilsen84/lunar-client-qt
[JavaByteCode]: https://en.wikipedia.org/wiki/Java_bytecode
[LilithDiscord]: htt[s://discord.gg/lilith
[LilithDocsFAQ]: https://docs.lilithmod.xyz/#/FAQ
