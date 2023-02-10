# End of Life

The Flash Player **End of Life**, or **EoL** refers to the discontinuation of Flash Player. On the 31st December 2020, Adobe officially ended support for Flash Player, ceasing all updates. On the 12th January 2021, Flash content was blocked from running in the plugin, making it unusable.

## Background

### Security

Flash has suffered [numerous security vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-53/product_id-6761/Adobe-Flash-Player.html) throughout its lifetime, enabling attackers to perform a range of malicious (often devious or mischievous) acts, such as executing code remotely, allowing installation and execution of malware by loading flash content on an infected website. These vulnerabilities proved to be a liability for end users, and were consistently outpacing Adobe's attempts to patch them. This is the primary reason that Flash content is actively blocked, rather than simply no longer supported, thus protecting unsuspecting users from attacks.

### Obsolescence

Compared to modern technologies such as [HTML5](https://wikipedia.org/wiki/HTML5) and [WebAssembly](https://wikipedia.org/wiki/WebAssembly), Flash runs very slowly. Loading times are long, processing is inefficient, and rendering is laggy. Anything achievable with Flash can be achieved more efficiently with other standards. This makes it obsolete, and as such it is unprofitable for Adobe to continue supporting it with [Adobe Animate](https://wikipedia.org/wiki/Adobe_Animate).

## Killswitch

Version 32.0.0.387, the most recent version of the Flash plugin contains a mechanism referred to as the "killswitch" or "time bomb" that disables the functionality of the plugin if the system time is detected to be after 00:00 on the 12th January 2021. Notably, this is timezone-dependent, resulting in a phenomenon recorded on the EoL date wherein different countries experienced the effects of the killswitch at different times, corresponding to their local 00:00.

## Workarounds

### Official projector

The [official projector](../players/projector.md) can be used to play Flash content on a desktop without the need for a browser or a working Flash plugin. Although their availability is limited, they are generally not affected by the [killswitch](#killswitch).

### Emulators

See [Ruffle](../players/ruffle.md) and [Waflash](../players/waflash.md) for more information.

### Old browsers and plugins

Older versions of browsers still support Flash content. This kind of material can be hard to find, however, because browsers rarely provide downloads for older versions, and Adobe no longer provides downloads to the plugin.

An option for this method is to use [Chromium 87](https://commondatastorage.googleapis.com/chromium-browser-snapshots/index.html?prefix=Win_x64/812845/), the last version available before Flash support was removed. You can [download version 32.0.0.371 of the Flash plugin](https://archive.org/details/flashplayer_old) on the Internet Archive.

!!! danger
    Old browsers, particularly with Flash installed, are extremely prone to malware attacks and security vulnerabilities. Your computer may be permanently damaged. Proceed at your own risk, and take appropriate precautions.

## Links

- [Official Adobe info page](https://adobe.com/uk/products/flashplayer/end-of-life.html)

## Further reading

- [Section on Wikipedia](https://wikipedia.org/wiki/Adobe_Flash_Player#End_of_life)