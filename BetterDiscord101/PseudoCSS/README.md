<h1>Index:</h1>

1) <a href="#WhatAreSE">What Are Pseudo Elements</a>

2) <a href="#ApplyingPE">Applying Pseudo Elements</a>

3) <a href="#ApplyingBA">Applying The 'before' And 'after' Pseudo Elements</a>

4) <a href="#OtherPE">The Other Pseudo Elements</a>

<a name="WhatAreSE"><h2>What Are Pseudo Elements?</h2></a>

They modify a specific part of an element rather than the state of an element. <a href="https://www.w3schools.com/css/css_pseudo_elements.asp" target="_blank">[?]</a>
  
If there is an element that you cannot seem to find then it is probably due to pseudo elements. For instance, the scrollbars in discord are pseudo elements. Some pseudo elements are unique to the browser, discord is based off either the Google-Chrome/Chromium browser(s) so it uses webkit scrollbars. <a href="https://www.w3schools.com/css/css_pseudo_elements.asp" target="_blank">Pseudo elements</a> are not to be confused with <a href="https://www.w3schools.com/css/css_pseudo_classes.asp" target="_blank">pseudo classes</a> which are not the subject of this material.

<a name="ApplyingPE"><h2>Applying Pseudo Elements</h2></a>

<a href="https://www.w3schools.com/css/css_pseudo_elements.asp">Most information needed to apply this information will be pulled from here, at least in regards on how to use this information.</a>

As for pseudo element within discord they are typically found at the bottom of user styles, for example here is a scrollbar element for the message wrapper:

<img src="https://raw.githubusercontent.com/CompletelyUnbelievable/ThemeResource/master/BetterDiscord101/PseudoCSS/Images/PseudoElementExample.png" height="200px">

As you could see there was a ‘::before’ element, which I added, as part of the example. Let’s see how it looks as an element:

<img src="https://raw.githubusercontent.com/CompletelyUnbelievable/ThemeResource/master/BetterDiscord101/PseudoCSS/Images/PseudoElementExample2.png" height="200px">

What is being pointed out here is that the scrollbar, though it is a pseudo element, does not add any element to the element tab. On the other hand the before pseudo element does get rendered in the element tab, even though it is a style that was added through CSS. This distinction is very important when it comes to pseudo elements, because you would otherwise be searching for an element that cannot be seen. That, or you weren't looking out for a ‘before’ or ‘after’ element that could have been what you were looking for.

<a name="ApplyingBA"><h2>Applying The 'before' And 'after' Pseudo Elements</h2></a>

When it comes to the before and after elements they always require content as a style even if that content does not contain anything. If it does not contain content then the before and after elements will not be rendered at all.

The before and after elements are extremely useful in limited situations, one such situation is when you are confined to only modifing the CSS or making a JavaScript plugin. Since JavaScript requires more from the developer, whatever can be done through CSS alone will be done through CSS. <a href="https://github.com/CompletelyUnbelievable/ThemeResource/blob/master/GuildsBar/ChangeOutage.theme.css">Take a look at the CSS I wrote to change both the contents and insert an image to the discord outage area</a>, before and after elements are used to both hide and add text and images all from the CSS itself. Here's an image of it in action:

![Puts the Better Discord Logo inside the outage symbol or area](https://raw.githubusercontent.com/CompletelyUnbelievable/ThemeResource/master/GuildsBar/Images/image.png)

As powerful as these pseudo elements may seem, there are things that they cannot do. To learn the limitations it would be best to try it for yourself, and ask around. People might even give you a way to get around it in a way that you'd never thought of.

<a name="OtherPE"><h2>The Other Pseudo Elements</h2></a>

The other pseudo elements listed are: 'first-letter', 'first-line', 'selection'. It is important to know that there is such ability to do things like they can, but they are not important in the grand scheme of things. There are very few times that these would need to be used, even less than the 'before' and 'after' pseudo elements.

There are other pseudo elements that are on a browser by browser basis that are useful but either fall to the same issue or due to obscurity. I would suggest looking up documentation for pseudo elements or unique styles on a browser by browser basis and see where they can be applied.

<h1>Appendix:</h1>

1) <a href="#WhatAreSE">What Are Pseudo Elements</a>

2) <a href="#ApplyingPE">Applying Pseudo Elements</a>

3) <a href="#ApplyingBA">Applying The 'before' And 'after' Pseudo Elements</a>

4) <a href="#OtherPE">The Other Pseudo Elements</a>

<h3>To be continued</h3>
