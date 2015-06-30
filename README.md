# pastebin-script
linux command line script that uploads text to numerous pastebin-type sites. These sites include:

* pastebin.com: http://pastebin.com
* sprunge.us: http://sprunge.us
* pastebin.ca: http://pastebin.ca
* pasteie.org: http://pasteie.org
* paste2.org: http://paste2.org
* privatepaste.com: http://privatepaste.com
* tny.cz: http://tny.cz
* clitxt.com: http://clitxt.com
* cxg.de: http://cxg.de
*  
* Want more sites? Submit an issue with the website and I will see if I can add it.

## How to get it, how to use it
Download the script from this repository, made it executable (chmod x+r pastebin) and run:
`pastebin -h` for usage

Within the file/script there are parameters that can be stored within the file that will make it more customizable to the user:

* `name`: username used for some websites that will post the user of the pastebin
* `ca_api_key`: Used for pastebin.ca if you want to use your own api key
* `api_key`: Used for pastebin.com if you want to use your own api key
* `user_key`: Used for pastebin.com if you want to use your own user key




