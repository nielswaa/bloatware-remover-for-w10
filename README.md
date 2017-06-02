# bloatware-remover-for-w10
Removes pre-installed Microsoft bloatware like:
- the `Skype App`
- `Zune Music` & `Zune Video`
- `Bing News`, `Bing Weather`, `Bing Sports`
And many, many more!

# Usage
1. Open the script in a text editor or IDE
2. place a hashtag (`#`) in front of all the items you want to keep
   - so for example: replace `"Microsoft.SkypeApp"` with `#"Microsoft.SkypeApp"` to keep it
3. Open PowerShell by right clicking it and running it as administrator, 
4. Once the PowerShell instance is opened, type: `set-executionpolicy unrestricted` (this will allow the powershell script to be ran)
5. Press enter and then hit A (or click on yes to all)
6. Run the script, let it do its thing
7. when finished type in: `Set-executionpolicy restricted` (this will put the PowerShell restrictions back for security reasons)
8. Look at all that bloatware you don't have <3


Mind you, after an update Microsoft might force the programs back onto your machine, re-run the script if the apps are present again!