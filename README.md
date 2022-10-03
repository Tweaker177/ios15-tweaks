# iOS 15 Tweaks

There are multiple methods to getting tweak injection working on iOS 15. Most notably, with a tethered jailbreak. Since we don't have a proper rootless tweak injector yet, we cannot use a semi-tethered or semi-untethered jailbreaks as of now.

What we can do is tether a device by using a dev kernel, bootstrapping with odysseyra1n, installing Subsitute 2.2.3, then renaming the snapshot so it won't revert on reboot. With iOS 15, and forced sealing, this will technically brick the device. But, on checkm8 devices, we can still boot it tethered (and rename the snapshot back if we ever wanted to revert and untether).

Tweaks that inject into apps will only work if: the sandbox is destroyed, or the app has the no-sandbox entitlement.

| Name                      | Compatible | Issue                                               | Description                                                                                                            | Repo                                                                                                          |
| ------------------------- | ---------- | --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Accent                    | ✔️         | -                                                   | iOS accent colors in macOS style                                                                                       | [BigBoss](http://apt.thebigboss.org/repofiles/cydia)                                                          |
| Amber                     | ⭕          | Changing flashlight color doesn't work when enabled | Amber-ify your LED torch                                                                                               | [PoomSmart](https://poomsmart.github.io/repo)                                                                 |
| Amelija                   | ✔️         | -                                                   | Take full control of your wallpapers on the fly                                                                        | [Twickd](https://repo.twickd.com/)                                                                            |
| Atria                     | ⭕          | Widgets bug out sometimes                           | A proper homescreen layout editor for iOS 13-15                                                                        | [Chariz](https://repo.chariz.com/)                                                                            |
| BatteryBoobs              | ✔️         | -                                                   | Enable Apple's hidden % in battery                                                                                     | [Download Deb](https://cdn.discordapp.com/attachments/730448303837151233/754524945983209603/BatteryBoobs.deb) |
| CC On & Off               | ✔️         | -                                                   | Toggle Wi-Fi and Bluetooth fully on/off from Control Center                                                            | [PoomSmart](https://poomsmart.github.io/repo)                                                                 |
| CCBalance                 | ✔️         | -                                                   | Change the audio balance from CC                                                                                       | [KingPuffdaddi](https://kingpuffdaddi.github.io/)                                                             |
| CCSupport                 | ✔️         | -                                                   | Support tweak for CC modules                                                                                           | [opa334](https://opa334.github.io/)                                                                           |
| ColorMeNotifs             | ❌          | Crashes to safemode                                 | Bring colors to your notifications                                                                                     | [Packix](https://repo.packix.com/)                                                                            |
| ColorMyBattery            | ✔️         | -                                                   | Battery Color based on the battery percentage                                                                          | [Packix](https://repo.packix.com/)                                                                            |
| Dodo                      | ✔️         | -                                                   | The perfect LS redesign.                                                                                               | [Ginsu Tweaks](https://repo.ginsu.dev/)                                                                       |
| Dress                     | ✔️         | -                                                   | Dress up your lockscreen                                                                                               | [Taurige Github](https://github.com/Traurige/Dress)                                                           |
| DualClock 2               | ⭕          | LS works, status bar doesn't                        | Add 2 time zones to the LS and status bar                                                                              | [Ginsu](https://repo.ginsu.dev/)                                                                              |
| EmojiPort (iOS 12.0-14.8) | ✔️         | Needs control file editing to install               | Latest emojis for iOS 12.0-14.8                                                                                        | [PoomSmart](https://poomsmart.github.io/repo)                                                                 |
| Eneko                     | ✔️         | -                                                   | Set a video as your wallpaper                                                                                          | [Taurige Github](https://github.com/Traurige/Eneko)                                                           |
| Ersatz                    | ✔️         | -                                                   | Replace any text, system-wide                                                                                          | [Skitty](https://skitty.xyz/repo)                                                                             |
| Filza File Manager 64-bit | ⭕          | Pressing on .deb's/binaries crashes the app         | File Manager for iPhone, iPad, iPod Touch                                                                              | [TIGI Software](https://tigisoftware.com/cydia)                                                               |
| HideSerialNumber          | ✔️         | -                                                   | Hide Serial Number in Settings About page                                                                              | [ichitaso](https://ichitaso.com/apt)                                                                          |
| Kalm                      | ❌          | Respring loops                                      | A beautiful first sight                                                                                                | [Chariz](https://repo.chariz.com/)                                                                            |
| Laetus                    | ⭕          | User apps can't be injected without no-sandbox      | Unparalleled keyboard customisation                                                                                    | [SparkDev](https://sparkdev.me/)                                                                              |
| LockApps                  | ✔️         | -                                                   | Add an App Library with your favorite apps to the LS                                                                   | [Ginsu](https://repo.ginsu.dev/)                                                                              |
| Lower                     | ✔️         | -                                                   | Change media controls/notifications height on iOS 11+                                                                  | [Packix](https://repo.packix.com/)                                                                            |
| Neonboard                 | ⭕          | Theming application icons are bugged                | none                                                                                                                   | [ArtikusHG](https://artikushg.github.io/)                                                                     |
| NewTerm 2                 | ✔️         | -                                                   | A powerful terminal app for iOS                                                                                        | [Chariz](https://havoc.app/)                                                                                  |
| OTADisabler               | ✔️         | -                                                   | Delete and disable OTA badge                                                                                           | [ichitaso](https://ichitaso.com/apt)                                                                          |
| PerfectTime               | ✔️         | -                                                   | Adds second line in status bar for showing the date on notched devices                                                 | [Johnzaro's](https://johnzaro.github.io/cydia/)                                                               |
| PomPom                    | ✔️         | -                                                   | A tidy lock screen redesign                                                                                            | none                                                                                                          |
| ProGesture                | ❌          | Crashes to safemode                                 | Modern gestures, iPad features, and many unique features but lightweight and less battery drain                        | [Packix](https://repo.packix.com/)                                                                            |
| QuitAll                   | ✔️         | -                                                   | One tweak to quit them all                                                                                             | [Chariz](https://repo.chariz.com/)                                                                            |
| Relocate Reborn           | ⭕          | Doesn't change location                             | Changes GPS location                                                                                                   | none                                                                                                          |
| Rose                      | ✔️         | -                                                   | The most advanced and feature rich system wide haptic feedback tweak                                                   | [Taurige Github](https://github.com/Traurige/Dress)                                                           |
| S8Edge                    | ✔️         | -                                                   | Brings Galaxy S8 Infinity to iOS                                                                                       | [Bruno Andrade's Repo](https://brunonfl.github.io/)                                                           |
| Shuffle                   | ⭕          | Sometimes crashes settings                          | Mix up your preferences                                                                                                | [CreatureCoding](https://creaturecoding.com/repo)                                                             |
| Snapper 2                 | ✔️         | -                                                   | Pin screenshots on the screen                                                                                          | [Havoc](https://havoc.app/)                                                                                   |
| SnowBoard                 | ⭕          | Theming application icons are bugged                | Theming engine                                                                                                         | [SparkDev](https://sparkdev.me/)                                                                              |
| Spectrum                  | ✔️         | -                                                   | Customize system colors                                                                                                | [Skitty](https://skitty.xyz/repo/)                                                                            |
| Starfish Beta             | ⭕          | Activating spotlight crashes                        | The long-awaited HS redesign                                                                                           | [Dynastic](https://repo.dynastic.co/)                                                                         |
| SwipeExtenderX            | ⭕          | User apps can't be injected without no-sandbox      | Reinvent your keyboard with this full remake of the legendary SwipeExpander tweak, designed to work on modern iOS      | [Chariz](https://repo.chariz.com/)                                                                            |
| System Info               | ✔️         | -                                                   | System information in Settings app > General > About, and other sections. Set boot-nonce, save shsh, battery info, etc | [ARX8x](https://apt.arx8x.net/)                                                                               |
| Tako                      | ❌          | Crashes to safemode                                 | Notification priority hub tweak                                                                                        | [Xyaman Repo](https://repo.xyaman.xyz/)                                                                       |
| TetherMe                  | ✔️         | -                                                   | Dynamically enables native tethering for iOS 8+ devices                                                                | [BigBoss](http://apt.thebigboss.org/repofiles/cydia)                                                          |
| Tranzlo                   | ⭕          | User apps can't be injected without no-sandbox      | A life savior translator tweak                                                                                         | [MiRO92](https://miro92.com/repo)                                                                             |
| TweakSettings             | ✔️         | -                                                   | Dedicated settings app for tweaks                                                                                      | [CreatureCoding](https://creaturecoding.com/repo)                                                             |
| Ultrasound                | ✔️         | -                                                   | The volume HUD you deserve                                                                                             | [Dynastic](https://repo.dynastic.co/)                                                                         |
| Vinyl                     | ✔️         | -                                                   | A simplified look for the lockscreen music player                                                                      | [BigBoss](http://apt.thebigboss.org/repofiles/cydia)                                                          |
| Xen HTML                  | ⭕          | Can't add widgets                                   | Run HTML widgets on the Lockscreen and Homescreen                                                                      | [Matchstic](https://xenpublic.incendo.ws/)                                                                    |
| croutons13                | ✔️         | -                                                   | Brings croutons tweak to iOS 13+                                                                                       | [Ren](http://repo.lauren.sh/)                                                                                 |
| dotto+                    | ✔️         | -                                                   | Notifications, your style                                                                                              | [Dynastic](https://repo.dynastic.co/)                                                                         |
| lockdown beta             | ✔️         | -                                                   | Re-enables passcode functionality on A10/A11 devices                                                                   | [krit's repo](https://repo.krit.me/)                                                                          |
