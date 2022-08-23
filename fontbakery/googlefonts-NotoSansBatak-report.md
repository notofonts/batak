## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[10] NotoSansBatak-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 319, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-batak, a_uSign-batak, aSima-batak, ha-batak, ha_uSign-batak, haSima-batak, haMandai-batak, haMandai_uSign-batak, ba-batak, ba_uSign-batak and 71 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- ogonekcomb

	- commaturnedabovecomb

	- acutecomb

	- tildecomb

	- ringcomb

	- hungarumlautcomb

	- cedillacomb

	- macroncomb

	- dotaccentcomb

	- brevecomb 

	- And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/batak.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansBatak/googlefonts/ttf/NotoSansBatak-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/batak.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ᯆᯨ᯿ᯣᯮ᯿</span> (Issue #2)</li>


<pre>Expected: karoBa-batak=0+1090|eSignPak-batak=0@-113,0+0|binduPangolat-batak=2+495|mba-batak=3+1090|uSign-batak=3@-441,-128+0|binduPangolat-batak=5+495</pre>



<pre>Got     : karoBa-batak=0+1090|eSignPak-batak=0+0|binduPangolat-batak=2+495|mba-batak=3+1090|uSign-batak=3+0|binduPangolat-batak=5+495</pre>



<pre>                                             +++++++                                                            ++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3170 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M495.0,-10.0Q405.0,-10.0 327.5,4.5Q250.0,19.0 191.5,48.5Q133.0,78.0 100.5,124.0Q68.0,170.0 68.0,234.0Q68.0,298.0 104.0,344.0Q140.0,390.0 200.5,420.0Q261.0,450.0 337.5,464.5Q414.0,479.0 495.0,479.0Q576.0,479.0 652.5,464.5Q729.0,450.0 789.5,420.0Q850.0,390.0 886.0,344.0Q922.0,298.0 922.0,234.0Q922.0,170.0 889.5,124.0Q857.0,78.0 798.5,48.5Q740.0,19.0 662.5,4.5Q585.0,-10.0 495.0,-10.0ZM495.0,78.0Q555.0,78.0 614.0,86.0Q673.0,94.0 721.0,112.5Q769.0,131.0 798.0,161.0Q827.0,191.0 827.0,234.0Q827.0,278.0 798.0,308.0Q769.0,338.0 721.0,356.0Q673.0,374.0 614.0,382.5Q555.0,391.0 495.0,391.0Q435.0,391.0 376.0,382.5Q317.0,374.0 269.0,356.0Q221.0,338.0 192.0,308.0Q163.0,278.0 163.0,234.0Q163.0,191.0 192.0,161.0Q221.0,131.0 269.0,112.5Q317.0,94.0 376.0,86.0Q435.0,78.0 495.0,78.0Z"  transform="translate(0, 793)"/>
<path d="M-183.0,552.0Q-199.0,552.0 -209.5,562.0Q-220.0,572.0 -220.0,590.0Q-220.0,600.0 -212.0,608.0Q-204.0,616.0 -196.0,625.0Q-186.0,636.0 -167.5,651.5Q-149.0,667.0 -127.0,682.5Q-105.0,698.0 -86.0,708.0Q-107.0,732.0 -136.0,751.0Q-165.0,770.0 -196.0,789.0Q-220.0,803.0 -220.0,823.0Q-220.0,841.0 -209.5,851.0Q-199.0,861.0 -183.0,861.0Q-173.0,861.0 -151.0,850.0Q-129.0,839.0 -103.5,821.0Q-78.0,803.0 -54.5,782.5Q-31.0,762.0 -15.5,742.0Q0.0,722.0 0.0,708.0Q0.0,697.0 -6.5,686.0Q-13.0,675.0 -23.0,668.0Q-56.0,646.0 -90.0,620.0Q-124.0,594.0 -156.0,563.0Q-169.0,552.0 -183.0,552.0Z"  transform="translate(1090, 793)"/>
<path d="M-55.0,-275.0Q-86.0,-275.0 -98.0,-259.5Q-110.0,-244.0 -110.0,-230.0Q-110.0,-210.0 -97.0,-201.0Q-84.0,-192.0 -73.0,-190.0Q-61.0,-188.0 -35.5,-183.0Q-10.0,-178.0 17.0,-169.0Q71.0,-151.0 121.0,-118.5Q171.0,-86.0 211.0,-37.5Q251.0,11.0 274.0,75.5Q297.0,140.0 297.0,223.0Q297.0,297.0 273.5,361.0Q250.0,425.0 210.5,475.5Q171.0,526.0 121.0,561.5Q71.0,597.0 17.0,615.0Q4.0,620.0 -17.0,625.0Q-38.0,630.0 -67.0,635.0Q-83.0,638.0 -96.5,648.0Q-110.0,658.0 -110.0,677.0Q-110.0,692.0 -99.0,706.5Q-88.0,721.0 -60.0,721.0Q-42.0,721.0 -13.5,714.5Q15.0,708.0 40.0,700.0Q109.0,676.0 171.0,635.0Q233.0,594.0 281.5,535.0Q330.0,476.0 357.5,398.5Q385.0,321.0 385.0,223.0Q385.0,117.0 354.0,37.0Q323.0,-43.0 271.5,-100.5Q220.0,-158.0 157.5,-195.5Q95.0,-233.0 33.0,-256.0Q14.0,-263.0 -10.5,-269.0Q-35.0,-275.0 -55.0,-275.0Z"  transform="translate(1090, 793)"/>
<path d="M495.0,-10.0Q405.0,-10.0 327.0,4.5Q249.0,19.0 191.0,48.5Q133.0,78.0 100.5,124.0Q68.0,170.0 68.0,234.0Q68.0,300.0 104.0,346.5Q140.0,393.0 200.5,422.0Q261.0,451.0 337.5,465.0Q414.0,479.0 495.0,479.0Q579.0,479.0 655.5,465.0Q732.0,451.0 792.5,422.0Q853.0,393.0 887.5,346.5Q922.0,300.0 922.0,234.0Q922.0,169.0 888.0,122.5Q854.0,76.0 794.5,47.0Q735.0,18.0 658.0,4.0Q581.0,-10.0 495.0,-10.0ZM495.0,78.0Q558.0,78.0 617.5,86.5Q677.0,95.0 724.5,113.5Q772.0,132.0 799.5,161.5Q827.0,191.0 827.0,234.0Q827.0,278.0 798.0,308.0Q769.0,338.0 721.0,356.5Q673.0,375.0 614.0,383.0Q555.0,391.0 495.0,391.0Q435.0,391.0 376.0,383.0Q317.0,375.0 269.0,357.0Q221.0,339.0 192.0,309.0Q163.0,279.0 163.0,234.0Q163.0,190.0 191.5,160.0Q220.0,130.0 268.0,112.0Q316.0,94.0 375.0,86.0Q434.0,78.0 495.0,78.0ZM495.0,174.0Q467.0,174.0 447.0,194.0Q427.0,214.0 427.0,242.0Q427.0,270.0 447.0,290.0Q467.0,310.0 495.0,310.0Q524.0,310.0 543.5,290.0Q563.0,270.0 563.0,242.0Q563.0,214.0 543.5,194.0Q524.0,174.0 495.0,174.0Z"  transform="translate(1585, 793)"/>
<path d="M55.0,-291.0Q39.0,-291.0 27.0,-280.0Q15.0,-269.0 15.0,-250.0Q15.0,-241.0 18.5,-231.0Q22.0,-221.0 34.0,-213.0Q63.0,-193.0 103.5,-163.5Q144.0,-134.0 173.0,-100.0Q143.0,-64.0 104.0,-33.5Q65.0,-3.0 34.0,17.0Q23.0,25.0 19.0,35.0Q15.0,45.0 15.0,54.0Q15.0,73.0 27.0,83.5Q39.0,94.0 55.0,94.0Q67.0,94.0 92.0,78.5Q117.0,63.0 147.5,39.0Q178.0,15.0 206.0,-12.0Q234.0,-39.0 252.0,-62.0Q270.0,-85.0 270.0,-99.0Q270.0,-112.0 252.0,-135.5Q234.0,-159.0 206.0,-185.5Q178.0,-212.0 147.5,-236.0Q117.0,-260.0 92.0,-275.5Q67.0,-291.0 55.0,-291.0Z"  transform="translate(2675, 793)"/>
<path d="M-55.0,-275.0Q-86.0,-275.0 -98.0,-259.5Q-110.0,-244.0 -110.0,-230.0Q-110.0,-210.0 -97.0,-201.0Q-84.0,-192.0 -73.0,-190.0Q-61.0,-188.0 -35.5,-183.0Q-10.0,-178.0 17.0,-169.0Q71.0,-151.0 121.0,-118.5Q171.0,-86.0 211.0,-37.5Q251.0,11.0 274.0,75.5Q297.0,140.0 297.0,223.0Q297.0,297.0 273.5,361.0Q250.0,425.0 210.5,475.5Q171.0,526.0 121.0,561.5Q71.0,597.0 17.0,615.0Q4.0,620.0 -17.0,625.0Q-38.0,630.0 -67.0,635.0Q-83.0,638.0 -96.5,648.0Q-110.0,658.0 -110.0,677.0Q-110.0,692.0 -99.0,706.5Q-88.0,721.0 -60.0,721.0Q-42.0,721.0 -13.5,714.5Q15.0,708.0 40.0,700.0Q109.0,676.0 171.0,635.0Q233.0,594.0 281.5,535.0Q330.0,476.0 357.5,398.5Q385.0,321.0 385.0,223.0Q385.0,117.0 354.0,37.0Q323.0,-43.0 271.5,-100.5Q220.0,-158.0 157.5,-195.5Q95.0,-233.0 33.0,-256.0Q14.0,-263.0 -10.5,-269.0Q-35.0,-275.0 -55.0,-275.0Z"  transform="translate(2675, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3170 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M495.0,-10.0Q405.0,-10.0 327.5,4.5Q250.0,19.0 191.5,48.5Q133.0,78.0 100.5,124.0Q68.0,170.0 68.0,234.0Q68.0,298.0 104.0,344.0Q140.0,390.0 200.5,420.0Q261.0,450.0 337.5,464.5Q414.0,479.0 495.0,479.0Q576.0,479.0 652.5,464.5Q729.0,450.0 789.5,420.0Q850.0,390.0 886.0,344.0Q922.0,298.0 922.0,234.0Q922.0,170.0 889.5,124.0Q857.0,78.0 798.5,48.5Q740.0,19.0 662.5,4.5Q585.0,-10.0 495.0,-10.0ZM495.0,78.0Q555.0,78.0 614.0,86.0Q673.0,94.0 721.0,112.5Q769.0,131.0 798.0,161.0Q827.0,191.0 827.0,234.0Q827.0,278.0 798.0,308.0Q769.0,338.0 721.0,356.0Q673.0,374.0 614.0,382.5Q555.0,391.0 495.0,391.0Q435.0,391.0 376.0,382.5Q317.0,374.0 269.0,356.0Q221.0,338.0 192.0,308.0Q163.0,278.0 163.0,234.0Q163.0,191.0 192.0,161.0Q221.0,131.0 269.0,112.5Q317.0,94.0 376.0,86.0Q435.0,78.0 495.0,78.0Z"  transform="translate(0, 793)"/>
<path d="M-183.0,552.0Q-199.0,552.0 -209.5,562.0Q-220.0,572.0 -220.0,590.0Q-220.0,600.0 -212.0,608.0Q-204.0,616.0 -196.0,625.0Q-186.0,636.0 -167.5,651.5Q-149.0,667.0 -127.0,682.5Q-105.0,698.0 -86.0,708.0Q-107.0,732.0 -136.0,751.0Q-165.0,770.0 -196.0,789.0Q-220.0,803.0 -220.0,823.0Q-220.0,841.0 -209.5,851.0Q-199.0,861.0 -183.0,861.0Q-173.0,861.0 -151.0,850.0Q-129.0,839.0 -103.5,821.0Q-78.0,803.0 -54.5,782.5Q-31.0,762.0 -15.5,742.0Q0.0,722.0 0.0,708.0Q0.0,697.0 -6.5,686.0Q-13.0,675.0 -23.0,668.0Q-56.0,646.0 -90.0,620.0Q-124.0,594.0 -156.0,563.0Q-169.0,552.0 -183.0,552.0Z"  transform="translate(977, 793)"/>
<path d="M-55.0,-275.0Q-86.0,-275.0 -98.0,-259.5Q-110.0,-244.0 -110.0,-230.0Q-110.0,-210.0 -97.0,-201.0Q-84.0,-192.0 -73.0,-190.0Q-61.0,-188.0 -35.5,-183.0Q-10.0,-178.0 17.0,-169.0Q71.0,-151.0 121.0,-118.5Q171.0,-86.0 211.0,-37.5Q251.0,11.0 274.0,75.5Q297.0,140.0 297.0,223.0Q297.0,297.0 273.5,361.0Q250.0,425.0 210.5,475.5Q171.0,526.0 121.0,561.5Q71.0,597.0 17.0,615.0Q4.0,620.0 -17.0,625.0Q-38.0,630.0 -67.0,635.0Q-83.0,638.0 -96.5,648.0Q-110.0,658.0 -110.0,677.0Q-110.0,692.0 -99.0,706.5Q-88.0,721.0 -60.0,721.0Q-42.0,721.0 -13.5,714.5Q15.0,708.0 40.0,700.0Q109.0,676.0 171.0,635.0Q233.0,594.0 281.5,535.0Q330.0,476.0 357.5,398.5Q385.0,321.0 385.0,223.0Q385.0,117.0 354.0,37.0Q323.0,-43.0 271.5,-100.5Q220.0,-158.0 157.5,-195.5Q95.0,-233.0 33.0,-256.0Q14.0,-263.0 -10.5,-269.0Q-35.0,-275.0 -55.0,-275.0Z"  transform="translate(1090, 793)"/>
<path d="M495.0,-10.0Q405.0,-10.0 327.0,4.5Q249.0,19.0 191.0,48.5Q133.0,78.0 100.5,124.0Q68.0,170.0 68.0,234.0Q68.0,300.0 104.0,346.5Q140.0,393.0 200.5,422.0Q261.0,451.0 337.5,465.0Q414.0,479.0 495.0,479.0Q579.0,479.0 655.5,465.0Q732.0,451.0 792.5,422.0Q853.0,393.0 887.5,346.5Q922.0,300.0 922.0,234.0Q922.0,169.0 888.0,122.5Q854.0,76.0 794.5,47.0Q735.0,18.0 658.0,4.0Q581.0,-10.0 495.0,-10.0ZM495.0,78.0Q558.0,78.0 617.5,86.5Q677.0,95.0 724.5,113.5Q772.0,132.0 799.5,161.5Q827.0,191.0 827.0,234.0Q827.0,278.0 798.0,308.0Q769.0,338.0 721.0,356.5Q673.0,375.0 614.0,383.0Q555.0,391.0 495.0,391.0Q435.0,391.0 376.0,383.0Q317.0,375.0 269.0,357.0Q221.0,339.0 192.0,309.0Q163.0,279.0 163.0,234.0Q163.0,190.0 191.5,160.0Q220.0,130.0 268.0,112.0Q316.0,94.0 375.0,86.0Q434.0,78.0 495.0,78.0ZM495.0,174.0Q467.0,174.0 447.0,194.0Q427.0,214.0 427.0,242.0Q427.0,270.0 447.0,290.0Q467.0,310.0 495.0,310.0Q524.0,310.0 543.5,290.0Q563.0,270.0 563.0,242.0Q563.0,214.0 543.5,194.0Q524.0,174.0 495.0,174.0Z"  transform="translate(1585, 793)"/>
<path d="M55.0,-291.0Q39.0,-291.0 27.0,-280.0Q15.0,-269.0 15.0,-250.0Q15.0,-241.0 18.5,-231.0Q22.0,-221.0 34.0,-213.0Q63.0,-193.0 103.5,-163.5Q144.0,-134.0 173.0,-100.0Q143.0,-64.0 104.0,-33.5Q65.0,-3.0 34.0,17.0Q23.0,25.0 19.0,35.0Q15.0,45.0 15.0,54.0Q15.0,73.0 27.0,83.5Q39.0,94.0 55.0,94.0Q67.0,94.0 92.0,78.5Q117.0,63.0 147.5,39.0Q178.0,15.0 206.0,-12.0Q234.0,-39.0 252.0,-62.0Q270.0,-85.0 270.0,-99.0Q270.0,-112.0 252.0,-135.5Q234.0,-159.0 206.0,-185.5Q178.0,-212.0 147.5,-236.0Q117.0,-260.0 92.0,-275.5Q67.0,-291.0 55.0,-291.0Z"  transform="translate(2234, 665)"/>
<path d="M-55.0,-275.0Q-86.0,-275.0 -98.0,-259.5Q-110.0,-244.0 -110.0,-230.0Q-110.0,-210.0 -97.0,-201.0Q-84.0,-192.0 -73.0,-190.0Q-61.0,-188.0 -35.5,-183.0Q-10.0,-178.0 17.0,-169.0Q71.0,-151.0 121.0,-118.5Q171.0,-86.0 211.0,-37.5Q251.0,11.0 274.0,75.5Q297.0,140.0 297.0,223.0Q297.0,297.0 273.5,361.0Q250.0,425.0 210.5,475.5Q171.0,526.0 121.0,561.5Q71.0,597.0 17.0,615.0Q4.0,620.0 -17.0,625.0Q-38.0,630.0 -67.0,635.0Q-83.0,638.0 -96.5,648.0Q-110.0,658.0 -110.0,677.0Q-110.0,692.0 -99.0,706.5Q-88.0,721.0 -60.0,721.0Q-42.0,721.0 -13.5,714.5Q15.0,708.0 40.0,700.0Q109.0,676.0 171.0,635.0Q233.0,594.0 281.5,535.0Q330.0,476.0 357.5,398.5Q385.0,321.0 385.0,223.0Q385.0,117.0 354.0,37.0Q323.0,-43.0 271.5,-100.5Q220.0,-158.0 157.5,-195.5Q95.0,-233.0 33.0,-256.0Q14.0,-263.0 -10.5,-269.0Q-35.0,-275.0 -55.0,-275.0Z"  transform="translate(2675, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- waSima_uSign-batak
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 eSignPak-batak (U+1BE8), eeSign-batak (U+1BE9), hSign-batak (U+1BF1), ngSign-batak (U+1BF0), oSignKaro-batak (U+1BED), tompi-batak (U+1BE6) and uSignSima-batak (U+1BEF) [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 4 | 5 | 113 | 7 | 105 | 0 |
| 0% | 2% | 2% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
