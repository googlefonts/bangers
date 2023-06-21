## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[1] Family checks</b></summary><div><details><summary>ℹ <b>INFO:</b> Check axis ordering on the STAT table.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/axis_order">com.google.fonts/check/STAT/axis_order</a>)</summary><div>


* ℹ **INFO** From a total of 1 font files, 1 of them (100.00%) lack a STAT table.

	And these are the most common STAT axis orderings:
	 [code: summary]
</div></details><br></div></details><details><summary><b>[13] Bangers-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NeWT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* Hbar
	* Lcaron
	* dcroat
	* franc
	* hbar
	* lcaron
	* ohorn
	* peseta
	* uhorn and 18 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- caronalt

	- ijacute 

	- uni0326.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 4	Expected: 5

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: registered	Contours detected: 5	Expected: 3 or 4

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3 

	- 132 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Oslash (U+00D8): L<<606.0,704.0>--<623.0,724.0>>/L<<623.0,724.0>--<550.0,630.0>> = 2.531775301616936

	* Oslashacute (U+01FE): L<<606.0,704.0>--<623.0,724.0>>/L<<623.0,724.0>--<550.0,630.0>> = 2.531775301616936

	* oslash (U+00F8): L<<606.0,704.0>--<623.0,724.0>>/L<<623.0,724.0>--<550.0,630.0>> = 2.531775301616936

	* oslashacute (U+01FF): L<<606.0,704.0>--<623.0,724.0>>/L<<623.0,724.0>--<550.0,630.0>> = 2.531775301616936

	* percent (U+0025): B<<468.0,161.0>-<468.0,237.0>-<506.0,315.0>>/B<<506.0,315.0>-<459.0,246.0>-<417.5,184.0>> = 8.28670893666324

	* percent (U+0025): B<<682.0,579.0>-<627.0,497.0>-<568.0,409.0>>/B<<568.0,409.0>-<599.0,441.0>-<634.5,461.0>> = 10.250563415833561

	* perthousand (U+2030): B<<517.0,161.0>-<517.0,237.0>-<555.0,315.0>>/B<<555.0,315.0>-<508.0,246.0>-<466.5,184.0>> = 8.28670893666324 

	* perthousand (U+2030): B<<731.0,579.0>-<676.0,497.0>-<617.0,409.0>>/B<<617.0,409.0>-<648.0,441.0>-<683.5,461.0>> = 10.250563415833561 [code: found-jaggy-segments]
</div></details><details><summary>ℹ <b>INFO:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* ℹ **INFO** Hinting filesize impact:

 |               | Bangers-Regular.ttf          |
 |:------------- | ---------------:|
 | Dehinted Size | 65.9kb |
 | Hinted Size   | 90.2kb   |
 | Increase      | 24.3kb      |
 | Change        | 36.9 %  |
 [code: size-impact]
</div></details><details><summary>ℹ <b>INFO:</b> EPAR table present in font? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/epar">com.google.fonts/check/epar</a>)</summary><div>


* ℹ **INFO** EPAR table not present in font. To learn more see https://github.com/googlefonts/fontbakery/issues/818 [code: lacks-EPAR]
</div></details><details><summary>ℹ <b>INFO:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* ℹ **INFO** These are the ppm ranges declared on the gasp table:

PPM <= 65535:
	flag = 0x0F
	- Use grid-fitting
	- Use grayscale rendering
	- Use gridfitting with ClearType symmetric smoothing
	- Use smoothing along multiple axes with ClearType®
 [code: ranges]
</div></details><details><summary>ℹ <b>INFO:</b> Check for font-v versioning. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontv">com.google.fonts/check/fontv</a>)</summary><div>


* ℹ **INFO** Version string is: "Version 2.100; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.31]"
The version string must ideally include a git commit hash and either a "dev" or a "release" suffix such as in the example below:
"Version 1.3; git-0d08353-release" [code: bad-format]
</div></details><details><summary>ℹ <b>INFO:</b> Font contains all required tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/required_tables">com.google.fonts/check/required_tables</a>)</summary><div>


* ℹ **INFO** This font contains the following optional tables:

	- cvt 

	- fpgm

	- loca

	- prep

	- GPOS

	- GSUB 

	- gasp [code: optional-tables]
</div></details><details><summary>ℹ <b>INFO:</b> List all superfamily filepaths (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/superfamily/list">com.google.fonts/check/superfamily/list</a>)</summary><div>


* ℹ **INFO** . [code: family-path]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 7 | 120 | 7 | 112 | 0 |
| 0% | 0% | 3% | 49% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **PASS**
* **DEBUG**
