## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | The locl feature did not affect Eng |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| dyo_Latn (Jola-Fonyi) | The locl feature did not affect Eng |
| ny_Latn (Nyanja) | The locl feature did not affect Eng |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |
| wo_Latn (Wolof) | The locl feature did not affect Eng |

 [code: failed-language-shaping]
</div></details><br></div></details><details><summary><b>[10] Asset-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, tai-le, math, malayalam, old-permic, coptic, syriac, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, yi
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2260 NOT EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* Aring
	* Atilde
	* Ccedilla
	* Itilde
	* Ntilde
	* Otilde
	* Rcaron
	* aring and ccedilla
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1684 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 1429:
greater, less

Width = 1714:
logicalnot

Width = 1468:
multiply

Width = 1200:
notequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lslash (U+0141): L<<2400.0,810.0>--<2400.0,800.0>> -> L<<2400.0,800.0>--<2399.0,788.0>>

	* N (U+004E): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* Nacute (U+0143): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* Ncaron (U+0147): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* Ntilde (U+00D1): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* Oslash (U+00D8): L<<1753.0,645.0>--<1753.0,675.0>> -> L<<1753.0,675.0>--<1752.0,703.0>>

	* P (U+0050): L<<1655.0,1170.0>--<1655.0,619.0>> -> L<<1655.0,619.0>--<1657.0,573.0>>

	* Z (U+005A): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* Zacute (U+0179): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* Zcaron (U+017D): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* Zdotaccent (U+017B): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* backslash (U+005C): L<<363.0,1178.0>--<515.0,868.0>> -> L<<515.0,868.0>--<630.0,638.0>>

	* backslash (U+005C): L<<377.0,775.0>--<217.0,1085.0>> -> L<<217.0,1085.0>--<54.0,1393.0>>

	* bar (U+007C): L<<360.0,525.0>--<362.0,290.0>> -> L<<362.0,290.0>--<365.0,-40.0>>

	* bar (U+007C): L<<362.0,772.0>--<360.0,525.0>> -> L<<360.0,525.0>--<362.0,290.0>>

	* bar (U+007C): L<<365.0,1145.0>--<362.0,772.0>> -> L<<362.0,772.0>--<360.0,525.0>>

	* dcroat (U+0111): L<<1475.0,1113.0>--<1293.0,1112.0>> -> L<<1293.0,1112.0>--<1141.0,1107.0>>

	* eight (U+0038): L<<2010.0,886.0>--<2078.0,877.0>> -> L<<2078.0,877.0>--<2144.0,867.0>>

	* four (U+0034): L<<1304.0,526.0>--<1305.0,536.0>> -> L<<1305.0,536.0>--<1305.0,1103.0>>

	* hbar (U+0127): L<<468.0,1065.0>--<310.0,1062.0>> -> L<<310.0,1062.0>--<158.0,1057.0>>

	* ij (U+0133): L<<3209.0,1075.0>--<3209.0,897.0>> -> L<<3209.0,897.0>--<3208.0,677.0>>

	* j (U+006A): L<<1336.0,1075.0>--<1336.0,897.0>> -> L<<1336.0,897.0>--<1335.0,677.0>>

	* jcircumflex (U+0135): L<<1323.0,1075.0>--<1323.0,897.0>> -> L<<1323.0,897.0>--<1322.0,677.0>>

	* jcircumflex (U+0135): L<<445.0,153.0>--<444.0,222.0>> -> L<<444.0,222.0>--<444.0,472.0>>

	* jcircumflex (U+0135): L<<445.0,56.0>--<445.0,153.0>> -> L<<445.0,153.0>--<444.0,222.0>>

	* numbersign (U+0023): L<<1037.0,386.0>--<939.0,387.0>> -> L<<939.0,387.0>--<880.0,387.0>>

	* numbersign (U+0023): L<<670.0,542.0>--<802.0,541.0>> -> L<<802.0,541.0>--<960.0,541.0>>

	* numbersign (U+0023): L<<802.0,541.0>--<960.0,541.0>> -> L<<960.0,541.0>--<1083.0,542.0>>

	* numbersign (U+0023): L<<816.0,1039.0>--<1096.0,1039.0>> -> L<<1096.0,1039.0>--<1230.0,1040.0>>

	* onehalf (U+00BD): L<<889.0,347.0>--<1156.0,605.0>> -> L<<1156.0,605.0>--<1336.0,783.0>>

	* onequarter (U+00BC): L<<879.0,347.0>--<1146.0,605.0>> -> L<<1146.0,605.0>--<1326.0,783.0>>

	* oslash (U+00F8): L<<1517.0,541.0>--<1334.0,437.0>> -> L<<1334.0,437.0>--<1129.0,318.0>>

	* percent (U+0025): L<<826.0,257.0>--<1093.0,515.0>> -> L<<1093.0,515.0>--<1273.0,693.0>>

	* perthousand (U+2030): L<<826.0,257.0>--<1093.0,515.0>> -> L<<1093.0,515.0>--<1273.0,693.0>>

	* slash (U+002F): L<<1059.0,1393.0>--<896.0,1085.0>> -> L<<896.0,1085.0>--<736.0,775.0>>

	* slash (U+002F): L<<482.0,638.0>--<597.0,868.0>> -> L<<597.0,868.0>--<749.0,1178.0>>

	* slash (U+002F): L<<896.0,1085.0>--<736.0,775.0>> -> L<<736.0,775.0>--<628.0,564.0>>

	* threequarters (U+00BE): L<<1048.0,347.0>--<1315.0,605.0>> -> L<<1315.0,605.0>--<1495.0,783.0>>

	* two (U+0032): L<<1655.0,394.0>--<1853.0,393.0>> -> L<<1853.0,393.0>--<2046.0,392.0>>

	* uni00B5 (U+00B5): L<<1047.0,-45.0>--<1026.0,-45.0>> -> L<<1026.0,-45.0>--<1004.0,-44.0>>

	* uni0145 (U+0145): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* uni0199 (U+0199): L<<538.0,704.0>--<536.0,864.0>> -> L<<536.0,864.0>--<523.0,1083.0>>

	* uni01F0 (U+01F0): L<<1336.0,1075.0>--<1336.0,897.0>> -> L<<1336.0,897.0>--<1335.0,677.0>>

	* uni01F8 (U+01F8): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* uni0237 (U+0237): L<<1336.0,1075.0>--<1336.0,897.0>> -> L<<1336.0,897.0>--<1335.0,677.0>>

	* uni1E44 (U+1E44): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* uni1E46 (U+1E46): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>>

	* uni1E56 (U+1E56): L<<1655.0,1170.0>--<1655.0,619.0>> -> L<<1655.0,619.0>--<1657.0,573.0>>

	* uni1E90 (U+1E90): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* uni1E92 (U+1E92): L<<2584.0,507.0>--<2631.0,507.0>> -> L<<2631.0,507.0>--<2677.0,508.0>>

	* uni2116 (U+2116): L<<1805.0,0.0>--<1439.0,315.0>> -> L<<1439.0,315.0>--<739.0,915.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<2382.0,690.0>-<2193.0,681.0>-<1993.0,679.0>>/B<<1993.0,679.0>-<2242.0,678.0>-<2460.5,669.0>> = 0.8030409927805215

	* R (U+0052): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* Racute (U+0154): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* Rcaron (U+0158): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* a (U+0061): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* aacute (U+00E1): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* abreve (U+0103): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* acircumflex (U+00E2): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* adieresis (U+00E4): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* ae (U+00E6): B<<1091.5,982.5>-<990.0,988.0>-<849.0,988.0>>/B<<849.0,988.0>-<943.0,986.0>-<1014.0,969.5>> = 1.2188752351313326

	* agrave (U+00E0): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* amacron (U+0101): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* aogonek (U+0105): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* aring (U+00E5): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* at (U+0040): B<<1505.5,928.5>-<1394.0,940.0>-<1217.0,940.0>>/B<<1217.0,940.0>-<1307.0,938.0>-<1374.5,922.5>> = 1.273030020056664

	* atilde (U+00E3): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* backslash (U+005C): B<<12.0,1644.0>-<29.0,1653.0>-<27.0,1652.0>>/B<<27.0,1652.0>-<46.0,1662.0>-<77.0,1674.0>> = 1.1934894239817435

	* braceleft (U+007B): B<<902.0,716.5>-<812.0,649.0>-<603.0,645.0>>/B<<603.0,645.0>-<749.0,643.0>-<834.0,611.0>> = 1.8812606869849084

	* braceright (U+007D): B<<510.0,574.0>-<600.0,641.0>-<809.0,645.0>>/B<<809.0,645.0>-<665.0,648.0>-<579.5,679.5>> = 2.2899255079749463

	* five (U+0035): B<<1078.5,153.0>-<955.0,93.0>-<701.0,89.0>>/B<<701.0,89.0>-<766.0,83.0>-<842.5,71.5>> = 6.176117118881824

	* onehalf (U+00BD): B<<2009.0,708.5>-<1959.0,704.0>-<1924.0,702.0>>/B<<1924.0,702.0>-<2070.0,694.0>-<2120.5,660.0>> = 6.406846291516141

	* ordfeminine (U+00AA): B<<726.5,1559.0>-<684.0,1558.0>-<648.0,1555.0>>/B<<648.0,1555.0>-<762.0,1555.0>-<832.0,1530.0>> = 4.763641690726143

	* question (U+003F): B<<743.5,1483.0>-<668.0,1478.0>-<621.0,1472.0>>/B<<621.0,1472.0>-<748.0,1467.0>-<832.5,1446.5>> = 9.529579923824253

	* questiondown (U+00BF): B<<1894.0,-337.5>-<1970.0,-332.0>-<2016.0,-327.0>>/B<<2016.0,-327.0>-<1888.0,-322.0>-<1804.0,-301.5>> = 8.440426965129493

	* r (U+0072): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* racute (U+0155): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* rcaron (U+0159): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* registered (U+00AE): B<<2338.0,609.0>-<2135.0,543.0>-<1805.0,541.0>>/L<<1805.0,541.0>--<2123.0,541.0>> = 0.3472428970853889

	* section (U+00A7): B<<2244.5,337.5>-<2082.0,270.0>-<1773.0,258.0>>/B<<1773.0,258.0>-<1894.0,244.0>-<2004.5,221.0>> = 8.823878222299347

	* sterling (U+00A3): B<<2337.5,1174.5>-<2427.0,1190.0>-<2547.0,1191.0>>/B<<2547.0,1191.0>-<2439.0,1205.0>-<2319.5,1216.5>> = 7.863496928576796

	* three (U+0033): B<<1142.5,163.0>-<1019.0,103.0>-<765.0,99.0>>/B<<765.0,99.0>-<808.0,96.0>-<889.0,90.0>> = 4.893134259959919

	* three (U+0033): B<<2723.0,742.5>-<2500.0,662.0>-<2030.0,636.0>>/B<<2030.0,636.0>-<2290.0,628.0>-<2490.5,609.5>> = 4.92871754266395

	* three (U+0033): B<<978.0,1204.0>-<929.0,1200.0>-<897.0,1199.0>>/B<<897.0,1199.0>-<1032.0,1194.0>-<1121.0,1173.5>> = 3.9110070049075616

	* threequarters (U+00BE): B<<1288.0,1364.5>-<1173.0,1341.0>-<1023.0,1331.0>>/B<<1023.0,1331.0>-<1192.0,1326.0>-<1326.0,1307.5>> = 5.508721902827444

	* threequarters (U+00BE): B<<615.5,1665.5>-<548.0,1659.0>-<516.0,1659.0>>/B<<516.0,1659.0>-<653.0,1651.0>-<701.0,1617.0>> = 3.341943857261075

	* threequarters (U+00BE): B<<641.0,1050.0>-<581.0,1019.0>-<452.0,1016.0>>/L<<452.0,1016.0>--<565.0,1008.0>> = 5.381801557140907

	* two (U+0032): B<<1081.0,1205.0>-<984.0,1198.0>-<913.0,1191.0>>/B<<913.0,1191.0>-<1048.0,1186.0>-<1137.5,1165.5>> = 7.751779154296687

	* uni00B2 (U+00B2): B<<594.0,1671.5>-<544.0,1667.0>-<509.0,1665.0>>/B<<509.0,1665.0>-<655.0,1657.0>-<705.5,1623.0>> = 6.406846291516141

	* uni00B3 (U+00B3): B<<1266.5,1353.0>-<1169.0,1338.0>-<1051.0,1331.0>>/B<<1051.0,1331.0>-<1230.0,1326.0>-<1371.5,1307.5>> = 4.994948257266031

	* uni00B3 (U+00B3): B<<611.0,1030.5>-<566.0,1022.0>-<499.0,1021.0>>/B<<499.0,1021.0>-<522.0,1020.0>-<548.0,1017.0>> = 3.3446503182658285

	* uni00B3 (U+00B3): B<<649.0,1663.0>-<598.0,1654.0>-<563.0,1654.0>>/B<<563.0,1654.0>-<634.0,1650.0>-<675.0,1638.5>> = 3.22452260651989

	* uni0156 (U+0156): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* uni0157 (U+0157): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* uni0181 (U+0181): B<<2382.0,690.0>-<2193.0,681.0>-<1993.0,679.0>>/B<<1993.0,679.0>-<2242.0,678.0>-<2460.5,669.0>> = 0.8030409927805215

	* uni01B4 (U+01B4): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* uni01CE (U+01CE): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* uni01E3 (U+01E3): B<<1091.5,982.5>-<990.0,988.0>-<849.0,988.0>>/B<<849.0,988.0>-<943.0,986.0>-<1014.0,969.5>> = 1.2188752351313326

	* uni0227 (U+0227): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* uni0233 (U+0233): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* uni1E02 (U+1E02): B<<2382.0,690.0>-<2193.0,681.0>-<1993.0,679.0>>/B<<1993.0,679.0>-<2242.0,678.0>-<2460.5,669.0>> = 0.8030409927805215

	* uni1E04 (U+1E04): B<<2382.0,690.0>-<2193.0,681.0>-<1993.0,679.0>>/B<<1993.0,679.0>-<2242.0,678.0>-<2460.5,669.0>> = 0.8030409927805215

	* uni1E58 (U+1E58): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* uni1E59 (U+1E59): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* uni1E5A (U+1E5A): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* uni1E5B (U+1E5B): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* uni1E5C (U+1E5C): B<<2317.5,629.0>-<2179.0,622.0>-<2029.0,621.0>>/L<<2029.0,621.0>--<2454.0,621.0>> = 0.3819662047286989

	* uni1E5D (U+1E5D): B<<1803.0,931.0>-<1885.0,954.0>-<1967.0,955.0>>/B<<1967.0,955.0>-<1786.0,955.0>-<1659.5,922.5>> = 0.6986943829831717

	* uni1E8F (U+1E8F): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* uni1EA1 (U+1EA1): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* uni1EAD (U+1EAD): B<<1078.0,996.0>-<932.0,996.0>-<804.0,988.0>>/B<<804.0,988.0>-<995.0,988.0>-<1111.0,935.5>> = 3.576334374997269

	* uni1EF9 (U+1EF9): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* uni20B4 (U+20B4): B<<1235.5,726.0>-<1333.0,731.0>-<1433.0,752.0>>/B<<1433.0,752.0>-<1340.0,752.0>-<1211.0,751.5>> = 11.859779120947966

	* uni20B4 (U+20B4): B<<1909.5,604.0>-<1764.0,597.0>-<1661.0,580.0>>/B<<1661.0,580.0>-<1783.0,580.0>-<1928.5,580.5>> = 9.372092708579077

	* y (U+0079): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* yacute (U+00FD): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* ycircumflex (U+0177): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* ydieresis (U+00FF): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167

	* ygrave (U+1EF3): B<<787.0,-361.0>-<686.0,-414.0>-<486.0,-414.0>>/B<<486.0,-414.0>-<531.0,-421.0>-<594.0,-428.0>> = 8.84181456019167 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Ccedilla (U+00C7): L<<1371.0,156.0>--<1372.0,-124.0>>

	* Eng (U+014A): L<<2801.0,922.0>--<2799.0,535.0>>

	* Scedilla (U+015E): L<<1362.0,156.0>--<1363.0,-124.0>>

	* at (U+0040): L<<2586.0,660.0>--<2585.0,454.0>>

	* bar (U+007C): L<<360.0,525.0>--<362.0,290.0>>

	* bar (U+007C): L<<362.0,772.0>--<360.0,525.0>>

	* bar (U+007C): L<<365.0,1145.0>--<362.0,772.0>>

	* ccedilla (U+00E7): L<<1185.0,156.0>--<1186.0,-124.0>>

	* cedilla (U+00B8): L<<792.0,156.0>--<793.0,-124.0>>

	* dcroat (U+0111): L<<1475.0,1113.0>--<1293.0,1112.0>>

	* eng (U+014B): L<<2691.0,612.0>--<2689.0,299.0>>

	* ij (U+0133): L<<3209.0,897.0>--<3208.0,677.0>>

	* j (U+006A): L<<1336.0,897.0>--<1335.0,677.0>>

	* jcircumflex (U+0135): L<<1323.0,897.0>--<1322.0,677.0>>

	* numbersign (U+0023): L<<1008.0,885.0>--<770.0,883.0>>

	* numbersign (U+0023): L<<1096.0,1039.0>--<1230.0,1040.0>>

	* numbersign (U+0023): L<<670.0,542.0>--<802.0,541.0>>

	* numbersign (U+0023): L<<960.0,541.0>--<1083.0,542.0>>

	* scedilla (U+015F): L<<1164.0,156.0>--<1165.0,-124.0>>

	* two (U+0032): L<<1655.0,394.0>--<1853.0,393.0>>

	* two (U+0032): L<<1853.0,393.0>--<2046.0,392.0>>

	* uni0162 (U+0162): L<<1377.0,156.0>--<1378.0,-124.0>>

	* uni0163 (U+0163): L<<967.0,156.0>--<968.0,-124.0>>

	* uni01F0 (U+01F0): L<<1336.0,897.0>--<1335.0,677.0>>

	* uni0237 (U+0237): L<<1336.0,897.0>--<1335.0,677.0>>

	* uni0327 (U+0327): L<<792.0,156.0>--<793.0,-124.0>>

	* uni1E29 (U+1E29): L<<1459.0,156.0>--<1460.0,-124.0>>

	* uni1E9E (U+1E9E): L<<1655.0,692.0>--<1656.0,565.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Kom (Latn, 360,685 speakers), Mango (Latn, 77,000 speakers), Dan (Latn, 1,099,244 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 10 | 122 | 7 | 115 | 0 |
| 0% | 0% | 4% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
