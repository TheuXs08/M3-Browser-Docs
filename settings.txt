M3 Browser — Settings Guide

This guide explains the settings available in M3 Browser and how they affect your browsing experience.

Search

Search engine

Choose the search engine used when searching from the browser.

Available options:

- Google
- Bing
- DuckDuckGo
- Brave

Select an option from the button group.

Home URL
Enter the website that M3 Browser should use as its homepage.

Example:

https://google.com

You can enter any valid URL.

---

WebView
These settings control how websites are rendered and behave inside M3 Browser.

JavaScript
Enables or disables JavaScript on websites.
JavaScript is required by many modern websites for interactive features, web applications, menus, login systems, and other functionality.
Disabling JavaScript may cause some websites to stop working correctly.

Media autoplay
Controls whether websites can automatically play media.
When enabled, websites may start playing audio or video without requiring additional interaction.

Pre-rendering
Enables WebView pre-rendering when supported by the installed WebView.
Pre-rendering can allow supported pages to begin loading before you navigate to them.

Zoom
Controls the default page zoom level.
Move the slider to choose the desired zoom level.

- "1–100": Apply the selected zoom level.
- "0": Use the normal page size.

---

User-Agent
The User-Agent identifies the browser to websites.

M3 Browser provides separate User-Agent presets for mobile and desktop browsing.

Phone

Available presets:

- Default
- Chrome
- Safari

These presets make websites identify M3 Browser as a mobile browser.

Computer

Available presets:

- Chrome
- Firefox
- Safari

These presets make websites identify M3 Browser as a desktop browser.
Changing the User-Agent can affect how websites display their interface or which version of a website they provide.

---

App
These settings control M3 Browser itself.

Enable tabs
Enables the browser's tab functionality.
When disabled, M3 Browser operates without the normal tab interface.

Enable progress bar
Displays a progress indicator while a page is loading.

Restore tabs
Restores previously open tabs when supported by the browser's saved session data.

---

Data
These settings control website data stored by WebView.

Cookies
Enables or disables cookies.
Cookies are commonly used by websites for:

- Login sessions
- Preferences
- Shopping carts
- Authentication
- Other website functionality

Disabling cookies may cause some websites to lose functionality or require you to log in repeatedly.

Third-party cookies
Controls whether third-party websites can use cookies.
Some websites may rely on third-party cookies for embedded content or cross-site functionality.

DOM Storage
Controls Web Storage functionality used by websites, including:

- "localStorage"
- "sessionStorage"

Some modern websites require DOM Storage to work correctly.

Delete all data
Deletes browser-related website data stored by M3 Browser.
Depending on what the browser clears, this may include:

- Cookies
- Cache
- Web Storage
- History
- Other locally stored WebView data

«Warning: This action cannot be easily undone.»

---

Privacy Policy

View

Opens the M3 Browser Privacy Policy.
The policy explains how M3 Browser handles local browser data, permissions, and interaction with third-party websites.

---

Licenses

View

Displays the open-source software and other third-party components used by M3 Browser, together with their applicable licenses and copyright notices.

---

Developer
Developer settings are intended primarily for testing, development, and troubleshooting websites and WebView behavior.

Developer Mode

Enables additional developer-oriented functionality.
This setting should generally remain disabled during normal browsing unless you need the available development features.

WebView and WebKit version
Displays information about the WebView installed on the device and the AndroidX WebKit version used by M3 Browser.
The displayed information includes:

- Version name
- Version code
- WebKit version

The WebView version is provided by the Android System WebView or another WebView provider selected by the device.

Allow mixed content
Controls whether an HTTPS page can load resources using HTTP.
Allowing mixed content can make older websites work, but it can reduce the security of HTTPS pages.
Keep this disabled unless it is required for testing or for a specific website.

Enable WebView debugging
Enables WebView debugging for development and troubleshooting.
This option is intended for developers and should normally remain disabled during regular browsing.

Show page load time
Displays the approximate time taken for a page navigation to reach the WebView's "onPageFinished" event.
The value is displayed in milliseconds.
Example:

Load time: 842 ms

The measurement is intended for diagnostics and is not a complete measurement of every network, rendering, or page-processing operation.

---

About

Check for updates
Checks whether a newer version of M3 Browser is available.

Set as default browser
Opens the Android settings used to select the default browser application.
After selecting M3 Browser as the default browser, links opened by other applications can be handled by M3 Browser.

---

Recommended configuration

For normal everyday browsing:

JavaScript: On
Media autoplay: On
Pre-rendering: On
Zoom: "0"
Cookies: On
Third-party cookies: Off
DOM Storage: On
Allow mixed content: Off
WebView debugging: Off
Show page load time: Off
Developer Mode: Off

These settings provide a general-purpose configuration, but some websites may require different settings to function correctly.
