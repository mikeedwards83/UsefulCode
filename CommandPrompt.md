# Command Prompt

## Clean up files over 7 days old:

     forfiles -p "D:\Apps\int\sitecore\CM\Data\logs" -s -m *.* /D -7 /C "cmd /c del @path"