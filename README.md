# SimSig-Simulation-Picker
This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.txt). This basically means you can redistribute this product with modification, for patent or private use, as long as you accredit all contributors and keep the license on your derivation of the project. You may NOT distribute the code as closed-source. Please follow the aforementioned link for more information.

## About
This is an HTML page, with associated JavaScript and CSS, that picks a random SimSig simulation (out of the full pool of British SimSig sims) with all associated settings.

The common settings (seen across most, if not all sims) are:
- Temporary speed restrictions (TSR)
- Adverse weather conditions
- Automatic route settings (ARS)
- Train operated route release (TORR)
- Absolute block (AB)
- Level crossings (LC)
- Difficulty lists (vary between simulations)
- Era lists (vary between simulations)
- Scenarios (vary between simulations)

Certain simulations have unique options, these are all included in the picker. Six miscellaneous variables are reserved for this purpose. For example, the Marylebone simulation has three miscellaneous variables used, one is a boolean (Autum overlaps toggle), two are arrays for which a random value is picked (Failures and LUL Area size).

The program, as of 2 November 2021, is up-to-date aside from an omission of the recently released Doncaster South simulation.

## Usage
This program is as simple as pressing the Generate button on the page. If you'd like to filter out sims (such as paid ones you don't own), you can manually check them or use disable/enable all in the dropdown.

## Utilized Libraries
Bootstrap was used for styling purposes, meaning for the correct appearance, an internet connection is required. The script still functions regardless.
