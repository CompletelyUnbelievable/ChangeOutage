If a theme does not show up on the theme menu after restarting discord and verifying the Better Discord install there are two causes and should be checked in this order:
1) The name of the theme file is incorrect (see the ThemeName folder for instructions)
2) The theme meta is broken

Theme meta is one of the major things that allows Better discord themes to be used and understood by itself defining names, descriptions, versions, etc. If a theme is without a meta, then it is not a theme, it is only a bunch of stylings pertaining to better discord and wont show up in the theme menu.

Some themes will have special instructions in their meta that mean something else, such as "\n" being an instruction to go to the next line. These instructions are carried over from different coding languages, and are completely valid in the theme meta without breaking the theme.

Theme meta should look something like this:
//META{"name":"TheName","description":"TheDescription","author":"TheAuthor","version":"1.0"}*//

Sometimes it will have curly brackets/braces at the end of the meta, such as "{}". According to Observer of Time (134312541869441035), "The meta lines confuse some editors so that's kind of a workaround." Meaning that they serve no actual use at all other than the theme developer's sanity. I'll be looking for more insight to it and add it here.
