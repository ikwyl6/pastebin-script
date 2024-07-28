# pastebin-script
linux command line script that uploads text to numerous pastebin-type sites. These sites include:

* pastebin.com: http://pastebin.com
~~* sprunge.us: http://sprunge.us~~
~~* pastebin.ca: http://pastebin.ca~~
* pasteie.org: http://pasteie.org
* paste2.org: http://paste2.org
* paste.rs
* dpaste.com
~~* privatepaste.com: http://privatepaste.com~~
~~* tny.cz: http://tny.cz~~
~~* clitxt.com: http://clitxt.com~~
~~* cxg.de: http://cxg.de~~
* paste-bin.xyz
* 0paste.com/paste.myconan.net
* nopaste.ml
* vpaste.net
* Want more sites? Submit an issue/PR with the website and I will see if I can add it.

## How to get it, how to use it
Download the script from this repository, made it executable (chmod x+r pastebin) and run:
`pastebin -h` for usage

A config file 'pastebin.conf' is used for some variables. These are mostly for pastebin.com but any variables can be added that you want to use. The script looks for this file in $HOME/.pastebin.conf:

* `name`: username used for some websites that will post the user of the pastebin
* `ca_api_key`: Used for pastebin.ca if you want to use your own api key
* `api_key`: Used for pastebin.com if you want to use your own api key
* `api_user_key`: Used for pastebin.com if you want to use your own user key
* -xclip : location and options for xclip to auto copy your link using xclip
