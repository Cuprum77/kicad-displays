# How to contribute

## Requests for new displays

- Make sure its not already in the repository or already requested
- Check the [display pinouts](pinouts/) to see if the display is already supported, either directly or indirectly through a similar display pinout
- Open an issue with [relevant information](#display-requests-issues)

Please note that a request does not entitle you to a display footprint or symbol.
And that these requests will be followed up on a best effort basis.

### Display requests issues

If you want to request a new display, please open an issue with the following information:

- Display name
- Display datasheet

If no datasheet is available, please provide a link to the display on Aliexpress or similar.

## Contributing to the repository

Any contribution is welcome, whether it is a new display, a new footprint, or a new symbol!
But be aware that there is some quality control in place, and that not all contributions will be accepted if they do not meet the minimum requirements!

Make sure to avoid linking any file together in KiCAD as this is not properly supported by KiCAD yet.
There is currently no way to get KiCAD to reliably use relative paths!
If you are unfamiliar with the system, you also risk exposing your full file path to the public, which could include your real name!

### New symbols

- Suggest your changes in an issue or a pull request
- Make sure to create a pinout file for the display, if it is not already in the repository
- Continue with the existing naming convention for your new symbol
- Make sure to use the same pinout as the display datasheet, or the pinout file in the repository!
- Add the symbol to the [README.md](README.md) file in the root of the repository
- Submit a pull request with your changes

### New footprints

- Suggest your changes in an issue or a pull request
- Continue with the existing naming convention for your new footprint
- 3D models are optional, but greatly appreciated!
- Make sure that the footprint is correct and matches the display pinout
- Submit a pull request with your changes
