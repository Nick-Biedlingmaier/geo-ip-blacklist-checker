# Geo-IP-Blacklist-Checker for Powershell and Bash #

#### *Update* :

23 Oct 2025 - Added geoip.sh Bash script to perform the same funtion on Linux. More details below the gif.

This is a simple Powershell (or Bash!) script that queries various dbs and API endpoints and prints your IPv4 and IPv6 public IPs as well as checks them against a handful of known blacklist databases.

## To use:

Open PS as admin within the same directory as the script by right-clicking and then holding Shift+Ctrl and clicking "Open in Terminal." Run this command first to make sure you can always run scripts without issue. This only applies to your own account, not all system accounts.

*Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted*

### WARNING: This will let you run ANY Powershell script. Know what you're running, otherwise use *Bypass* for the current script you're trying to run before you run it each time.

*Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass*

Then run the script afterwards. Execute any script by using the command with .\ before it. (Ex: .\examplescript.ps1)

![](/Animation.gif)

# Running on Linux distros #

1. Download ##geoip.sh## from Releases.
2. Open Terminal
3. Navigate to the file dirextory
4. Run: sudo *chmod +x geoip.sh* to make the script execuatable.
5. Run: *sudo bash geoip.sh*
