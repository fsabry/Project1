Command line arguments
==========================================

/noscan - do not scan passwords at startup
/plugins - use plugins
/nodrv - do not use kernel mode driver for reading blocked files
/newlang - MPR will create en.lang file, which you can translate into new language to obtain a free registration key
/extlang - use external language file (ext.lang), can be used to test new translations
/export - automaticly export passwords to an external file

Translation
==========================================

Jaroslav Cizek, DreamWalker[CLS] - Czech  
Dmitry Merzlikin - Ukrainian
Anton Verzijl - Dutch
Hedin - Belarussian
Hevesi Janos - Hungarian
Zeloran - German
Linux2000Pro - Simplified Chinese
DreamWalker[CLS] - Slovak
Cristian Stefan - Romanian
Christian Olaechea M. - Spanish
Ariestya Dibyanugraha - Indonesian
Andrzej Rudnik - Polish
Olga Shyshkina - Italian
M. Bugra AKTAS - Turkish
dboki89 - Croatian
dboki89 - Serbian

Thanks to
==========================================

* Shira for some of the decryption routines

* Beta testers: geney, GOOD, .DN, NIGER, Artix, $ASH, Skratch and others

* geney for the MPR key icon

* David Barton for the DCPcrypt library
http://www.cityinthesky.co.uk

* OpenSSL group, Tim Hudson and Eric Young for the encryption library
http://www.openssl.org

* Andrew Leigh for text scrolling component
http://www.alphalink.com.au/~leigh/components

* Themida software protection system
http://www.oreans.com

Changelog
==========================================


[!] Important
[+] New feature
[*] Improvment
[-] Bugfix


25-Jun-2006, v.0.2.4
[+] English translation
[+] New modules
	+ PocoMail
	+ BulletProof FTP Client
	+ Windows Live Messenger
[*] More supported modules in the wizard
[*] UPX (.exe packer) is not longer used

11-Jul-2006, v.0.2.5
[!] Posibility to delete saved passwords in some modules
[+] New command line argument /newlang, MPR will create en.lang file, which you can translate into new language to obtain free registration key
[+] New modules
	+ Forte Agent
	+ SmartFTP
[+] Recovering passwords from all accounts in the MSN Messenger, improved decryption in versions 7.x
[+] On second scan the tree view control saves position of the selected item
[*] Improved error handling
[*] More modules in the wizard
[*] Speed and size optimizations
[-] Memory leak in Google Talk module

30-Jul-2006, v.0.2.6
[+] Password recovery for the Outlook .pst files
[+] Added support for SmartFTP 2.x
[+] New modules
	+ ASP.NET Account
	+ Remote Desktop Connection (password from Default.rdp file)
[*] More modules in the wizard
[-] Report loading was broken
[-] Fixed some small bugs

18-Sep-2006, v.0.2.7
[!] New interface languages: Ukrainian, Belorussian, German, Dutch
[+] Added Drag & Drop support for loading saved reports
[+] Added decryption for CuteFTP Pro 8
[+] Searching for com-plugins is disabled now by default (speeds up application launching)
[*] Miranda-IM module sometimes didn't find password
[*] Changed some icons
[*] Improved QIP recovery
[-] Improved work with Internet Explorer 7 installed

29-Oct-2006, v.0.2.8
[!] Registration keys are no longer time-limited
[+] New module: The Bee
[+] New interface language: Czech
[+] New Miranda-IM decryption code, added MRA and Gadu-Gadu protocols
[-] Fixed MSN password recovery in Miranda-IM
[-] Sometimes instead of empty passwords there were junk characters

01-Dec-2006, v.1.0 Release
[!] New feature: password audit in all modules
[+] New module: Paltalk
[+] Improved password decryption in the latest versions of Opera Browser
[+] Added support for the Firefox 2.0
[+] New interface language: Hungarian
[+] Improved Bullet Proof FTP file search
[+] Improved Gmail Notifier password decryption
[+] Added IE7 basic auth password recovery
[+] Added information about translators in the 'About' menu
[-] Fixed bug while collecting data from an active IE window

26-Dec-2006, v.1.0.1
[+] New modules: Excite Private Messenger, Gizmo Project
[+] New interface language: Simplified Chinese
[*] Improved Outlook .pst password decryption
[*] Updated Hungarian translation
[-] Mozilla Thunderbird password recovery was broken
[-] Fixed memory leak in Windows / Total Commander decryption module

03-Jan-2007, v.1.0.2
[+] New modules: iScribe/nScribe Email Client, TurboFTP
[*] Size optimizations
[-] Excite Private Messenger long passwords could not be decrypted
[-] Fixed BulletProof FTP 2.5 password recovery
[-] Some Firefox 2.0 passwords could not be decrypted
[-] Fixed SmartFTP password recovery
[-] Fixed FlashGet (JetCar) password recovery

26-Mar-2007, v.1.0.3
[+] New module: FFFTP
[+] New modules in the decryption wizard
[+] Added support for the latest QIP versions
[*] Added support for the latest Mozilla Firefox 2 versions
[*] Added support for the latest Opera Browser (thx 0utC4St)
[-] Fixed few memory leaks
[-] No more password dupes in Firefox module

01-Aug-2007, v1.0.4
[!] You can now order limited Multi Password Recovery registration keys for the lower price. Such keys are valid 7 days only.
[+] New module: FreeCall
[*] Added support for Forte Agent 4.2
[-] Fixed Opera Browser decryption
[-] Fixed Forte Agent password recovery
[-] Fixed few minor bugs

18-Aug-2007, v1.0.5
[+] New modules: Pidgin, AIM6, AIM Pro, CamFrog
[+] Added support for the latest Mail.Ru Agent versions
[*] Updated Hungarian translation (thx Hevesi Janos)

18-Oct-2007, v1.0.6
[-] Fixed language selection (was broken since v1.0.5)
[-] Improved PocoMail password recovery
[-] Fixed FFFTP password recovery
[-] Fixed Mail.Ru Agent password recovery for passwords longer then 4 chars
[-] Fixed Outlook Express module
[*] Improved Outlook Express identity password recovery
[*] Updated Hungarian translation (thx Hevesi Janos)

27-Oct-2007, v1.0.7
[+] Added "Check for update" feature
[+] Updated interface
[+] Using Thedima protector now for application protection
[+] Added Hungarian installer translations (thx Hevesi Janos)
[+] Added Slovak and Czech installer translations (thx DreamWalker[CLS])
[*] Updated Czech and added Slovak language translation (thx DreamWalker[CLS])
[-] Fixed few minor bugs

12-Jan-2008, v.1.0.8
[+] New modules: CoffeeCup FTP, Core FTP, FTPExplorer, POP Peeper, Frigate3 FTP, Mail Commander, SecureFX, PC Remote Control, UltraFXP, FTPRush
[+] Added Romanian translation (thx Cristian Stefan)
[+] New command line key /extlang - use external language file (ext.lang), can be used to test new translations
[+] QIP passwords can be removed now
[*] Improved Outlook .pst password recovery
[*] Improved FlashFXP password recovery
[*] Updated Czech translation (thx Jaroslav Cizek)
[*] Added support for the latest SmartFTP versions
[*] Improved FTP Commander and FTP Navigator password recovery
[*] Improved CuteFTP password recovery, version 8.1 is supported now
[-] Fixed scrolling text in the "About" dialog

17-Mar-2008, v.1.0.9
[+] New module: MySpaceIM
[+] MPR now asks for confirmation on password deletion
[*] New modules in the password decryption wizard
[-] Quick Connect passwords in CuteFTP 8 were not recovered
[-] Improved password recovery in older CuteFTP versions

13-Oct-2008, v.1.1.0
[+] CuteFTP Lite password decryption
[+] Support for Remote Desktop Connection decryption in SP3
[-] Fixed WS_FTP password decryption
[-] Fixed SecureFX unicode password decryption
[-] Password deletion in Windows Live Messenger and Gmail Notifier wasn't working

03-Jan-2009, v.1.1.1
[!] Portable version of Multi Password Recovery is out now
	Portable software is a class of software that is suitable for use on portable drives
	such as an USB drive. Portable MPR version does not require installation, registration key 
	can be stored in 'key.txt' file, all application settings are also stored in a file.
	This version leaves a near-zero "footprint" on any PC it's run on after being used.
	All temporary files/registry settings are removed once the program has exited.
[+] New modules: Pandion, UPSMon, QIP.Online, JAJC (Just Another Jabber Client),
  Web Site Publisher (c) Brian Cryer, Digsby, Apple Safari, Google Chrome
[+] MPR checks for the update on start every 7 days
[+] Implemented Mozilla Firefox 3 password decryption
[+] FileZilla 3 account processing is now supported
[+] Added Spanish translation (thx Christian Olaechea M.)
[-] Fixed Windows product key retrieval (System Info module)
[-] Removed memory leak in Firefox decryption module

26-Jan-2009, v.1.1.2
[+] New modules: Windows 9x Cached Network passwords, 
  Windows Cached Credentials (.NET Passport, Domain and Network passwords),
  Microsoft Access .mdb password recovery (long passwords are supported),
  Cisco VPN Client
[+] Added detailed help file
[+] MPR under Windows Vista will now require administrator privileges through manifest resource
[+] Added Indonesian translation (thx Ariestya Dibyanugraha)
[*] Updated System Info module
[-] Fixed 'wand.dat' file processing error in Opera module
[-] Fixed missing 'sqlite3.dll' file error (Firefox 3 password recovery module)
[-] Fixed FTP/Basic Auth password recovery in Google Chrome
[-] Fixed Trillian password recovery

06-Feb-2009, v.1.1.3
[+] New module: BitKinex
[+] Implemented Internet Explorer 7 saved forms password decryption
[*] Updated Hungarian translation (thx Hevesi Janos)
[-] Fixed bug in 'Windows Cached Credentials' module
[-] Fixed a few memory leaks

13-Mar-2009, v.1.1.4
[+] Added Polish translation (thx Andrzej Rudnik)
[*] Updated NSIS installer
[-] Windows Cached Credentials password recovery was broken in 1.1.3

17-May-2009, v.1.1.5
[+] New modules: ExpanDrive, Classic FTP, Fling
[+] Added Italian translation (thx Olga Shyshkina)
[+] Improved Internet Explorer 8 password recovery
[+] Opera 10 Preview browser is supported now
[+] WS_FTP 12 Home/Pro is supported now

24-Jun-2009, v.1.1.6
[+] New translations: Turkish (thx M.Bugra AKTAS), Croatian, Serbian (thx dboki89)
[+] New modules: SoftX FTP Client, Directory Opus, FTP Uploader
[+] Improved decryption for latest Mail.ru Agent versions
[+] Implemented Opera 10 Beta password recovery
[+] Improved Outlook 2007 password recovery
[-] Fixed automatic update checker bug after the system regional settings change
[-] Fixed regional characters in following translations: Italian, Romanian

13-Aug-2009, v.1.1.7
[+] New modules: Windows Live Mail, Windows Mail password recovery
[+] Mail Commander was added to advanced decryption wizard
[+] Better autorun detection
[*] Minor GUI updates
[-] Google Chrome browser bugfixes

20-Oct-2009, v.1.1.8
[!] New command line option "/export" (export passwords into an external file) can be used for password backup automation
[+] Implemented .mpf file association
[+] Implemented Firefox 3 SQLite password decryption
[*] Updated help file
[*] Reworked trial mode (all passwords shorter than 3 chars can be viewed for free)
[*] Updated NSIS (win32 installer/uninstaller system)
[-] Minor bug fixes and GUI updates

01-Dec-2009, v.1.1.9
[!] New icon set (thx Serghei Demidiuk)
[+] New modules: Trillian Astra, FreeFTP, DirectFTP, LeapFTP, WinSCP
[+] Improved Windows 7 compatibility
[+] Improved XP/Vista/Win7 64-bit compatibility
[+] Latest TurboFTP versions are supported now, including Unicode .dat files
[*] Improved Miranda IM profile scanner
[*] Improved BulletProof FTP dat file scanner
[*] Application size optimizations
[*] Updated Hungarian translation (thx Hevesi J.)
[*] Updated German translation (thx zeloran)
[-] Fixed Total Commander FTP ini file scanner
[-] Uninstaller did not remove shortcuts under Windows 7 and Vista

08-March-2010, v.1.2.0
[+] New modules: 32bit FTP, WebDrive, FTP Control
[+] Implemented FAR 2 FTP password decryption
[+] Added support for Eudora 8 beta
[+] Added support for Mozilla Thunderbird 3 (Lanikai) 
[*] Improved password scanner in Pidgin/GAIM
[*] Improved autorun detection under 64-bit systems
[*] Fixed incorrect file reading in Miranda-IM, Mail.Ru Agent modules
[-] Fixed Miranda-IM password decryption for latest versions
[-] Fixed Opera E-mail 10.50 password decryption
[-] Fixed rare bug in Google Talk password decryption algorithm

25-May-2010, v.1.2.1
[*] Firefox, Mozilla Thunderbird, Eudora 8 password decryption optimization
[*] Updated Hungarian translation 
[*] Updated Polish translation
[*] Multithreading optimizations
[-] Some registry entries in Windows x64 systems could not be deleted
[-] Minor bug fixes and GUI updates

12-Jul-2010, v.1.2.2
[+] Implemented Microsoft Outlook 2010 password recovery (PST files and servers)
[+] Implemented TurboFTP 6 password recovery
[-] Fixed Windows 7, Windows Vista UAC installer compatibility issues
[-] Fixed BitKinex password decryption

--
ICQ: 74657
E-mail: info@passrecovery.com
Web: http://passrecovery.com
