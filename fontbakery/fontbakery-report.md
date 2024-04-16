## FontBakery report

fontbakery version: 0.12.1



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Matemasie-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[8] Matemasie-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: oslash	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Hbar.alt1

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

- d.alt

- eight.ss1.alt

- f.alt

- f.ss1.alt

- five.ss1.alt

- g.alt

- g.alt2

- germandbls.ss1.alt

- i.loclTRK

- l.alt

- m.alt

- n.alt

- o.alt

- p.alt

- periodcentered.loclCAT

- q.alt

- questiondown..alt

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

- uni030C.alt

- uni1E9E.alt

- uni1E9E.alt1

- y.alt

- y.ss1.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Nzakara (Latn, 50,000 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Basaa (Latn, 332,940 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Avokaya (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mango (Latn, 77,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Zapotec (Latn, 490,000 speakers), Sar (Latn, 500,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, tifinagh, tai-le, malayalam, old-permic, math, coptic, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+1EAE LATIN CAPITAL LETTER A WITH BREVE AND ACUTE: try adding vietnamese</li>
<li>U+1EAF LATIN SMALL LETTER A WITH BREVE AND ACUTE: try adding vietnamese</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: manichaean, phags-pa, wancho, marchen, lepcha, sogdian, batak, osage, hanifi-rohingya, tai-le, buhid, gurmukhi, old-permic, takri, math, kayah-li, nko, tifinagh, bengali, tamil, kharoshthi, cham, newa, ahom, masaram-gondi, syloti-nagri, meetei-mayek, coptic, dogra, miao, psalter-pahlavi, armenian, mahajani, gujarati, hebrew, buginese, grantha, tagalog, khmer, kaithi, mongolian, thaana, javanese, sharada, modi, siddham, bassa-vah, soyombo, brahmi, limbu, mende-kikakui, elbasan, gunjala-gondi, balinese, khudawadi, devanagari, saurashtra, syriac, caucasian-albanian, malayalam, thai, bhaiksuki, kannada, new-tai-lue, sinhala, symbols, myanmar, music, rejang, khojki, oriya, tirhuta, pahawh-hmong, chakma, adlam, duployan, tagbanwa, tibetan, tai-tham, hanunoo, lao, sundanese, tai-viet, zanabazar-square, mandaic, warang-citi, yi, canadian-aboriginal, telugu</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.505x (1505)</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;<a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 8 | 118 | 6 | 116 | 0 | 
| 0% | 0% | 0% | 3% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
