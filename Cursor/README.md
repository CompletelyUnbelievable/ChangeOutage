# General cursor requirements

<div>Custom cursors are rarely requested, but often done incorrectly. They have a few requirements, <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_User_Interface/Using_URL_values_for_the_cursor_property">some documentation here</a>:<br><br>
<ul>
<li>The images recommended resolution is 36px by 36px. From what I've checked it can go up to 128px by 128px, which I assume is the limit.</li>
<li>The file formats must be one of these: PNG, GIF, JPG, BMP, and CUR. Mileage may vary for other formats.</li>
<li>If the cursor image is animated then it will only show the first frame. See <i>animated cursors with css animations</i> as a potential solution below.</li>
<li>When specifying a url for the cursor there must be a backup cursor set.</li>
</ul>
</div>

# To be continued
