# Debloated MIUI 12 (Poco X3 NFC)

**I don&#39;t know if this will work on other MIUI based ROMs so if you want to try it be my guest and let me know how it goes** U/Blothen

P.S. Not everything in this repo belongs to me, some are scripts I found.

Key things to note;

1. You will have to void your warranty to get to this point.
2. If you mess up don&#39;t panic flash anything!
3. Nearly most of, if not all the MIUI Bloat will be disabled (depending on what you pick).
4. This will Wipe your data.

Steps;

1. Please make sure you have an unlocked bootloader; this can be done by going to the settings app \&gt; about phone \&gt; all specs \&gt; clicking on the MIUI version until you have developer options \&gt; home of settings \&gt; scroll down \&gt; additional settings \&gt; developer options \&gt; Mi unlock status
2. (POCO X3 NFC ONLY) After you have an unlocked bootloader flash either orange fox or TWRP (both are in the repo), follow the steps included for either one. Orange fox: [https://telegra.ph/How-to-install-Orange-Fox-for-Poco-X3-09-25](https://telegra.ph/How-to-install-Orange-Fox-for-Poco-X3-09-25) TWRP : [https://forum.xda-developers.com/t/recovery-3-5-0-0-unofficial-twrp-xiaomi-poco-x3-surya-karna.4168511/](https://forum.xda-developers.com/t/recovery-3-5-0-0-unofficial-twrp-xiaomi-poco-x3-surya-karna.4168511/)
3. Wipe your entire phone in either, recovery then download MIUI for your POCO X3 Variant [https://xiaomifirmwareupdater.com/miui/surya/](https://xiaomifirmwareupdater.com/miui/surya/)
4. Flash MIUI and download magisk [https://github.com/topjohnwu/Magisk](https://github.com/topjohnwu/Magisk)
5. Flash magisk and reboot
6. Once the phone has booted and completed setup go and repeat step 1 up until you have enabled developer options, one you have go into developer options and enable Install via USB (This is necessary to hide magisk and pass SafetyNet) ![](RackMultipart20210201-4-16zpxov_html_9080587004b12316.jpg)

7. Once that is enabled go into magisk manager \&gt; settings \&gt; scroll down \&gt; hide magisk manager
8. Next flash SafetyNet Fix in magisk and reboot SafetyNet will pass now, so don&#39;t worry about banking apps detecting or refusing to work.
9. This is step is necessary! Go into settings \&gt; Passwords and security \&gt; Authorisation and revocation and make sure to disable Security
10. Install /d/gapps and click grant, here you can click on disable on all, be careful with google and only click on Delete Without GMS if you want to keep play services
11. Next flash the other magisk module called MIUI Plus Full Debloat but don&#39;t reboot next flash MIUI Gapps keep only
12. Reboot now and you should be heavily debloated, most of the bloat left behind is necessary for the phone to run smoothly