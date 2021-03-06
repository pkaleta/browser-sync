# BrowserSync [![Build Status](https://travis-ci.org/shakyShane/browser-sync.svg?branch=master)] (https://travis-ci.org/shakyShane/browser-sync) [![Build status] (https://ci.appveyor.com/api/projects/status/r5vung2ipn9uj4sy)](https://ci.appveyor.com/project/shakyShane/browser-sync) [![Coverage Status](https://img.shields.io/coveralls/shakyShane/browser-sync.svg)](https://coveralls.io/r/shakyShane/browser-sync?branch=master) [![NPM version](https://badge.fury.io/js/browser-sync.svg)](http://badge.fury.io/js/browser-sync)

> Keep multiple browsers & devices in sync when building websites.

<a href="http://www.wearejh.com"><img src="http://cl.ly/image/3Y3O0M2z310j/jh-100-red.png" /></a>

BrowserSync is developed and maintained internally at <a href="http://www.wearejh.com">JH</a>, follow <a href="http://www.twitter.com/browsersync">@BrowserSync</a> on twitter for news & updates.

##Features
1. **Scroll** - I can keep your pages in sync when scrolling.
2. **Forms** - You fill out a form in one browser, I'll copy the data to all the others.
3. **Links** - I'll watch your clicks and make all the other browsers follow you.
4. **CSS injecting** - I can even watch your CSS files & inject them when they change.
5. **Live Reload** - I can also watch files like HTML and PHP & when they change I can reload all browsers for you.
6. **Built-in Server** - Yep, I can serve static files too if you need me to (uses Connect).
7. **Use with any back-end setup** - I even have a proxy option so that I can be used with existing PHP, Rails, Python, Node or ASP.net setup.
8. **Public URL** - View your website via a URL that any internet connected device can access & maintain all BrowserSync features.
9. **Browser Stack support** - Use the all of my features when viewing your site through Browser Stack.


##When is it useful?
It's pretty useful when used with a single browser, watching a CSS file for changes & injecting it. But the real power comes when you're building responsive sites and using multiple devices/monitors because it can keep all browsers in sync & make your workflow much faster.

##Install
```
npm install -g browser-sync
```
##How to use it

1. [Command line](http://www.browsersync.io/docs/command-line/)
2. [API](http://www.browsersync.io/docs/api/)

## Using Grunt?
There's a [separate plugin](https://github.com/shakyShane/grunt-browser-sync) for that

## Using Gulp?
No problem, here's a [setup guide](http://www.browsersync.io/docs/gulp)

## Using Brunch?
Enjoy the [browser-sync-brunch plugin](https://github.com/ocombe/browser-sync-brunch)

## Screencasts
[Some listed here](https://github.com/shakyShane/browser-sync/wiki/Screencasts)
Want any more? Something specific? ask me nicely [@shaneOsbourne](http://www.twitter.com/shaneOsbourne)

##Support
If you've found Browser-sync useful and would like to contribute to its continued development & support, please feel free to send a donation of any size - it would be greatly appreciated!

[![Support via Gittip](https://rawgithub.com/chris---/Donation-Badges/master/gittip.jpeg)](https://www.gittip.com/shakyshane)
[![Support via PayPal](https://rawgithub.com/chris---/Donation-Badges/master/paypal.jpeg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=shakyshane%40gmail%2ecom&lc=US&item_name=browser%2dsync)

## Contributors

```
   703	Shane Osbourne
    16	Shinnosuke Watanabe
    13	Hugo Bessa
    11	Paul Kinlan
    10	Shane Daniel
     5	shinnn
     3	Marek 'saji' Augustynowicz
     3	Werner van Deventer
     2	chase_chou
     2	Michael Branch
     2	brutaldev
     2	Hugo Dias
     2	Olivier Combe
     2	Dan Tello
     2	Paul Robertson
     1	viktor hesselbom
     1	Cameron Spear
     1	Carl Henderson
     1	Cedric Kastner
     1	Craig Morris
     1	Dave Hall
     1	Guillaume Lambert
     1	Jory Graham
     1	Robert Vock
     1	Sylvain Emery
     1	Tony Holdstock-Brown
     1	Victor Fernandez de Alba
     1	Yazhong Liu
     1	mericson
     1	Benjamín Eidelman
```

## Troubleshooting

The way BrowserSync works is by injecting an asynchronous script tag (`<script async>...</script>`) right after the `<body>` tag during initial request. The role of this tag is to request a BrowserSync's JS file when loading the page. In order for this to work properly the `<body>` tag must be present.

## License
Copyright (c) 2014 Shane Osbourne
Licensed under the GPL license.
