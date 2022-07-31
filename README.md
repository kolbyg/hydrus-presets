# Hydrus Presets
These downloaders expect that you have a basic knowledge of the Hydrus Downloader system. More info can be found here: https://hydrusnetwork.github.io/hydrus/getting_started_downloading.html

Import these by going to network > downloaders > import downloaders, then either dragging the png onto the screen or clicking to open a file browser.

Downloaders I will likely make in the near-ish future:
- AO3 - Partially working, Hydrus does not recommend/support downloading in-progress works, which presents a problem
- IMDb - Done, need to test and then upload.


Completed Downloaders:


Tiktok - You must go to tiktok.com in your browser, then export the cookies and import them into Hydrus. You do not need to login, this is only to skip past the browser verification. This extension can make the process easy: https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid

Instagram - Login required, sign in to Instagram.com and use this extension to export cookies: https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid
NOTE: Due to recent changes in the Instagram API, and the lack of support for B64 decode in Hydrus, a local webserver is currently required to translate some URLs.
This works fine and doesnt affect the scraping at all, but you need the local infrastrucutre to run a python script that will translate the URLs for you.
I may eventually put this up publicly, as it's a fairly simple script, but for now you're on your own.
You'll need to modify the relevant URL classes and parsers with your local server's DNS name. The python script is here:
https://github.com/kolbyg/Script-Repository/blob/main/Social%20Media%20Scraping/Hydrus%20Custom%20Endpoints/ig-b64convert.py
