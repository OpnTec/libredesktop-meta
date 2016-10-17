# libredesktop-meta

The libredesktop-meta package takes care of customizing packages and settings for the libredesktop.

## Customizing browser settings
In the browser settings custom search, tiles, snippets can be set for browsers.

### What are we changing in the Firefox browser?

1) Directory Tiles:
in about:config: browser.newtabpage.directory.source
Wert: https://tiles.services.mozilla.com/v2/links/fetch/%LOCALE%
https://tiles.services.mozilla.com/v2/links/fetch/de für Deutsch.

2) about:home Snippets:
in about:config: browser.aboutHomeSnippets.updateUrl
Wert: https://snippets.cdn.mozilla.net/%STARTPAGE_VERSION%/%NAME%/%VERSION%/%APPBUILDID%/%BUILD_TARGET%/%LOCALE%/%CHANNEL%/%OS_VERSION%/%DISTRIBUTION%/%DISTRIBUTION_VERSION%/
(ich weiß nicht, was jeder Parameter "übersetzt" liefert

3) Search


## How and where do we configure profiles?

Im Profilverzeichnis eine Datei mit dem Namen user.js kann zur Konfiguration benutzt werden:
http://kb.mozillazine.org/User.js_file

Resources

Möglicherweise in diesem Zusammenhang interessant:
https://addons.mozilla.org/en-US/firefox/addon/cck2wizard/

NSIS Installer: http://nsis.sourceforge.net/Main_Page
