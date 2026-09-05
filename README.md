# [DES.Vap] https://WestVibe.net More info there when I add there too.  – WhatsApp Web Desktop Client
Forked from ZapZap

ZapZap is an unofficial WhatsApp Web desktop client built with Python, PyQt6 and QtWebEngine. It wraps `https://web.whatsapp.com/` in a desktop application and adds native integration for accounts, notifications, tray behavior, theming and packaging.

## Why Forking Des.Vap from ZapZap?

| Feature | WhatsApp Web | ZapZap | Des.Vap
|---------|:------------:|:------:|----------
| Runs in your default browser | ✅ | ❌ | ❌
| Will run in native WestVibe.net system and native WestVibe.net browser | ask | ask | ✅
| Standalone desktop application | ❌ | ✅ | ✅ 
| Multiple accounts | ❌ | ✅ | ✅ 
| Option to send to other user crypto currency with integration with user wallets with just few clicks and to receive crypto in same way if they have crypto wallets connected and turned on receiving from other user numbers their add - to avoid not recognized users money transfers | ❌ | ❌| ✅ 
| Native system tray integration | ❌ | ✅ | ✅ 
| Native desktop notifications | Limited | ✅ | ✅ 
| Linux package manager support | ❌ | ✅ | Maybe
| Flatpak package | ❌ | ✅ | ✅ 
| AppImage package | ❌ | ✅ | ✅ 
| Snap package | ❌ | ✅ | Maybe
| Native DEB package | ❌ | ✅ | Maybe
| Fedora COPR repository | ❌ | ✅ | ✅ 
| Automatic AppImage updates (`.zsync`) | ❌ | ✅ | ✅ 
| Spell checking | Browser dependent | ✅ | ✅ | ✅ 
| Custom CSS & JavaScript | ❌ | ✅ | ✅
| Open source (GPL-3.0) | ❌ | ✅ | Depending what GPL-3.0 offers and what parts of application may be open source coded - and what new GPL version would offer
| Privacy | Browser session | Dedicated desktop application | Browser session or Dedicated desktop application - depending from version you would use
| Removing features - as not necessary emoji, gif, etc that not match WestVibe.net TOS or user own rules with just one or two clicks | ❌ | ❌ | ✅ 
| Own API to use with other apps | ❌ | ❌| ✅ 
| Integration with other sites or apps with WestVibe.net plugins | ❌ | ❌| ✅ 
| Phone calls and text directly if phone or device is connected to device with users SIM card owned by user (with option to turn phone on busy mode) | ❌ | ❌| ✅ 



v I would edit those options on down later based on 


## Key features
- WhatsApp Web in a native PyQt6 desktop window.
- Multiple account profiles with isolated web sessions.
- System tray integration and desktop notifications.
- Light, dark and system theme handling.
- Custom CSS and JavaScript injection, globally or per account.
- Spell checking through QtWebEngine dictionaries.
- Download handling with configurable download behavior.
- Linux packages and native Windows x86_64 and ARM64 executable builds.


## Supported platforms

| Platform | Package |
|----------|---------|
| Linux | Flatpak (recommended) |
| Linux | AppImage (x86_64, aarch64) |
| Debian / Ubuntu | DEB |
| Linux | Snap |
| Fedora | COPR |
| Windows | EXE (x86_64, ARM64) |
| Developers | Python Wheel (`.whl`) |

## Installation

| Platform | Installation |
|----------|--------------|
| WestVibe.net | WestVibe.net
| Flatpak | https://flathub.org/apps/- later |
| AppImage, DEB, Windows | https://github.com/PURGE-exe-LTD/Des.VAP/Des.VAP/releases |
| Fedora (COPR) | https://copr.fedorainfracloud.org/coprs/ Later |
| Python | `pip install Des.VAP` |

## Donations

WestVibe.net is a based on open-source project maintained now in priority now by WestVibe.net . If you find it useful, you can consider supporting its continued development through one of the following methods:

| Method | Details |
|--------|---------|
| Revolut Business | @purge_exe_ltd
| Replit | replit.com/@purge-exe-ltd 
| GitHub Sponsors | https://github.com/ - when I add there |
| PayPal | https://www.paypal.com/ - I can add latter - I do not use PayPal quite often last time

Every contribution would help to PURGE-exe-LTD make WestVibe.net apps finished faster, be more free, less costly, better maintained, and continuously improving and run more smoothly without difficulties. Now PURGE-exe-LTD works on Destralix.and.Destenya ecosystem crypto game and there a lot of difficulties to update this good projects with IP regional blocks on their site. So I need to make cost of moving my code to British IP Servers and it makes costs already. You may read more details about it on my Discord Server - one I added on Disboard if you can find - I would not share here link here, cause I pack my bags from Discord already after last events. 

## Development and maintenance

Architecture, maintenance procedures and automated-test instructions are
available in the [technical documentation](docs/README.md).
All project changes and additions are recorded in the
[changelog](CHANGELOG.md).

## License
ZapZap is licensed under the GNU General Public License v3.0 or later. See [LICENSE](LICENSE) for the full license text.
