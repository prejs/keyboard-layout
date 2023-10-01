# Danish & Polish (QWERTY) Layout

US-standard QWERTY layout as base with a third and fourth layer available through the <kbd>AltGr</kbd>/<kbd>⌥ Option</kbd> key and <kbd>AltGr</kbd>/<kbd>⌥ Option</kbd>+<kbd>⇧ Shift</kbd>.

These additional layers provide support for Danish[^1][^2] and Polish[^3][^4] languages, and subjective selection of special characters, and common mathematical symbols from Danish, Polish (Programmers) and US-International[^5][^6] layouts for both Windows and Mac.

[^1]: https://en.wikipedia.org/wiki/QWERTY#Danish
[^2]: https://learn.microsoft.com/en-us/globalization/keyboards/kbdda
[^3]: https://en.wikipedia.org/wiki/QWERTY#Polish
[^4]: https://learn.microsoft.com/en-us/globalization/keyboards/kbdpl1
[^5]: https://en.wikipedia.org/wiki/QWERTY#US-International
[^6]: https://learn.microsoft.com/en-us/globalization/keyboards/kbdusx

## PC

![](./assets/layout-pc-qwerty.svg)

Windows sources:

- [KBDDAPLP](win/kbddaplp/KBDDAPLP.klc) with default system code page (1252) of the Danish (Denmark) language for non-Unicode applications
- [KBDPLDAP](win/kbdpldap/KBDPLDAP.klc) with default system code page (1250) of the Polish (Poland) language for non-Unicode applications

For convenience builds are added to GitHub _Releases_.

## Mac

![](./assets/layout-mac-qwerty.svg)

MacOS source:

- [Danish Polish International](mac/dapl.bundle/Contents/Resources/Danish%20Polish%20International.keylayout) with unicode coding

&nbsp;

# Danish & Polish (Colemak) Layout

Poor man's Colemak layout that provides support for Danish and Polish languages.

## PC

![](./assets/layout-pc-colemak.svg)

Windows sources:

- [KBDDAPLC](win/kbddaplc/KBDDAPLC.klc) with default system code page (1252) of the Danish (Denmark) language for non-Unicode applications
- [KBDPLDAC](win/kbdpldac/KBDPLDAC.klc) with default system code page (1250) of the Polish (Poland) language for non-Unicode applications

For convenience builds are added to GitHub _Releases_.

## Mac

![](./assets/layout-mac-colemak.svg)

MacOS source:

- [Danish Polish Colemak](mac/dapl.bundle/Contents/Resources/Danish%20Polish%20Colemak.keylayout) with unicode coding

&nbsp;

# Compare layouts

The Colemak layout is designed to make typing more efficient and comfortable by placing the most frequent letters on the home row. Since the layout was designed for english language, the following diagrams help understand if the goal is also met in other languages.

|                     | Diagrams of letter frequencies on QWERTY | Diagrams of letter frequencies on Colemak |
| ------------------- | ---------------------------------------- | ----------------------------------------- |
| **English** letters | ![](./assets/heatmap-qwerty-en.svg)      | ![](./assets/heatmap-colemak-en.svg)      |
| **Danish** letters  | ![](./assets/heatmap-qwerty-da.svg)      | ![](./assets/heatmap-colemak-da.svg)      |
| **Polish** letters  | ![](./assets/heatmap-qwerty-pl.svg)      | ![](./assets/heatmap-colemak-pl.svg)      |

&nbsp;
