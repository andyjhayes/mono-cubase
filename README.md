# Monogram + Cubase #

This is a collection of Monogram assignments for Steinberg Cubase, version 11 or later.

### Prerequisites ###

- [Monogram Creator](https://monogramcc.com/download/)
- [Monogram Creative Console](https://monogramcc.com/) (Not developed or tested with Palette Gear)
- [Steinberg Cubase](https://captureone.com/) (Version 11 or later required)

---

## Setup Instructions ##

### Add Monogram as Generic Remote to Cubase ###

1. [Download and unzip latest release](https://github.com/andyjhayes/mono-cubase/releases); copy the unzipped folder to a safe location like your Documents folder.
2. Locate <code>Monogram + Cubase Generic Remote > MCC-GenericRemote.xml</code> inside downloaded package.
3. In the Cubase menu bar, go to Studio > Studio Setup. Select or add a Generic Remote and select 'Import'.
4. Import the <code>MCC-GenericRemote.xml</code> file as located in step 2 above.

### Add integration bundle to Monogram Creator ###

1. In Monogram Creator, go to File > Preferences > Integrations.
2. Hit the + button (lower right); this should open a file browser.
3. Browse for your <code>mono-cubase</code> folder, then double-click it to look inside for the <code>cubase</code> folder.
4. Choose the <code>cubase</code> folder, then hit "Open" (bottom right).

---

## Disclaimers ##

This is purely a homebrewed set of Monogram assignments for Cubase. A few things to keep in mind:

- It isn't developed or endorsed by either company. 
- It's provided with no warranty and it may not work on your system.
- Future Cubase or Monogram updates might break it.
- It's licensed under <a href="https://opensource.org/licenses/MIT">MIT</a>. Pull requests and issues are welcome :)

### Known Limitations ###

- Some assignments are unavailable or impossible with Orbiter inner disc (inherent incompatibility).
- Customize View in Creator > Module Settings window does not display Cubase Mode assignments. Please use Presets View > Cubase Mode or Customize View > MIDI Mode and Keyboard Mode in order to select your chosen assignments.
