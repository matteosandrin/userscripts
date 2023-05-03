# Matteo's Userscripts

**WARNING**: All the scripts in this repository contain `@downloadURL` and `@updateURL` tags that fetch new versions of the script periodically. If you prefer to turn this feature off, remove the `@downloadURL` and `@updateURL` tags after install.

To run any of the scripts in this repository, please install a userscript browser extension. The one I use is [Tampermonkey](https://chromewebstore.google.com/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo). 

## cobalt-clicker ([install](https://raw.githubusercontent.com/matteosandrin/userscripts/main/cobalt-clicker.user.js))

The Cobalt platform is used by many employers to manage the immigration journey of their employees. To access Cobalt you go to a third party page, click a button, and then land on Cobalt. This userscript does that sequence automatically. When the third-party page ([gadeloitte.com](gadeloitte.com)) is visited, the script automatically clicks the button labeled "Enter you immigration details", switches to the new tab, and then closes the original tab.
