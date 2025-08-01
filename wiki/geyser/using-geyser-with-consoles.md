---
title: Using Geyser with Consoles
description: Information on how to use Geyser with consoles, including how to join servers on console versions of Bedrock Edition.
---

# Using Geyser with Consoles

All consoles can join third-party servers - including Geyser servers - with workarounds. Xbox One, Nintendo Switch, and PS4 systems can join third-party servers using a third-party program called BedrockConnect. For technical information about the program, including how to run your own setup, see [their GitHub repository](https://github.com/Pugmatt/BedrockConnect) (*This program is not affiliated with GeyserMC*). Other methods are also available for use.

<!--There is also a tool anyone can set up that allows you to connect to the server via adding a user to your friends list - [FriendConnect](https://github.com/jrcarl624/FriendConnect), and [MCXboxBroadcast](https://github.com/rtm516/MCXboxBroadcast). The latter one can even be set up as a Geyser Extension.-->

:::note

The main IP used for BedrockConnect is often blocked on consoles, 
if you run into issues with internet connection or joining servers after changing your DNS, 
consider using either one of the other BedrockConnect servers on the [BedrockConnect Github Page](https://github.com/Pugmatt/BedrockConnect), 
or the [Public GeyserConnect](https://www.geyserconnect.net) which allows connecting to both Java and Bedrock servers.

:::

## Xbox One {#xbox-one}

(Video linked below)

[![Xbox One BedrockConnect](https://img.youtube.com/vi/g8mHvasVHMs/0.jpg)](https://www.youtube.com/watch?v=g8mHvasVHMs)

## Nintendo Switch {#nintendo-switch}

(Video linked below)

[![Nintendo Switch BedrockConnect](https://img.youtube.com/vi/zalT_oR1nPM/0.jpg)](https://www.youtube.com/watch?v=zalT_oR1nPM)

Text directions:
1. Select “System Settings” from the HOME Menu of your Nintendo Switch console.
2.  Select “Internet”, and then “Internet Settings”. Your Nintendo Switch console will automatically search for nearby Wi-Fi signals.
3.  Select your network from the list of networks located under “Registered Networks”.
4.  Select “Change Settings”, then scroll down and select "DNS Settings".
5.  Select "Manual".
6.  Select "Primary DNS" with the A Button, and then hold down the B Button to delete the DNS (it defaults to zeros).
7.  Enter the BedrockConnect IP for the preferred Primary DNS (Multiple options depending on region can be found on the [BedrockConnect Github Page](https://github.com/Pugmatt/BedrockConnect)).
8.  Select "Secondary DNS" with the A Button, and then hold down the B Button to delete the existing DNS.
9.  Enter a secondary DNS. Google's or Cloudfare's IP (8.8.8.8 or 1.1.1.1) are recommended.

## PlayStation 4 {#playstation-4}

1. Go to your PS4 Home screen.
2. Go to Settings.
3. Go to Network.
4. Select Set Up Internet connection.
5. If you are using wired internet, select "Use LAN Cable", otherwise choose "Use Wi-Fi".
6. Select the Custom network creation mode.
7. Select Automatic IP Address.
8. For DHCP Host Name, make sure you select Do Not Specify.
9. Under DNS Settings, select Manual.
10. Enter the BedrockConnect IP for the preferred Primary DNS (Multiple options depending on region can be found on the [BedrockConnect GitHub Page](https://github.com/Pugmatt/BedrockConnect)) and something like Google or Cloudflare's IP for the Secondary DNS (8.8.8.8 or 1.1.1.1).

## Alternative Methods {#alternative-methods}

If you'd rather try emulating a LAN game on your network on another device, here's how you'd do that.

*Note that this method will not work with the Nintendo Switch.*

### Using a PC {#using-a-pc}
If you have a PC, you can use [Phantom](https://github.com/jhead/phantom).

### Using an Android Device {#using-an-android-device}
If you have an Android device, you have several options:
- [BedrockTogether](https://play.google.com/store/apps/details?id=pl.extollite.bedrocktogetherapp)
- [MC Lan Proxy (Trial)](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroidtrial)
- [MC Lan Proxy (Paid)](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroid)
- [MC Server Connector](https://play.google.com/store/apps/details?id=com.smokiem.mcserverconnector)

### Using an iOS device {#using-an-ios-device}
If you have an iOS 14+ device, you can use [BedrockTogether](https://apps.apple.com/app/bedrocktogether/id1534593376).
