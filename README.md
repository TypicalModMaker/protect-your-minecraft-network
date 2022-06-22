# How to hide your bungeecord properly

In this repository I will teach you how to **hide** your Minecraft server from **griefers** like me!\
You might be asking, who is this guy and why does he want me to do stuff to my server?!\
I am a griefer. This might happen if your server **is not secure**!: [Video #1](https://www.youtube.com/watch?v=-_N-j7jamjQ&), or this [Video #2](https://www.youtube.com/watch?v=ricF53F6fDE&t=118s), or even this! [Gif #1](https://cdn.discordapp.com/attachments/929111080276467723/989227429828653066/80k.mp4), **80k IPS dumped with MD5 encrypted passwords** 

Now you probably think that I am a bad person and that I am not trustworthy! Well **you are wrong**! Over **20 people trust me** with their server security! If you want to contact some of them: 
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

Rest is coming soon....
