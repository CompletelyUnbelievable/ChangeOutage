# Images Not Loading

<div>In order for images to load as backgrounds or otherwise in BetterDiscord the image link must contain:<br><br>

<ul>
	<li>HTTPS at the beginning of the link to the image. [<b>https</b>://i.imgur.com/iNq5zmg.png]</li>
	<li>Must end with an image file type: <b>.png</b>, <b>.jpg</b>, or something similar. <a>[https://i.imgur.com/iNq5zmg<b>.png</b>]</a></li>
	<li>The best way to ensure you have a good link it to open it in a browser and make sure that there is nothing else except for the image.</li>
	<li>Beyond this, then it is probably a typo in the CSS file. Generally caused by the average user. Redownload the theme from #theme-repo.</li>
</ul>
</div>
  
# Fixing an image display typo in CSS

<div>It is generally not advisable to most people to fix css formatting issues because you might as well learn HTML/CSS if you’re going to bother doing that. <b>Make sure the theme is being actively updated, if it isn't then don't bother trying this.</b> This is no cure all solution for fixing a typo because it can be rather nuanced, you can try this but it does make a number of assumptions:<br><br>

<ol>
	<li>Open the file with notepad/notepad++</li>
	<li>If you see "@import" one or more of these then you know that the bulk of the css is being brought in from elsewhere. If there is nothing below the imports then it means it is the fault of the developer or it has since ceased development, get a newer theme from #theme-repo in that case otherwise continue to the next step.</li>
	<li>Use the find/search function to find "https", this will allow you to search for all links in the file.</li>
	<li>Open each image link in your browser until you find the image you are trying to fix.</li>
	<li>If the image does not load or the image is deleted, find a new image otherwise get a different theme from #theme-repo. If you can't find the image link in the file then get a different theme from #theme-repo. Otherwise continue to the next step.</li>
	<li>Next is to identify what you are dealing with. If the line begins with "--" then it is a css variable, continue to the next step. If the line does not begin with and does not contain "--" then skip the next step.</li>
	<li>After the "--" is the css variable name and a colon, leave those alone and if you messed with them redownload the theme. The letters <i>url(</i> should encompass a link with or without quotation marks or apostrophes with <i>);</i> at the end of the line. If all of that is true then it should be working. Example: <a>[<i>--BackgroundPhoto: url(https://i.imgur.com/iNq5zmg.png);</i>]</a></li>
	<li>To be written...</li>
</ol>
</div>

# Oddly Sized Images

<div><a href="https://github.com/CompletelyUnbelievable/ThemeResource/blob/master/BetterDiscord101/ImageIssues/Images/bRMaNZT.gif">Sometimes Gifs are more than they seem, click here to see.</a><br><br>

User BloodPSTL (118854717370531846) was having issues getting an image to work on a modified version of the Dark Matter theme, this show why images might not be centered correctly with CSS. Feel free to use this simple <a href="https://github.com/CompletelyUnbelievable/ThemeResource/blob/master/BetterDiscord101/ImageIssues/OddlySizedImagesExample.html">example</a> file to make sure images are centered properly, just replace the imgur link with a direct link to the image you want to check.</div>
