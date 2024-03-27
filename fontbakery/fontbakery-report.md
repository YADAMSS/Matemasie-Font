## FontBakery report

fontbakery version: 0.11.2

<h2>Check results</h2><details><summary><b>[11] Matemasie-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| nl_Latn (Dutch) | Shaper didn't attach acutecomb to uni0237 |
|  ^  | Shaper didn't attach acutecomb to J |

 [code: failed-language-shaping]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1259, but got 1091 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, coptic, old-permic, malayalam, math, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EAE LATIN CAPITAL LETTER A WITH BREVE AND ACUTE: try adding vietnamese
 * U+1EAF LATIN SMALL LETTER A WITH BREVE AND ACUTE: try adding vietnamese
 * U+25CC DOTTED CIRCLE: try adding one of: brahmi, symbols, new-tai-lue, gujarati, coptic, elbasan, pahawh-hmong, siddham, music, bengali, hebrew, duployan, sundanese, zanabazar-square, balinese, meetei-mayek, gurmukhi, kharoshthi, mahajani, marchen, myanmar, masaram-gondi, mongolian, takri, tagalog, syloti-nagri, sogdian, yi, dogra, javanese, newa, khmer, bhaiksuki, tifinagh, cham, armenian, gunjala-gondi, lao, adlam, modi, tamil, malayalam, osage, khojki, math, batak, sharada, chakma, mende-kikakui, lepcha, syriac, caucasian-albanian, sinhala, canadian-aboriginal, ahom, psalter-pahlavi, nko, hanifi-rohingya, khudawadi, tai-viet, rejang, phags-pa, devanagari, buginese, tai-tham, thai, grantha, wancho, thaana, telugu, hanunoo, kayah-li, warang-citi, mandaic, tibetan, kaithi, manichaean, bassa-vah, soyombo, tirhuta, saurashtra, miao, limbu, tai-le, old-permic, tagbanwa, oriya, kannada, buhid

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check that legacy accents aren't used in composite glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* ⚠ **WARN** Glyph "Aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Abreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Adieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Amacron" has a legacy accent component  (macron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Aring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Atilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ccaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Dcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ecaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Edieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Edotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Emacron" has a legacy accent component  (macron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gbreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Idieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Idotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ncaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ntilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Odieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Omacron" has a legacy accent component  (macron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Otilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Rcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Scaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Tcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ubreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Udieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Umacron" has a legacy accent component  (macron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wdieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ydieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "acutecomb" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni004A0301" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni006A0301" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- A.ss01

	- Hbar.001

	- Hbar.002

	- L.ss01

	- L.ss02

	- M.ss01

	- Q.ss01

	- Q.ss02

	- R.ss01

	- S.ss01

	- Z.ss01

	- a.ss01

	- a.ss02

	- b.ss02

	- d.ss02

	- eight.ss01

	- f.ss01

	- f.ss02

	- five.ss01

	- g.ss01

	- g.ss02

	- germandbls.ss01

	- h.ss01

	- i.loclTRK

	- l.ss02

	- m.ss01

	- n.ss01

	- newGlyph

	- o.ss02

	- p.ss02

	- periodcentered.loclCAT

	- q.ss02

	- questiondown.ss01

	- r.ss01

	- s.ss01

	- s.ss02

	- scedilla.ss01

	- section.ss01

	- seven.ss02

	- t.ss01

	- t.ss02

	- t.ss03

	- t.ss04

	- three.ss01

	- u.ss01

	- uni004A0301

	- uni006A0301

	- uni1E9E.ss01

	- uni1E9E.ss02

	- uogonek.ss01

	- y.ss01

	- y.ss02

	- z.ss01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: oslash	Contours detected: 2	Expected: 3

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: oslash	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Ma’di (Latn, 584,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Avokaya (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Dan (Latn, 1,099,244 speakers), Southern Kisi (Latn, 360,000 speakers), Aghem (Latn, 38,843 speakers), Lugbara (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Makaa (Latn, 221,000 speakers), Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), South Central Banda (Latn, 244,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Nzakara (Latn, 50,000 speakers), Navajo (Latn, 166,319 speakers), Bafut (Latn, 158,146 speakers), Ngbaka (Latn, 1,020,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Dutch (Latn, 31,709,104 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 4 | 7 | 127 | 7 | 115 | 0 |
| 0% | 0% | 2% | 3% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
