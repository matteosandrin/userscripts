# Matteo's Userscripts

To run any of the scripts in this repository, please install a userscript browser extension. The one I use is [Tampermonkey](https://chromewebstore.google.com/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo). 

**WARNING**: The scripts in this repository include `@downloadURL` and `@updateURL` tags that enable the scripts to automatically fetch new versions periodically. However, by default, Tampermonkey is not configured to search for updates. To enable this feature, navigate to the script settings and select the "Check for updates" option.

## cobalt-clicker ([install](https://raw.githubusercontent.com/matteosandrin/userscripts/main/cobalt-clicker.user.js))

The Cobalt platform is utilized by employers to manage their employees' immigration process. To access Cobalt, users typically navigate to a third-party SSO page and click a button that redirects them to the Cobalt site. This userscript streamlines the process by automating the sequence. Specifically, when the user visits [gadeloitte.com](gadeloitte.com), the script automatically clicks the button labeled "Enter your immigration details", opens a new tab, and closes the original tab.
