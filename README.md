<table align="center"><tr><td align="center" width="9999">

# MisModPublisher 

​An Alternative Tool To Upload Your Miscreated Mods On Steam
</td></tr></table>



MisModPublisher is a tool designed to simplify the process of uploading and updating your mods on Steam.
Easier and more convenient to use than the regular SteamCMD, this application lets you :

- Create a reference file (vdf) for your mod, including : Title, Description, Changenotes, Steam Tags ...
- Upload/update your mod on Steam without disconnecting your Steam account.
- Automatically open your mod page at the end of the upload to let you personnalize it.

We are going to detail the process of each steps in the subsections below.


<div align="center">
INSTALLATION

**************************************************************************************************************************************************************************
</div>

 - Grab The QuickStart.Zip from here: [Latest Release](https://github.com/MisModding/MisModPublisher/releases/latest)
 - Extract the content of the zip file.
 > You Can Extract the Package Anywhere you Like though the Information Below Presumes Your Current Users Desktop
 > run the included Update.exe to validate you have the lastest version


<div align="center">
HOW TO USE

**************************************************************************************************************************************************************************
</div>

1. Copy your Mod freshly created into the MiscreatedMods/Mods folder.

2. Open your mod.vdf file

>If you don't have any reference file (.vdf) you can simply create one using tools/createVDF.bat (instructions below) and jump to #6.

3. Edit the paths of "contentfolder" and "previewfile" to match the new locations. 

> For example, if you have extracted misModPublisher in your desktop, that would be:
>`C:\\Users\\[YOURNAME]\\Desktop\\MiscreatedMods\\Mods\\[YOURMOD]\\Paks` 
>
>and
>
> `C:\\Users\\[YOURNAME]\\Desktop\\MiscreatedMods\\Mods\\[YOURMOD]\\Images\\[YOURIMAGE]`

4. Be sure to fill every following queries : Title / Description / Changenote

5. You can also add Steam Tags to better detail your mod. For example : 

> `"tags"   "admin,item,weapons"`
>
> Only use lowercase characters when setting your tags. THIS IS IMPORTANT.

6. Go back to misModPublisher main folder and copy/past the UploadToWorkshop.bat file into your Mod folder >> where your mod.vdf is.

7. Double click on your UploadToWorkshop.bat to start the upload. misModPublisher will automatically open your brand new mod page.

>IMPORTANT : a new txt file has been created into your mod folder, containing your mod ID. 
>Copy that ID into your vdf file, in the "publishedfileid" query.



<div align="center">
ADDITIONAL TOOLS

**************************************************************************************************************************************************************************
</div>

- Updater

 from time to time we may release various improvements or bugfixes for mismodpublisher
 to ensure you have the latest version remember to run Updater.exe found in the same folder as you extracted mismodpublisher
 (the mismodpublisher folder in the uickstart) when i finaly get round to working on the intended UI for this tool this will be done automaticaly. bu for now it needs to be done manualy

- createVDF


Found in: MiscreatedMods/Tools

If you want to be guided during the creation of your vdf, you can use that very convenient tool. 
Place it in your mod folder, launch it and let it guide you. It will create a new vdf file ready to use.


<div align="center">
CREDITS

**************************************************************************************************************************************************************************
</div>


> PitiViers, for Writing the ReadMe and for their Help With Testing & Debugging.


<div align="center">
USEFUL LINKS

**************************************************************************************************************************************************************************
</div>

Projects By Svaltek : http://svaltek.xyz/projects/

Miscreated Official Discord : https://discord.gg/X8HJM6S

Miscreated Modding Discord (Unofficial) : https://discord.gg/BbEhbTA

Miscreated Workshop : https://steamcommunity.com/app/299740/workshop/

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
That's all folks ! :)

