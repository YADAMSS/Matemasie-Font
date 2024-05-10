## FontBakery report

fontbakery version: 0.12.5



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



<details><summary>[7] Matemasie-Regular.ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with ZeroDivisionError: float division by zero</p>
<pre><code>  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/fontbakery/checks/outline.py&quot;, line 366, in com_google_fonts_check_outline_direction
    if path.direction == 1:
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/beziers/path/__init__.py&quot;, line 558, in direction
    return math.copysign(1, self.signed_area)
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/beziers/path/__init__.py&quot;, line 541, in signed_area
    flat = self.flatten()
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/beziers/path/__init__.py&quot;, line 494, in flatten
    segs.extend(s.flatten(degree))
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/beziers/quadraticbezier.py&quot;, line 58, in flatten
    samples = self.sample(self.length/degree)
  File &quot;/home/runner/work/Matemasie-Font/Matemasie-Font/venv-test/lib/python3.10/site-packages/beziers/utils/samplemixin.py&quot;, line 20, in sample
    step = 1.0 / float(samples)

</code></pre>
 [code: failed-check]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking with fontTools.ttx <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>WARNING: name id 256 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 257 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 258 missing from name table</p>
 





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;<a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Makaa (Latn, 221,000 speakers), Bafut (Latn, 158,146 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Igbo (Latn, 27,823,640 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Kom (Latn, 360,685 speakers), Nzakara (Latn, 50,000 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nateni (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ebira (Latn, 2,200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Fur (Latn, 1,230,163 speakers), Bete-Bendi (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ejagham (Latn, 120,000 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, tifinagh, canadian-aboriginal, coptic, malayalam, old-permic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+1EAE LATIN CAPITAL LETTER A WITH BREVE AND ACUTE: try adding vietnamese</li>
<li>U+1EAF LATIN SMALL LETTER A WITH BREVE AND ACUTE: try adding vietnamese</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: saurashtra, sundanese, coptic, lao, tagbanwa, tibetan, symbols, sharada, myanmar, cham, chakma, tai-tham, kayah-li, thaana, balinese, marchen, khmer, modi, batak, limbu, new-tai-lue, hebrew, manichaean, caucasian-albanian, tifinagh, elbasan, tirhuta, nko, sinhala, gurmukhi, gunjala-gondi, tai-le, warang-citi, zanabazar-square, telugu, kannada, dogra, psalter-pahlavi, tagalog, gujarati, newa, duployan, soyombo, lepcha, old-permic, phags-pa, meetei-mayek, miao, osage, music, pahawh-hmong, siddham, buginese, syloti-nagri, malayalam, thai, javanese, devanagari, yi, mende-kikakui, mahajani, brahmi, syriac, bassa-vah, takri, bhaiksuki, mandaic, wancho, oriya, armenian, sogdian, bengali, khudawadi, adlam, tai-viet, ahom, hanifi-rohingya, masaram-gondi, khojki, canadian-aboriginal, hanunoo, math, mongolian, kharoshthi, rejang, tamil, grantha, buhid, kaithi</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
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
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 2 | 5 | 118 | 6 | 118 | 0 | 
| 0% | 0% | 1% | 2% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
