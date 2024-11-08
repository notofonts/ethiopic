## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[7] NotoSerifEthiopic[wdth,wght].ttf</summary>
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
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 48 in glyph 'two' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifEthiopic/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, todhri, coptic, old-permic, hebrew, math, malayalam, canadian-aboriginal, syriac, tifinagh, duployan</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: lisu, sundanese, coptic, yi, kaithi, sora-sompeng, kharoshthi, arabic, hebrew, syloti-nagri, kayah-li, cham, armenian</li>
<li>U+22EE VERTICAL ELLIPSIS: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: tibetan, wancho, javanese, oriya, marchen, balinese, canadian-aboriginal, hanunoo, tagalog, coptic, siddham, yi, buginese, takri, thai, meetei-mayek, saurashtra, mongolian, osage, music, mende-kikakui, warang-citi, sogdian, adlam, math, tamil, cham, caucasian-albanian, tirhuta, zanabazar-square, mandaic, sinhala, modi, myanmar, old-permic, rejang, gunjala-gondi, kayah-li, dogra, pahawh-hmong, bhaiksuki, armenian, brahmi, gurmukhi, khudawadi, gujarati, tagbanwa, miao, batak, nko, sharada, telugu, ahom, hanifi-rohingya, kharoshthi, hebrew, tifinagh, kannada, khojki, elbasan, grantha, mahajani, malayalam, thaana, devanagari, bengali, phags-pa, lao, syriac, limbu, sundanese, masaram-gondi, tai-le, lepcha, new-tai-lue, psalter-pahlavi, soyombo, tai-viet, duployan, symbols, newa, kaithi, bassa-vah, syloti-nagri, tai-tham, buhid, khmer, chakma, manichaean</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Basaa (Latn, 332,940 speakers), Ebira (Latn, 2,200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Ngbaka (Latn, 1,020,000 speakers), Aghem (Latn, 38,843 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Ejagham (Latn, 120,000 speakers), Sar (Latn, 500,000 speakers), Mfumte (Latn, 79,000 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Bete-Bendi (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Heiltsuk (Latn, 300 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers).</p>
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
| 0 | 0 | 1 | 6 | 95 | 7 | 142 | 0 | 
| 0% | 0% | 0% | 2% | 38% | 3% | 57% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
