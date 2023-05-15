# How to hide your bungeecord properly

In this repository I will teach you how to **hide** your Minecraft server from **griefers** like me!\
You might be asking, who is this guy and why does he want me to do stuff to my server?!\
I am a griefer. This might happen if your server **is not secure**!: [Video #1](https://www.youtube.com/watch?v=-_N-j7jamjQ&), or this [Video #2](https://www.youtube.com/watch?v=ricF53F6fDE&t=118s), or even this! [Gif #1](https://cdn.discordapp.com/attachments/929111080276467723/989227429828653066/80k.mp4), **80k IPS dumped with MD5 encrypted passwords** 

Now you probably think that I am a bad person and that I am not trustworthy! Well **you are wrong**! **Over 20 people trust me** with their server security! If you want to contact some of them: 
1. Viremox#0001, https://discord.gg/minecraftserver
2. tdvne#0001, https://discord.esta.land
3. Swm#0001, https://discord.pvp.zone and https://discord.gg/kloude

⚠️WARNING⚠️\
**Every point flagged with 🟥 Requires a vps/vds/dedicated system. This means that these points wont work if you are using a Minecraft server hosting**

<!--- Idk how to use markdown dont hate me please :) -->
# Sections:

&nbsp;1. Reverse TCP Proxy\
&nbsp;&nbsp;&nbsp;1.1. Choosing the best reverse proxy\
&nbsp;2. UUID Spoofing\
&nbsp;&nbsp;&nbsp;2.1. What is UUID Spoofing?\
&nbsp;&nbsp;&nbsp;2.2. What are the consequences for ignoring this problem\
&nbsp;&nbsp;&nbsp;2.3. On what servers does this design flaw work\
&nbsp;&nbsp;&nbsp;2.4. How to block it\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.4.1. External: IPWhitelist\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.4.2. External: BungeeGuard\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.4.3. Using Velocity protection\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.4.3. Firewalling 🟥\
&nbsp;3. Hide Bungeecord\
&nbsp;&nbsp;&nbsp;3.1. Allow connections only with specific domain, a plugin made by me [Bungeecord only, no velocity support]\
&nbsp;4. Block Port scanning 🟥\
&nbsp;&nbsp;&nbsp;4.1. Firewalling [NOT RECOMMENDED, USE PSAD INSTEAD] 🟥\
&nbsp;&nbsp;&nbsp;4.1. Using psad 🟥\
&nbsp;5. Hide Pterodactyl Panel | Any Pterodactyl Fork 🟥\
&nbsp;&nbsp;&nbsp;5.1. Blocking IOT Scanners 🟥\
&nbsp;&nbsp;&nbsp;5.2. Setting up CloudFlare 🟥\
&nbsp;&nbsp;&nbsp;5.3. Configuring WebServer 🟥\
&nbsp;&nbsp;&nbsp;5.4. Firewalling 🟥\
&nbsp;6. Block ICMP probes 🟥\
&nbsp;&nbsp;&nbsp;6.1. Firewalling 🟥\
&nbsp;&nbsp;&nbsp;6.2. Editing kernel parameters 🟥


### 1. Reverse TCP Proxy:
#### &nbsp;1.1 Choosing the best reverse proxy
&nbsp;&nbsp;There are plenty of reverse proxies available on the internet, most popular ones are: [TCPSHIELD](https://tcpshield.com/), [Infininity Filter](https://www.infinity-filter.com/) and [MC SHIELD](https://mcshield.com/).\
&nbsp;\
&nbsp;&nbsp;I recommend using [EnkiProtect](https://enkiprotect.info/), Its not popular, but its very powerful. It also has alot of features like AntiBot, AntiVPN and  **unlimited traffic!** This is probably the best option you could pick. Check the site for more info.
### 2. UUID Spoofing:
#### &nbsp;&nbsp;&nbsp;2.1. What is UUID Spoofing?
&nbsp;&nbsp;UUID spoofing was first discovered in early 2013, and is now a well-known Bungeecord design flaw - mainly abused to grief servers. This exploit is one of the most used methods to gain administrator privileges on vulnerable Minecraft servers.
#### &nbsp;&nbsp;&nbsp;2.2. What are the consequences for ignoring this problem
&nbsp;&nbsp;Ignoring UUID spoofing will make your server vulnerable and exposed to everyone. This might result in all of your player's ip being leaked, your network getting completly destroyed or even your server being deleted! So you better check if your server is vulnerable ASAP.
#### &nbsp;&nbsp;&nbsp;2.3. On what servers does this design flaw work
&nbsp;&nbsp;This flaw works on every single bungeecord instance (including forks such as flamecord, waterfall) that are connected to Java Edition Servers.
#### &nbsp;&nbsp;&nbsp;2.4. How to block it
##### &nbsp;&nbsp;&nbsp;&nbsp;2.4.1 External: IPWhitelist
&nbsp;&nbsp;&nbsp;&nbsp;IPWhitelist allows to filter out the connections at specific spigot server for specific IP Addresses      https://www.spigotmc.org/resources/ipwhitelist.61/ \
&nbsp;&nbsp;&nbsp;&nbsp;Configuration is pretty simple, check the spigot page for more info.
##### &nbsp;&nbsp;&nbsp;&nbsp;2.4.1 External: Bungeeguard
&nbsp;&nbsp;&nbsp;&nbsp;Bungeeguard allows to add a "token" system to your spigot and bungee server. https://github.com/lucko/BungeeGuard \
&nbsp;&nbsp;&nbsp;&nbsp;Configuration is pretty simple, check the spigot page for more info.

I dont have time to finish this lmao.
Im too lazy but if u want to hire me join my discord and dm me
