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
neowofetch --ascii 'color/ibm-transpad-v.txt' --ascii_colors '#FFFFFF' '#55CDFD' '#F6AAB7'
```
![Neofetch with IBM TransPad logo (vertical)](./screenshots/ibm-transpad-v-full.png?raw=true)

```
neowofetch --ascii 'color/ibm-transpad-h.txt' --ascii_colors '#FFFFFF' '#55CDFD' '#F6AAB7'
```
![IBM TransPad logo (horizontal)](./screenshots/ibm-transpad-h.png?raw=true)

```
neowofetch --ascii 'color/ibm-twinkpad-h.txt' --ascii_colors '#FFFFFF' '#55CDFD' '#F6AAB7'
```
![IBM TwinkPad logo (horizontal)](./screenshots/ibm-twinkpad-h.png?raw=true)

```
neowofetch --ascii 'color/ibm-thiccpad-h.txt' --ascii_colors '#FFFFFF' '#55CDFD' '#F6AAB7'
```
![IBM ThiccPad logo (horizontal)](./screenshots/ibm-thiccpad-h.png?raw=true)

```
neowofetch --ascii 'color/thiccpad-v.txt' --ascii_colors '#e32726' '#ffffff'
neowofetch --ascii 'color/thiccpad-h.txt' --ascii_colors '#e32726' '#ffffff'
```
![ThiccPad logo (vertical)](./screenshots/thiccpad-v.png?raw=true)
![ThiccPad logo (horizontal)](./screenshots/thiccpad-h.png?raw=true)

```
neowofetch --ascii 'color/pinkpad-v.txt' --ascii_colors '#ff66cc' '#ffffff'
neowofetch --ascii 'color/pinkpad-h.txt' --ascii_colors '#ff66cc' '#ffffff'
```
![PinkPad logo (vertical)](./screenshots/pinkpad-v.png?raw=true)
![PinkPad logo (horizontal)](./screenshots/pinkpad-h.png?raw=true)

### Notes ###

* If your terminal or your `*fetch` program doesn't support true color, try color indices like `--ascii_colors 15 14 9` for classic IBM logos and `--ascii_colors 1 15` for modern ones (result depends on your palette). Versions without color tags are available in `*-bw` subfolders.
* Default versions use Unicode characters beyond the charset of [code page 437](https://en.wikipedia.org/wiki/Code_page_437) (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Box Drawing](https://en.wikipedia.org/wiki/Box_Drawing)), so make sure your terminal emulator and font support them. For nostalgia purposes, `cp437-*` folders contain blockier versions restricted to the classic CP437 charset (though still coded in Unicode for compatibility).
* Enjoy!

### Legal disclaimer ###

* I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.
* For guidelines on the permitted uses of the IBM logo, refer to <https://www.ibm.com/design/language/ibm-logos/8-bar/>.
* For guidelines on the permitted uses of the Lenovo and ThinkPad logos, refer to <https://www.lenovo.com/us/en/legal/copytrade/>.
