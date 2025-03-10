# Update Guide

All software has bugs, and new updates to software can sometimes have regressions that break features that were working fine in previous versions.

Unfortunately when it comes to apps on the Apple App Store, you can only ever download the latest software, and you don't have any access to older versions.

This means, if you're a professional Final Cut Pro editor, you need to be very careful about keeping copies of older versions of Final Cut Pro, Compressor and Motion as backups incase there's bugs, but also incase you have to access older Libraries in the future that may not open in the latest version of Final Cut Pro.

You can learn more about backing up Final Cut Pro on Apple's site [here](https://support.apple.com/en-au/HT203010).

You can read our current recommendations below:

---

## macOS Sonoma

Generally speaking, upgrading from **macOS Ventura to macOS Sonoma** is fairly smooth sailing, with no major widespread issues reported.

However, it's worth reading Larry Jordan's post on [Don’t Hurry to Upgrade](https://larryjordan.com/articles/caution-dont-hurry-to-upgrade/).

If you're still on much older version of macOS and Final Cut Pro, such as **Final Cut Pro 10.6.5** - keep in mind that FxPlug3 was depreciated and removed in Final Cut Pro 10.6.6, so older plugins may stop working.

Keep an eye on the [Final Cut Pro bug tracker](/bugtracker/) for more niche issues too before updating.

If you use **MotionVFX**, mLUT, mFlare 2, mFilmLook, mMuppet & mTracker all requires updates for macOS Sonoma.

**MotionVFX** also reports on [Twitter](https://twitter.com/motionVFX/status/1724434901804458426):

> ⚠️ On another note, If you're having issues with our products on macOS Sonoma (mainly red screen in FCP), please make sure to update mInstaller (3.0.2 version) 🚀Only once that's done, uninstall the product and install it again (don't use the "repair" option this time) 😉

If you can't use your camera or video output device after updating to **macOS Sonoma 14.1**, Apple has released a workaround.

Starting in **macOS Sonoma 14.1**, cameras and video output devices that don't use modern system extensions won't be available to use unless you restore the legacy settings. You can learn more [here](https://support.apple.com/en-us/HT213969).

---

## Final Cut Pro 10.7

**Final Cut Pro 10.7** was released on the Mac App Store on 30th November 2023.

If you're currently using **Final Cut Pro 10.6.10** on macOS Ventura or Sonoma, there are currently no major reported issues that would prevent you from updating.

{.compact}
| Plugin                   | Known Issues                                                                                            |
|--------------------------|---------------------------------------------------------------------------------------------------------|
| BRAW Toolbox             | No Known Issues                                                                                         |
| Color Finale             | No Known Issues                                                                                         |
| CommandPost              | No Known Issues                                                                                         |
| CoreMelt                 | No Known Issues                                                                                         |
| FxFactory                | No Known Issues                                                                                         |
| Generic Motion Templates | No Known Issues                                                                                         |
| Gyroflow Toolbox         | No Known Issues                                                                                         |
| Marker Toolbox           | No Known Issues                                                                                         |
| MotionVFX                | No Known Issues                                                                                         |

---

## Final Cut Pro 10.6.10

**Final Cut Pro 10.6.10** was released on the Mac App Store on 6th October 2023.

FxFactory has confirmed that this fixes object tracking and face recognition for any FxFactory plug-ins working on the Title layer. Woohoo!

If you're currently using **Final Cut Pro 10.6.9** on macOS Ventura or Sonoma, there are currently no major reported issues that would prevent you from updating.

{.compact}
| Plugin                   | Known Issues                                                                                            |
|--------------------------|---------------------------------------------------------------------------------------------------------|
| BRAW Toolbox             | No Known Issues                                                                                         |
| Color Finale             | [Requires Color Finale 2.7.0 Build 552](https://colorfinale.com)                                        |
| CommandPost              | No Known Issues                                                                                         |
| CoreMelt                 | No Known Issues                                                                                         |
| FxFactory                | No Known Issues                                                                                         |
| Generic Motion Templates | No Known Issues                                                                                         |
| Gyroflow Toolbox         | No Known Issues                                                                                         |
| Marker Toolbox           | No Known Issues                                                                                         |
| MotionVFX                | mLUT, mFlare 2, mFilmLook, mMuppet & mTracker all requires updates for macOS Sonoma                     |

---

## Final Cut Pro 10.6.9

**Final Cut Pro 10.6.9** was released on the Mac App Store on 19th September 2023.

This update drops support for macOS Monterey - only macOS Ventura and Sonoma are now supported.

This update unfortunately breaks any FxPlug4 effects that use the [Analysis API](https://developer.apple.com/documentation/professional_video_applications/fxanalysisapi_v2?language=objc) on Titles.

**FxFactory** writes:

> Final Cut Pro 10.6.9 is now available on the Mac App Store. This version breaks all FxFactory products that perform object tracking or face recognition through the Title layer.
>
> Regrettably this constitutes the entirety of our catalog featuring object tracking or face detection, since developers and users alike have come to favor the Title layer for its flexibility.
>
> Because of the large number of products affected, we recommend that you do not apply this update.

Read more about this bug [here](https://fxfactory.com/news/finalcutpro-10.6.9-skip-the-update/).

If you use FxFactory Trackers, we recommend sticking with an earlier version of Final Cut Pro for the time being.

CoreMelt's Tracking Tools are not affected, as they don't use the Analysis API on their Title effects.

If you're currently using **Final Cut Pro 10.6.8** on macOS Ventura or Sonoma, and don't use FxFactory's Trackers, then there are currently no major reported issues that would prevent you from updating.

Motion templates with an applied **Align To** behavior also display an incorrect animation.

{.compact}
| Plugin                   | Known Issues                                                                                            |
|--------------------------|---------------------------------------------------------------------------------------------------------|
| BRAW Toolbox             | No Known Issues                                                                                         |
| Color Finale             | [Requires Color Finale 2.7](https://colorfinale.com)                                                    |
| CommandPost              | No Known Issues                                                                                         |
| CoreMelt                 | No Known Issues                                                                                         |
| FxFactory                | [Tracking using Title Templates Broken](https://fxfactory.com/news/finalcutpro-10.6.9-skip-the-update/) |
| Generic Motion Templates | No Known Issues                                                                                         |
| Gyroflow Toolbox         | No Known Issues                                                                                         |
| Marker Toolbox           | No Known Issues                                                                                         |
| MotionVFX                | [Tracking using Title Templates Broken](https://fxfactory.com/news/finalcutpro-10.6.9-skip-the-update/) |

---

## Final Cut Pro 10.6.8

**Final Cut Pro 10.6.8** was released on the Mac App Store on 1st August 2023.

If you're currently using **Final Cut Pro 10.6.6 or earlier** we recommend sticking with that for the time being, as this release has a [lot of unreproducible crashes](https://github.com/CommandPost/FCPCafe/issues/238).

However, if you're using **Final Cut Pro 10.6.7** we recommend updating, as it resolves some issues with the Viewer going black and various crashes.

You can learn more about the issues in **Final Cut Pro 10.6.7** [here](https://github.com/CommandPost/FCPCafe/issues/223).

{.compact}
| Plugin                   | Known Issues                                                                                            |
|--------------------------|---------------------------------------------------------------------------------------------------------|
| BRAW Toolbox             | No Known Issues                                                                                         |
| Color Finale             | No Known issues                                                                                         |
| CommandPost              | No Known Issues                                                                                         |
| CoreMelt                 | No Known Issues                                                                                         |
| FxFactory                | No Known Issues                                                                                         |
| Generic Motion Templates | No Known Issues                                                                                         |
| Gyroflow Toolbox         | No Known Issues                                                                                         |
| Marker Toolbox           | No Known Issues                                                                                         |
| MotionVFX                | No Known Issues                                                                                         |