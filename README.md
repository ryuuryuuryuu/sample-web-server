# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
Last login: Thu Jun 13 18:15:21 on ttys001
-bash: /Users/hiraikeryuta/.bash_profile: line 10: syntax error: unexpected end of file
heichiryuudainoMacBook-Pro:~ hiraikeryuta$ cd ~
heichiryuudainoMacBook-Pro:~ hiraikeryuta$ ls
AT.postflight.12191	IoT			fujiwara
Amazon Drive		Library			kid
Applications		Movies			program
Creative Cloud Files	Music			ryuuryuu
Desktop			Pictures		souko
Documents		Public			ssh
Downloads		VirtualBox		移送予定
Google ドライブ		VirtualBox VMs		趣味やん
heichiryuudainoMacBook-Pro:~ hiraikeryuta$ cd ~/fujiwara
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ ls
hello-git		learning-http-message	simple-web-site
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ git clone git@github.com:ryuuryuuryuu/sample-web-server.git
Cloning into 'sample-web-server'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
Receiving objects: 100% (7/7), done.
Resolving deltas: 100% (1/1), done.
remote: Total 7 (delta 1), reused 5 (delta 1), pack-reused 0
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ ls
hello-git		sample-web-server
learning-http-message	simple-web-site
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ cd s
sample-web-server/ simple-web-site/   
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ cd sample-web-server/
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ code .
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[{"weight":{"imperial":"7 - 14","metric":"3 - 6"},"id":"esho","name":"Exotic Shorthair","cfa_url":"http://cfa.org/Breeds/BreedsCJ/Exotic.aspx","vetstreet_url":"http://www.vetstreet.com/cats/exotic-shorthair","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/exotic-shorthair","temperament":"Affectionate, Sweet, Loyal, Quiet, Peaceful","origin":"United States","country_codes":"US","country_code":"US","description":"The Exotic Shorthair is a gentle friendly cat that has the same personality as the Persian. They love having fun, don’t mind the company of other cats and dogs, also love to curl up for a sleep in a safe place. Exotics love their own people, but around strangers they are cautious at first. Given time, they usually warm up to visitors.","life_span":"12 - 15","indoor":0,"lap":1,"alt_names":"Exotic","adaptability":5,"affection_level":5,"child_friendly":3,"dog_friendly":3,"energy_level":3,"grooming":2,"health_issues":3,"intelligence":3,"shedding_level":2,"social_needs":4,"stranger_friendly":2,"vocalisation":1,"experimental":0,"hairless":0,"natural":0,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Exotic_Shorthair","hypoallergenic":0}],"id":"dVujvBqnu","url":"https://cdn2.thecatapi.com/images/dVujvBqnu.jpg","width":1024,"height":999}]heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ ls
README.md
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ cd ..
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ ls
hello-git		learning-http-message	sample-web-server	simple-web-site
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ cd sample-web-server/
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ ls
README.md
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"anf","url":"https://cdn2.thecatapi.com/images/anf.jpg","width":640,"height":511},{"breeds":[],"id":"ar2","url":"https://cdn2.thecatapi.com/images/ar2.jpg","width":2592,"height":1944},{"breeds":[],"id":"MTU4MDQxMQ","url":"https://cdn2.thecatapi.com/images/MTU4MDQxMQ.jpg","width":1280,"height":1280}]heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ ls
README.md
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ brew install jq
Updating Homebrew...
==> Auto-updated Homebrew!
Updated 3 taps (homebrew/core, homebrew/cask and caskroom/cask).
==> New Formulae
swig@3
==> Updated Formulae
aws-sdk-cpp         folly               joplin              procs               terraform
braid               gibo                knot                pulumi              topgrade
calicoctl           glib                libev               pybind11            vultr
certbot             glooctl             lmod                pyenv               webpack
chakra              gmic                mighttpd2           rbspy               whois
circleci            graph-tool          minio               scalariform         wildfly-as
envconsul           gst-plugins-good    minio-mc            scons               wtf
exiftool            hlint               nomad               scrcpy              yelp-tools
firebase-cli        imagemagick         opa                 ship
flow                jdupes              paket               sops
fluxctl             jfrog-cli-go        phpunit             telegraf
==> Deleted Formulae
swig@3.04

==> Installing dependencies for jq: oniguruma
==> Installing jq dependency: oniguruma
==> Downloading https://homebrew.bintray.com/bottles/oniguruma-6.9.2.mojave.bottle.tar.gz
==> Downloading from https://akamai.bintray.com/c6/c613befafe81da48913ebd1a7eb036a7d8a147516fae32e2fb
######################################################################## 100.0%
==> Pouring oniguruma-6.9.2.mojave.bottle.tar.gz
🍺  /usr/local/Cellar/oniguruma/6.9.2: 17 files, 1.3MB
==> Installing jq
==> Downloading https://homebrew.bintray.com/bottles/jq-1.6.mojave.bottle.1.tar.gz
==> Downloading from https://akamai.bintray.com/71/71f0e76c5b22e5088426c971d5e795fe67abee7af6c2c4ae0c
######################################################################## 100.0%
==> Pouring jq-1.6.mojave.bottle.1.tar.gz
🍺  /usr/local/Cellar/jq/1.6: 18 files, 1MB
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ ls
README.md
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
[
  {
    "breeds": [],
    "id": "2oo",
    "url": "https://cdn2.thecatapi.com/images/2oo.gif",
    "width": 330,
    "height": 186
  },
  {
    "breeds": [],
    "categories": [
      {
        "id": 15,
        "name": "clothes"
      }
    ],
    "id": "8vh",
    "url": "https://cdn2.thecatapi.com/images/8vh.jpg",
    "width": 570,
    "height": 575
  },
  {
    "breeds": [],
    "id": "b5h",
    "url": "https://cdn2.thecatapi.com/images/b5h.jpg",
    "width": 645,
    "height": 900
  }
]
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ ls
README.md	thecat.json
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ cat ~/.bash_profile

# Setting PATH for Python 3.7
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.7/bin:${PATH}"
export PATH
if [ -f ~/.bashrc ]; then
if [ -f ~/.bashrc ]; then
  . ~/.bashrc
fi
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ nodebrew install-binary latest
-bash: nodebrew: command not found
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ curl -L git.io/nodebrew | perl - setup
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:03 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:03 --:--:--     0
100 24634  100 24634    0     0   5377      0  0:00:04  0:00:04 --:--:--  5377
Fetching nodebrew...
Installed nodebrew in $HOME/.nodebrew

========================================
Export a path to nodebrew:

export PATH=$HOME/.nodebrew/current/bin:$PATH
========================================
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ export PATH=$HOME/.nodebrew/current/bin:$PATH >> ~/.bashrc
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ source ~/.bashrc
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ nodebrew
nodebrew 1.0.1

Usage:
    nodebrew help                         Show this message
    nodebrew install <version>            Download and install <version> (from binary)
    nodebrew compile <version>            Download and install <version> (from source)
    nodebrew install-binary <version>     Alias of `install` (For backward compatibility)
    nodebrew uninstall <version>          Uninstall <version>
    nodebrew use <version>                Use <version>
    nodebrew list                         List installed versions
    nodebrew ls                           Alias for `list`
    nodebrew ls-remote                    List remote versions
    nodebrew ls-all                       List remote and installed versions
    nodebrew alias <key> <value>          Set alias
    nodebrew unalias <key>                Remove alias
    nodebrew clean <version> | all        Remove source file
    nodebrew selfupdate                   Update nodebrew
    nodebrew migrate-package <version>    Install global NPM packages contained in <version> to current version
    nodebrew exec <version> -- <command>  Execute <command> using specified <version>

Example:
    # install
    nodebrew install v8.9.4

    # use a specific version number
    nodebrew use v8.9.4
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ nodebrew install-binary latest
v12.4.0 is already installed
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ nodebrew ls
v12.4.0

current: v12.4.0
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ pwd
/Users/hiraikeryuta/fujiwara/sample-web-server
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ cd ~/fujiwara
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ ls
hello-git		learning-http-message	sample-web-server	simple-web-site
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ mkdir mywebapi
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ cd mywebapi/
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/hiraikeryuta/Documents/fujiwara/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes) 
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ 
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ npm install --save expless
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ expless@0.1.91
added 68 packages from 129 contributors and audited 83 packages in 7.354s
found 0 vulnerabilities

heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:7
app get ('/', (req, res) => res.send(''Hello));
    ^^^

SyntaxError: Unexpected token get
    at Module._compile (internal/modules/cjs/loader.js:718:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:8
app get ('/', (req, res) => res.send(''Hello));
    ^^^

SyntaxError: Unexpected token get
    at Module._compile (internal/modules/cjs/loader.js:718:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:8
app get ('/', (req, res) => res.send(''Hello));
    ^^^

SyntaxError: Unexpected token get
    at Module._compile (internal/modules/cjs/loader.js:718:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module 'express'
Require stack:
- /Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Module.require (internal/modules/cjs/loader.js:681:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at Object.<anonymous> (/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:2:17)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js' ]
}
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module 'express'
Require stack:
- /Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Module.require (internal/modules/cjs/loader.js:681:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at Object.<anonymous> (/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:3:17)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js' ]
}
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module 'express'
Require stack:
- /Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Module.require (internal/modules/cjs/loader.js:681:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at Object.<anonymous> (/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:2:17)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js' ]
}
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module 'express'
Require stack:
- /Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Module.require (internal/modules/cjs/loader.js:681:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at Object.<anonymous> (/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js:2:17)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/Users/hiraikeryuta/Documents/fujiwara/mywebapi/index.js' ]
}
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ pwd
/Users/hiraikeryuta/fujiwara/mywebapi
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ cd ..
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ ls
hello-git		mywebapi		simple-web-site
learning-http-message	sample-web-server
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ mv mywebapi/ sample-web-server/
heichiryuudainoMacBook-Pro:fujiwara hiraikeryuta$ cd sample-web-server/
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ pwd
/Users/hiraikeryuta/fujiwara/sample-web-server
heichiryuudainoMacBook-Pro:sample-web-server hiraikeryuta$ cd mywebapi/
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ npm install --save express
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
added 46 packages from 32 contributors and audited 209 packages in 5.011s
found 0 vulnerabilities

heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
Listening on port 3000
^C
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
Listening on port 3000
^C
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
Listening on port 3000
^C
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
Listening on port 3000
^C
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ vi index.js
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ped
-bash: ped: command not found
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ pwd
/Users/hiraikeryuta/fujiwara/sample-web-server/mywebapi
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		node_modules		package-lock.json	package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ mkdir web
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ cd web/
heichiryuudainoMacBook-Pro:web hiraikeryuta$ vi index.html
heichiryuudainoMacBook-Pro:web hiraikeryuta$ cd ..
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ ls
index.js		package-lock.json	web
node_modules		package.json
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ node index.js
Listening on port 3000
^C
heichiryuudainoMacBook-Pro:mywebapi hiraikeryuta$ 

```
