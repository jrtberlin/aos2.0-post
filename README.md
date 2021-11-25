
# AsteroidOS 2.0

There is no denying that it has been a while since our last release, but it's finally here!

AsteroidOS 2.0 has arrived, with major features like Always-on-Display, more supported watches, new launcher styles and improvements to our clients.

   * [Always-on Display](https://github.com/AsteroidOS/asteroid/issues/58)
   * [Tilt-to-wake](https://github.com/AsteroidOS/mce/pull/6)
   * [App Launcher Styles](https://github.com/AsteroidOS/asteroid-settings/pull/35)
   * [palm-to-sleep](https://github.com/AsteroidOS/mce/pull/11)
   * [Color Emoji](https://github.com/AsteroidOS/meta-asteroid/pull/56)
   * [music control](https://github.com/AsteroidOS/AsteroidOSSync/pull/117)
   * [Lag fix when more notifications appear](https://github.com/AsteroidOS/asteroid-launcher/pull/58)
   * base upgraded to Honister
   * [new wallpapers](https://github.com/AsteroidOS/asteroid-wallpapers/pull/4)
   * new UI elements (improved toggles, progress bars,...)
   * [initial step counting support](https://github.com/AsteroidOS/qtsensors/pull/1)
   * [compass support](https://github.com/AsteroidOS/asteroid-compass)
   * [flashlight app](https://github.com/AsteroidOS/asteroid-flashlight)
   * [HRM app](https://github.com/AsteroidOS/asteroid-hrm)
   * Qt 5.15 upgrade
   * the timer app works in the background
   * [more translations (56 languages)](https://hosted.weblate.org/projects/asteroidos/)
   * [support for Bluetooth HID and Audio](https://github.com/AsteroidOS/meta-asteroid/pull/27)
   * [ringtone vibration pattern](https://github.com/AsteroidOS/asteroid/issues/99)


## Supported Hardware

Since 1.0 we added the following watches:

   * Huawei Watch
   * Huawei Watch 2
   * Moto 360 2015
   * MTK6580 (Harmony/Inharmony)
   * Ticwatch E \& S
   * Skagen Falster 2 (ray)
   * Fossil Gen 4 Watches (firefish)
   * Ticwatch C2+ (skipjack)


In addition to new watches, we've also been busy improving the support for our already supported watches:

   * Asus Zenwatch: The long standing issue of the touch screen issue has been solved.
   * Asus Zenwatch 2: Sensors have been fixed. Bluetooth problems fixed
   * Asus Zenwatch 3: Sensors have been fixed.
   * Sony Smartwatch 3: Sensors have been fixed.


## Clients

### Android

   * [Call detection and display](https://github.com/AsteroidOS/AsteroidOSSync/pull/110)
   * [new Bluetooth lib](https://github.com/AsteroidOS/AsteroidOSSync/pull/127) should improve stability and simplify the paring process
   * a more modular architecture, allowing for easier extending and maintainability of the app.
   * [custom OWM API key support](https://github.com/AsteroidOS/AsteroidOSSync/pull/142)


### UBports

After our initial release [StefWe](https://github.com/StefWe) created [Telescope](https://github.com/AsteroidOS/telescope) a sync client for UBports.


### SailfishOS

With recent improvements in the SailfishOS BLE stack, our community member [GeoffTearle](https://github.com/GeoffTearle) got our [client for SailfishOS](https://github.com/AsteroidOS/starfish) into a working state. {An early version is already available to download here.}



## Infrastructure

Alongside 2.0 we introduce a community repository, to improve discoverability and simplify the installation of precompiled packages, while building the foundation for a possible graphical software center in the future. Currently, the repository consists of a few debugging tools, {community watchfaces}, games and emulators. Developers are welcome to create pull requests on the [meta-community](https://github.com/AsteroidOS/meta-asteroid-community) repo for packaging.

The second and smaller change is the switch to Markdown as our primary markup language for documentation. This enables users without deeper knowledge to contribute to the documentation via GitHub's integrated editor and us to switch the static site generator in the future.

In late March, we moved our infrastructure to a larger server at Hetzner. While this increased the costs, it already resulted in more frequent nightly releases.

On the repository of AsteroidOS Sync, our Android app, we enabled automatic builds on pull requests to catch issues with future changes early.

## Minor Changes

AsteroidOS has now support for [round screens with a cut-off](https://github.com/AsteroidOS/meta-asteroid/pull/41) and 

PostmarketOS now offers our launcher and core apps, thanks to [PureTryOut](todo), who moved our buildsystem from qmake to cmake along the way.

MagneFire and JRT joined the AsteroidOS team.

## Community

Our community sometimes comes up with funny or beautiful new watchfaces. Here are some examples of the recent highlights:

eLtMosen has created new watchfaces like the minimalistic [pulsedot watchface](https://www.youtube.com/watch?v=UETFXGV2dgU) and the Monty Python [silly walks watchface](https://twitter.com/eLtMosen/status/1403642123338014722). Most of his creations are available in the [unofficial-watchface repository](https://github.com/AsteroidOS/unofficial-watchfaces).

MagneFire did show-off a few emulators, Doom, [Super Tux Kart](https://fosstodon.org/@MagneFire/107105850296484856) and a 2048 port on his watch.

The creator of the unofficial [Subreddit](https://www.reddit.com/r/AsteroidOS/) gave us full access, making it an official channel alongside the [new Mastodon account](https://fosstodon.org/@AsteroidOS).
As we already mentioned in a [previous blog post](https://asteroidos.org/news/farewell-freenode), we moved all our communication from freenode to Matrix and Libera.chat.

## The Future

As you might have noticed, the current releases on the installation page already seem to have a feature parity with the 2.0 release. The reason behind this is that at some point we decided to switch from our stable 1.0 release to the 1.1 nightly release as the 1.0 release became too old. In the future we would like to change our release cycle to release more often. So that a stable release will always be stable but not too old where it is no longer maintainable.


For the future we also would like to setup a roadmap to what we would like to see in an eventual next release:

   * A fitness app (Heart rate monitoring and step counter tracking)
   * A proper WiFi setup via the settings app




===================================================================================================
   * Show pictures for some relevant things
       * Tilt-to-wake
       * palm-to-sleep
       * color emoji
       * New wallpapers
       * new watchfaces
       * Telescope
