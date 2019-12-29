# Data 8 Solutions
My repository for Fall 2019 for Data 8, UC Berkeley. 

## Bypassing Google Drive download restrictions 
1. Open the restricted Google Drive PDF file. Click top right three dots and `Open in New Window`
2. Go to **Networks** tab in Google Chrome Dev Tools (cmd + opt + i) and refresh the page.
3. Watch the XHR tab and look for file with 'upload?' in the file name
4. Open the file in a new tab and look for `pdf` key. The value of that key is the unrestricted PDF file. 

![XHR Tab and upload file](https://i.paste.pics/8b2cd9dfbfe6b24b452ef358df0566b9.png)
