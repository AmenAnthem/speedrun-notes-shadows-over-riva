The Steam version has several problems and crashes which may occur.

To fix a lot of these crashes you need to
- go to you Shadows over Riva directory (For Windows: C:\Program Files (x86)\Steam\steamapps\common\Realms of Arkania 3 SoR Classic)
- copy the JEMMEX.EXE from the DSA3 directory to the parent directory
- change the values of the properties xms, ems and umb to false in your dosboxrealms3.conf
- add the following line in your dosboxrealms3.conf above RIVA which is towards the end of the file:
jemmex load noems

This also removes the loading screens, which is helpful for the speedrun.