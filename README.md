![Chromatics Logo](http://thejourneynetwork.net/chromatics/chromatics_black_md.png)

**Lighting Effects for Final Fantasy XIV**

Chromatics is a plugin for Advanced Combat Tracker (ACT) which connects Final Fantasy XIV (and other ACT compatible games) with Razer Chroma, Logitech & Corsair RGB devices. You can use this to make your keyboard, mouse, headset, etc. react to events, custom triggers, timers & other in-game functions by creating visual alerts using the devices' countless lighting options.


[Download Latest Version](https://github.com/roxaskeyheart/Chromatics/releases)




##Features


* Set a device default color universally while ACT is running.
* Change color of devices when enmity is generated.
* Create alerts when Custom Triggers activate with adjustable rate & speed.
* Create alerts when Timers are triggered.
* Create alerts for receiving chat messages.
* Raid Mode for creating special effects when in Raiding instances.
* Vegas Mode for Gold Saucer. (Razer devices only at current release).
* Device manager to enable/disable devices in ACT (partially implemented).


![Settings](http://thejourneynetwork.net/chromatics/chromatics_settings.png)



##Device Compatibility


**Razer Chroma**
* BlackWidow Chroma
* BlackWidow TE Chroma
* DeathAdder Chroma
* DeathStalker Chroma (Partial)
* Diamondback (Partial)
* Firefly
* Kraken 7.1 Chroma
* Mamba TE Chroma
* Orbweaver Chroma
* Tartarus Chroma


**Logitech RGB**
* G910 Orion Spark
* G710+
* G633 & G933
* G600
* G510/G510s
* G110
* G19/G19s
* G105
* G105 COD
* G300
* G303 Daedalus Apex
* G11
* G13
* G15


**Corsair CUE**
* CGK65 RGB
* K70 RGB
* K95 RGB
* STRAFE
* STRAGE RGB

*Please note: Logitech & Corsair RGB devices are untested at this current point in time*




##Prerequisites


* [Advance Combat Tracker](Advanced Combat Tracker -- An MMO Combat Log Parser) with FFXIV Plugin
* [Razer SDK](http://www.razerzone.com/au-en/synapse) (Automatically installed with Razer Synapse) - *For Razer device support*
* .Net Framework 4.5 (Full)




##Installation


1. Download the [latest version](https://github.com/roxaskeyheart/Chromatics/releases) of Chromatics.
2. Unzip the contents of Chromatics_x64 to your computer. (Recommend ACT Plugins folder)
3. Turn on Chroma Apps in Razer Synapse (Synapse > Chroma Apps > Enable).
4. Open Advance Combat Tracker.
5. Browse to the extracted Chromatics_x64 directory and select the Chromatics.dll.
6. Browse to your ACT installation directory and select the Chromatics.dll in the Chromatics folder.
7. Select Add/Enable Plugin. 
8. A new Chromatics tab will appear, select this to customize settings.




##FAQ


**Q: How do I find out if my device is compatible with Chromatics?**


A: You can find a list of currently supported devices above under Device Compatibility.




**Q: Do you plan to add support for other RGB devices outside of Razer Chroma, Logitech RGB & Cosair?**


A: I am currently working to finish implementing Corsair mouse and headset support. I will be looking at other devices later on if their is high demand.




**Q: Is there a 32-bit version of Chromatics available?**


A: Unfortunately there is not a 32-bit version available due to device limitations. I am currently investigating this further.




**Q: I added the plugin to ACT and it shows an error message or crashes ACT.**


A: Make sure you have the latest versions of Razer Synapse, ACT and the FFXIV ACT Plugin installed on your computer before running Chromatics. Also check that you are running a 64-bit Operating System. Restarting ACT has also been known to fix errors similar to this. If you continue to have problems, please submit a [bug report](https://github.com/roxaskeyheart/Chromatics/issues) with your ACT log.




**Q: I'm getting a message saying Razer SDK cannot be found.**


A: Please reinstall or update [Razer Synapse](http://www.razerzone.com/au-en/synapse) (64-bit). This is not required if you are only using Logitech RGB devices.




**Q: I have everything setup but I can't see anything happening on my devices?**


A: Make sure Chroma Apps is turned on in Razer Synapse (Synapse > Chroma Apps > Enable) and that ACT is listed in the App List.




**Q: Will Chromatics work with other games and not just Final Fantasy XIV?**


A: Yes and No. Some core features of Chromatics such as Enmity Change, Custom Triggers and Timers will work, but Chat and Special alerts are only designed to work with Final Fantasy XIV. Additionally other games are untested.




**Q: When setting up chat notifications, I get notified when I send a message as well as when I relieve one. Can I set it to only notify me when I receive a message?**


A: This is currently a limitation of the FFXIV Parsing plugin. I am currently investigating to add this functionality in a future release.




**Q: The device controls don't work or only partially work correctly.**


A: The Device manager is only partially implemented as of 1.1.x. There will be bugs in using it which will be resolved in a future patch.




**Q: I have an idea for Chromatics. Will you implement it?**


A: Please submit a [feature request](https://github.com/roxaskeyheart/Chromatics/issues) and I'll see what I can do.




**Q: I'm a developer too! Can I help you develop Chromatics?**


A: For sure! Please contact me on Github for more information. Chromatics is built in C#. 






##Known Issues


* Device selection only partially implemented.
* An issue in which Chromatics may cause ACT to crash if the plugin is removed and re-added to ACT without restarting ACT in-between.
* Untested on Logitech RGB devices.
* Untested on Corsair RGB devices.
