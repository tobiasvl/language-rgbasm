# RGBASM language support in Atom

Adds syntax highlighting to RGBASM assembly files in [Atom](https://atom.io).

## RGBASM

RGBASM is the assembler dialect used for programming Game Boy games with the [Rednex Game Boy Development System](https://rednex.github.io) (RGBDS).

This is sometimes erroneously referred to as "Z80 assembler"; although the Game Boy's CPU is similar to Z80 and 8080, it's distinct, and using Z80 syntax highlighting isn't ideal, especially when using RGBASM features.

### Language reference

* [RGBASM language documentation](https://rednex.github.io/rgbds/rgbasm.5.html)
* [RGBASM Game Boy CPU opcode reference](https://rednex.github.io/rgbds/gbz80.7.html)

## To do

See [issues](https://github.com/tobiasvl/language-rgbasm/issues) for known bugs and planned features.

Please open an issue to report something. Pull requests are more than welcome.

## Related grammars

This grammar was inspired by other related grammars, but focuses on coverage of RGBASM, including features from newer versions of RGBDS.

* https://github.com/Bananattack/rgbds_textmate – RGBASM grammar for TextMate
* https://github.com/DonaldHays/rgbds-vscode/blob/master/syntaxes/rgbds-asm.tmLanguage - RGBASM grammar for VSCode
* https://atom.io/packages/language-gb – TASM grammar for Atom
* https://atom.io/packages/language-z80asm – generic Z80 grammar for Atom
