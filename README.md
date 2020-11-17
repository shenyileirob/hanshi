# Hanshi (MWG3_demo)
A handwriting font with full support for Hudum Mongolian, Sibe, Manchu and Manchu Ali Gali

## Features
* Multi-language support: Hanshi is a demo font for Hudum Mongolian (ᠬᠤᠳᠦᠮ᠋ ᠮᠣᠩᠭᠣᠯ), Sibe (ᠰᡳᠪᡝ), Manchu (ᠮᠠᠨᠵᡠ), and Manchu Ali Gali (ᠮᠠᠨᠵᡠ ᠠᠯᡳ ᡬᠠᠯᡳ). It supports phonetically, graphetically, and (Menksoft)-graphically encoded text.
* Handwriting font: Hanshi is a handwriting font, mimicking smooth joining and adjusted kerning in handwriting by means of juncture segmentation and substantial contextual substitutions.
* Proper placement of Manchu (Ali Gali) diacritics: Manchu (Ali Gali) diacritics are properly placed around consonant-vowel junctures instead of just beside consonants or vowels.
* Unbounded gender propagation: Unbounded progressive gender propagation is implemented in this font: ᠠᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭ ᠡᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠯᠢᠭ.
* Prompt for illicit strings: Invalid control characters are rendered visible in this font, and it clearly differentiates illicit positional forms from out-of-context forms (segments terminated by ZWJs) or abbreviations (segments terminated by nirugus): ***s*** = ᠰ, ***s***+`ZWJ` = ᠰ‍, ***s***+`nirugu` = ᠰ᠊; ***bey*** = ᠪᠡᠶ (halfway in typing ***bey_e*** ᠪᠡᠶ᠎ᠡ).

## Representation tips
In the representations below, \<⁰\> = `CGJ` = `U+034F`, \<¹\> = `FVS1` = `U+180B`, \<³\> = `FVS3` = `U+180D`, \<*ʔ*\> = `SSBM` = `U+1807`.
* ***i*** as a medial offglide
	* Regular double-shin: no FVS
		* ***ail***
	* Irregular single-shin: `CGJ`
		* ***nai***\<⁰\>***ma***
* ***y***
	* Regular hooked shin: no FVS
		* ***mayig***
	* Irregular hookless shin: `CGJ`
		* ***namay***\<⁰\>***i***, ***čimay***\<⁰\>***i***, ***say***\<⁰\>***i***
* (*o*) ***u*** (*ö*) ***ü*** after an initial consonant
	* Irregular bare belly: `FVS3`
		* ***bü***\<³\>***ü***, ***xü***\<³\>***ü***, ***xü***\<³\>
	* Irregular hollow belly: `CGJ`
		* ***mü***\<⁰\>, ***d***\<¹\>***u***\<⁰\>, ***ču***\<⁰\>
	* Regular forms found in the 12 syllabaries: no FVS
* ***g***
	* Feminine stray: no FVS
		* ***gram***
	* Feminine coda in feminine shaping context: no FVS
		* ***bilig*** (neuter word)
		* ***ǰigde*** (feminine word)
		* ***bolšëwig*** (bigender word)
		* ***migman*** (masculine word)
	* Feminine coda in masculine shaping context: `FVS3`
		* ***og***\<³\>***yu***, ***abisig***\<³\> (masculine word)
	* Masculine coda in masculine shaping context: no FVS
		* ***mëxanig*** (bigender word)
	* Masculine coda in feminine shaping context: `CGJ`
		* ***nig***\<⁰\>***ta*** (masculine word)
		* ***ig***\<⁰\>***či*** (neuter word)
* Common alternative forms of ***a o ö ü n t d***: `FVS1`
	* ***aü***\<¹\>***t***\<¹\>***o***\<¹\>, ***sëkü***\<¹\>***n***\<¹\>***d***\<¹\>, ***xaramö***\<¹\>***ren***, ***a***\<¹\>
* Vowel-led second stems: `SSBM`
	* ***altan***\<*ʔ*\>***odo***, ***buyan***\<*ʔ*\>***öljei***, ***čimed***\<*ʔ*\>***odcar***, ***čog***\<*ʔ*\>***agula***

## Preview
https://shenyileirob.github.io/hanshi/

## Download
https://raw.githubusercontent.com/shenyileirob/hanshi/main/MWG3_demo.ttf
