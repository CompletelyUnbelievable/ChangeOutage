<h1>Index:</h1>

1) <a href="#WhatMETA">What Is Wrong With My Theme</a>

2) <a href="#METALook">What Theme META Looks Like</a>

3) <a href="#ApplyingBA">placeholder</a>

4) <a href="#OtherPE">placeholder</a>

<a name="WhatMETA"><h2>What Is Wrong With My Theme?</h2></a>

If a theme does not show up on the theme menu after restarting discord and verifying the Better Discord install there are two causes and should be checked in this order:
1) The name of the theme file is incorrect (see the ThemeName folder for instructions)
2) The theme meta is broken

Theme meta is one of the major things that allows Better discord themes to be used and understood by itself defining names, descriptions, versions, etc. If a theme is without a meta, then it is not a theme, it is only a bunch of stylings pertaining to better discord and wont show up in the theme menu.

Some themes will have special instructions in their meta that mean something else, such as "\n" being an instruction to go to the next line. These instructions are carried over from different coding languages, and are completely valid in the theme meta without breaking the theme.
<a name="METALook"><h2>What Theme META Looks Like</h2></a>
Theme meta should look something like this:
//META{"name":"TheName","description":"TheDescription\nNewLine","author":"TheAuthor","version":"1.0"}*//

Sometimes it will have curly brackets/braces at the end of the meta, such as "{}".

According to Observer of Time (134312541869441035), "The meta lines confuse some editors so that's kind of a workaround." Meaning that they serve no actual use at all other than the theme developer's sanity.

According to Lost (392498266161414144), "[The] meta without brackets [seems to] make [the] editor ignore first rule-set," meaning that it will ignore the first selector as well as its declarations. Though I have never experienced what Lost claims with or without them, keep in mind that this might be true in some cases.

I'll be looking for more insight to it and add it here.
