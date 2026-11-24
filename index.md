# Privacy Policy – Santa Pop-In

**Full product & privacy details:** [https://jem6.com/extensions/santa-pop-in#privacy](https://jem6.com/extensions/santa-pop-in#privacy)

Santa Pop-In does not collect, store, transmit, sell, or share any personal data. It has no accounts, no developer servers, no analytics, and no tracking.

## What Chrome stores locally (and syncs via Chrome Sync)

To remember your configuration, Chrome stores the following in your browser profile using `chrome.storage.sync` (synchronized across your signed-in Chrome browsers by Chrome itself when Chrome Sync is enabled—not collected by the developer):

- **User preferences:** enabled state, appearance frequency, Santa size, soft-sounds toggle, enabled acts, and light/tree decoration options.
- **Paused website hostnames:** only the hostnames of sites where you click *Pause site*.
- **Snooze timestamp & candy cane counter:** when a one-hour snooze expires, plus your running count of popped candy canes.

In addition, `chrome.storage.session` holds a transient browser-session timestamp of Santa's last appearance to space out animations across open windows; it is cleared when Chrome closes.

## Permissions & website access

- **`storage`:** saves your preferences, paused hostnames, snooze expiry, and candy cane count in `storage.sync`, and tracks appearance timing in `storage.session`.
- **`activeTab`:** when you click the toolbar icon to open the popup, reads the active tab's URL solely to extract its hostname for the *Pause site* button.
- **`alarms`:** wakes Santa and restores the toolbar badge when a one-hour snooze expires.
- **Website access (`<all_urls>`):** allows Santa's animations, snow, and optional decorations to render on ordinary web pages you visit without requiring a click on every page (Chrome restricts privileged browser pages).

## External links & clearing data

External links in the popup (the optional Ko-fi tip link and the *jem6* homepage link) open in a new tab only when you click them. You can unpause sites or wake Santa in the popup, clear extension storage in Chrome's extension settings, or uninstall Santa Pop-In to remove its stored data.

## Contact

Questions? Contact the developer via [https://jem6.com/#contact](https://jem6.com/#contact) or email johnniestang@gmail.com.
