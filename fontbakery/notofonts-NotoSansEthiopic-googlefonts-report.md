## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[7] NotoSansEthiopic[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni030E

- uni0326

- uni0327

- uni0328

- uni135D

- uni135E

- uni135F
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 322:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansEthiopic/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



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
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tai-le, tifinagh, math, coptic, syriac, old-permic, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, hebrew, yi, kharoshthi, armenian, sora-sompeng, cham, sundanese, coptic, arabic, kayah-li, kaithi</li>
<li>U+22EE VERTICAL ELLIPSIS: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: syloti-nagri, psalter-pahlavi, kannada, adlam, sharada, gurmukhi, zanabazar-square, buginese, meetei-mayek, hebrew, oriya, bhaiksuki, warang-citi, khmer, kaithi, rejang, kharoshthi, modi, syriac, sinhala, mongolian, limbu, sogdian, armenian, music, sundanese, tifinagh, chakma, dogra, duployan, brahmi, symbols, elbasan, tai-le, marchen, math, cham, thaana, kayah-li, lao, manichaean, miao, tibetan, osage, masaram-gondi, mende-kikakui, bassa-vah, hanunoo, mahajani, batak, buhid, myanmar, nko, tai-viet, khudawadi, telugu, phags-pa, tamil, devanagari, mandaic, soyombo, javanese, ahom, new-tai-lue, wancho, gujarati, yi, pahawh-hmong, balinese, tagalog, newa, old-permic, caucasian-albanian, bengali, khojki, thai, takri, tai-tham, siddham, tirhuta, lepcha, canadian-aboriginal, malayalam, tagbanwa, gunjala-gondi, hanifi-rohingya, coptic, saurashtra, grantha</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̎ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̎ į̧̀ į̧́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mfumte (Latn, 79,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Zapotec (Latn, 490,000 speakers), Ejagham (Latn, 120,000 speakers), Sar (Latn, 500,000 speakers), Makaa (Latn, 221,000 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Vute (Latn, 21,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Ngbaka (Latn, 1,020,000 speakers).</p>
 [code: soft-dotted]



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
| 0 | 0 | 2 | 5 | 95 | 7 | 142 | 0 | 
| 0% | 0% | 1% | 2% | 38% | 3% | 57% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
