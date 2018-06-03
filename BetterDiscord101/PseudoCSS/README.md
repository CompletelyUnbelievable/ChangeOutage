<h1>Index:</h1>

1) <a href="#WhatAreSE">What are pseudo elements</a>

2) <a href="#ApplyingPE">Applying pseudo elements</a>

<h2>What Are Pseudo Elements?</h2>

<a name="WhatAreSE">If there is an element that you cannot seem to find then it is probably due to pseudo elements. For instance, every single scrollbar in discord is a pseudo element. Some pseudo elements are are unique to the browser, discord is based off either the Google Chrome or Chromium browsers to it uses webkit scrollbars. Pseudo elements are not to be confused with pseudo classes which are a listed at the end of the page linked below in the applying pseudo elements section.</a>

<h2>Applying Pseudo Elements</h2>

<a name="ApplyingPE" href="https://www.w3schools.com/css/css_pseudo_elements.asp">Most information needed to apply this information will be pulled from here, at least in reguards on how to use this information.</a>

As for pseudo element within discord they are typically found at the bottom of user styles, for example here is a scrollbar element for the message wrapper:

<img src="https://raw.githubusercontent.com/CompletelyUnbelievable/ThemeResource/master/BetterDiscord101/PseudoCSS/Images/PseudoElementExample.png" height="200px">

As you could see there was a "::before" element, which I added, as part of the example. Lets see how it looks as an element:

<img src="https://raw.githubusercontent.com/CompletelyUnbelievable/ThemeResource/master/BetterDiscord101/PseudoCSS/Images/PseudoElementExample2.png" height="200px">

What is being pointed out here is that the scrollbar, though it is a pseudo element, does not add any element to the element tab. On the other hand the before pseudo element does get rendered in the element tab, even though it is a style that was added through CSS. This distinction is very important when it comes to pseudo elements, because you would otherwise be searching for an element that cannot be seen. That, or you weren't looking out for a "::before" or "::after" element that could have been what you were looking for.

When it comes to the before and after elements they always require content as a style even if that content does not contain anything. If it does not contain content then the before and after elements will not be rendered at all.

The before and after elements are extremely useful in limited situations, one such situation is when you are confined to only modifing the CSS or making a javascript plugin. Since javascript requires more from the developer, whatever can be done through CSS alone will be done through CSS. <a href="https://github.com/CompletelyUnbelievable/ThemeResource/blob/master/ChangeOutage/raw/Outage.css">Take a look at the CSS I wrote to change both the contents and insert an image to the discord outage area</a>, before and after elements are used to both remove and add both text and images all from the CSS itself.

<h3>To be continued</h3>
