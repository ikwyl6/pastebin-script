# pastebin-script
linux command line script that uploads text to numerous pastebin-type sites. These sites include:

* pastebin.com: http://pastebin.com
* ~~sprunge.us: http://sprunge.us~~ Page not found
* ~~pastebin.ca: http://pastebin.ca~~ Website not up or 'Bad Gateway'
* ~~pasteie.org: http://pasteie.org~~ No dns record
* paste2.org: http://paste2.org
* paste.rs
* dpaste.com
* ~~privatepaste.com: http://privatepaste.com~~ No dns record
* ~~tny.cz: http://tny.cz~~ Website has captcha
* ~~clitxt.com: http://clitxt.com~~ Website times out
* ~~cxg.de: http://cxg.de~~ Domain up for sale
* ~~paste.ee~~ No dns record found
* ~~ghostbin.com~~ has captcha so will not work
* ~~hastebin.com~~ Forwards to another site
* paste-bin.xyz
* 0paste.com/paste.myconan.net
* nopaste.ml
* vpaste.net
* 0x0.st
* textbin.net - To be added
* txtbin.net - To be added
* Want more sites? Submit an issue/PR with the website and I will see if I can add it.

## How to get it, how to use it
Download the script from this repository, made it executable (`chmod x+r pastebin`) and run:
`pastebin -h` for usage

A config file `pastebin.conf` is used for some variables. These are mostly for pastebin.com but any variables can be added that you want to use. The script looks for this file in `$HOME/.pastebin.conf`:

* `name`: username used for some websites that will post the user of the pastebin
* `ca_api_key`: Used for pastebin.ca if you want to use your own api key
* `api_key`: Used for pastebin.com if you want to use your own api key
* `api_user_key`: Used for pastebin.com if you want to use your own user key
* `xclip` : location and options for xclip to auto copy your link using xclip
