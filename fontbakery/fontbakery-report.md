## FontBakery report

fontbakery version: 0.11.2

<h2>Check results</h2><details><summary><b>[8] Matemasie-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| nl_Latn (Dutch) | Shaper didn't attach acutecomb to uni0237 |
|  ^  | Shaper didn't attach acutecomb to J |

 [code: failed-language-shaping]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, canadian-aboriginal, math, coptic, tai-le, syriac, malayalam, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EAE LATIN CAPITAL LETTER A WITH BREVE AND ACUTE: try adding vietnamese
 * U+1EAF LATIN SMALL LETTER A WITH BREVE AND ACUTE: try adding vietnamese
 * U+25CC DOTTED CIRCLE: try adding one of: warang-citi, kayah-li, kharoshthi, dogra, thai, gunjala-gondi, tai-le, old-permic, duployan, canadian-aboriginal, phags-pa, soyombo, mandaic, miao, lao, mongolian, nko, tamil, oriya, tibetan, kaithi, sinhala, wancho, saurashtra, math, thaana, chakma, meetei-mayek, bengali, limbu, hanunoo, bassa-vah, lepcha, khojki, cham, ahom, syriac, malayalam, masaram-gondi, takri, buhid, symbols, tirhuta, tai-tham, sharada, adlam, buginese, myanmar, mende-kikakui, mahajani, yi, kannada, armenian, grantha, newa, balinese, osage, devanagari, sogdian, siddham, rejang, zanabazar-square, syloti-nagri, manichaean, brahmi, psalter-pahlavi, gurmukhi, modi, telugu, coptic, marchen, gujarati, hebrew, hanifi-rohingya, bhaiksuki, javanese, tifinagh, sundanese, music, khmer, tagbanwa, tai-viet, pahawh-hmong, new-tai-lue, caucasian-albanian, khudawadi, batak, tagalog, elbasan

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- A.alt

	- Hbar.alt1

	- Hbar.alt2

	- L.alt

	- L.alt2

	- M.alt

	- Q.alt

	- Q.ss2.alt

	- R.alt

	- S.alt

	- Z.alt

	- a.ss02

	- a.ss1.alt

	- b.alt

	- d.alt

	- eight.ss1.alt

	- f.alt

	- f.ss1.alt

	- five.ss1.alt

	- g.alt

	- g.alt2

	- germandbls.ss1.alt

	- h.ss1.alt

	- i.loclTRK

	- l.alt

	- m.alt

	- n.alt

	- o.alt

	- p.alt

	- periodcentered.loclCAT

	- q.alt

	- questiondown.ss1.alt

	- r.alt2

	- s.alt

	- s.ss1.alt

	- scedilla.ss1.alt

	- section.ss1.alt

	- seven.ss2.alt

	- t.alt

	- t.alt2

	- t.ss04

	- t.ss1.alt

	- three.ss1.alt

	- u.ss1.alt

	- uni004A0301

	- uni006A0301

	- uni1E9E.alt

	- uni1E9E.alt1

	- y.alt

	- y.ss1.alt

	- z.ss1.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: oslash	Contours detected: 2	Expected: 3

	- Glyph name: Emacron	Contours detected: 1	Expected: 2

	- Glyph name: Emacron	Contours detected: 1	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: oslash	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Bete-Bendi (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Koonzime (Latn, 40,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Basaa (Latn, 332,940 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Nzakara (Latn, 50,000 speakers), Sar (Latn, 500,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), South Central Banda (Latn, 244,000 speakers), Navajo (Latn, 166,319 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Dan (Latn, 1,099,244 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 2 | 6 | 127 | 7 | 118 | 0 |
| 0% | 0% | 1% | 2% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
