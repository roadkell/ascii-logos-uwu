## ThinkPad ASCII (actually, Unicode) logos for all your terminal needs — now in colors! 🏳️‍🌈 🏳️‍⚧️ ##

### Important ###

[Queer Svit](https://queersvit.org/) is a black queer-run independent team of volunteers from all over the world. With your support we help LGBTQ+ and BAME people affected by the war and/or political repressions get to safety by providing consultations, purchasing tickets, finding free accommodation and providing humanitarian aid.

Just like any other catastrophe, war affects the most those who are most vulnerable, including LGBTQ+ and BAME people while at the same time their troubles are often rendered invisible. But because our own team comprises LGBTQ+ and BAME people we see the specific challenges our beneficiaries face and understand how to help them.

Your donations make a difference; Queer Svit is run in large part on small donations from individual donors. We are grateful for any and all help to continue our work — thank you!

### Neofetch / HyFetch ###

* Install [HyFetch](https://github.com/hykilpikonna/hyfetch) (an updated fork of the original [Neofetch](https://github.com/dylanaraps/neofetch) with 24-bit color support)
* Clone this repo *or* download individual files from the `fetch` subfolder
* Run `neowofetch` with desired arguments (see examples below) *or* modify your `~/.config/neofetch/config.conf` to make changes permanent
* Also check out non-pride flag-colored versions [here](https://github.com/roadkell/ascii-logos) <3

### Command line examples ###

```
neowofetch --ascii 'path/to/ibm-transpad-v.txt' --ascii_colors '#55CDFD' '#F6AAB7' '#FFFFFF'
```
![Neofetch with IBM TransPad logo (vertical)](./screenshots/ibm-transpad-v-full.png?raw=true)

```
neowofetch --ascii 'path/to/ibm-transpad-h.txt' --ascii_colors '#55CDFD' '#F6AAB7' '#FFFFFF'
```
![IBM TransPad logo (horizontal)](./screenshots/ibm-transpad-h.png?raw=true)

```
neowofetch --ascii 'path/to/ibm-twinkpad-h.txt' --ascii_colors '#55CDFD' '#F6AAB7' '#FFFFFF'
```
![IBM TwinkPad logo (horizontal)](./screenshots/ibm-twinkpad-h.png?raw=true)

```
neowofetch --ascii 'path/to/ibm-thiccpad-h.txt' --ascii_colors '#55CDFD' '#F6AAB7' '#FFFFFF'
```
![IBM ThiccPad logo (horizontal)](./screenshots/ibm-thiccpad-h.png?raw=true)

### Notes ###

* There are Unicode symbols in use beyond the classic charset of ASCII codepage 437 (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Symbols for Legacy Computing](https://en.wikipedia.org/wiki/Symbols_for_Legacy_Computing)), so make sure your terminal emulator and font support them. For example, [Unifont Upper](https://unifoundry.com/unifont/index.html) (`fonts-unifont` package in Ubuntu, `font-gnu-unifont` in Homebrew) and [Code2001](https://www.code2001.com/code2001.htm) fonts have the necessary glyphs. If images look distorted, try `*-lowres.txt` versions — they only use symbols from Unicode 1.0-3.2 which are likely supported in all Unicode-enabled environments.
* If your terminal doesn't have true color support, try color indices like `--ascii_colors 9 14 15` (result depends on your palette). Also, colorless versions are available in the `bw` subfolder.
* Enjoy!

### To do ###

* Make low-res versions restricted to the charset of ASCII CP437.

### Legal disclaimer ###

* I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.
* For guidelines on the permitted uses of the IBM logo, refer to <https://www.ibm.com/design/language/ibm-logos/8-bar/>.
* For guidelines on the permitted uses of the Lenovo and ThinkPad logos, refer to <https://www.lenovo.com/us/en/legal/copytrade/>.
