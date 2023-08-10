# Theme switcher 

The Theme Switcher Button is based on a React component viewed on *https://developer.mozilla.org/*.

The JavaScript code is responsible for adding a click event listener to the document, which handles the toggling of the theme menu.

It will dinamically generate the theme options based on the "**items**" array and toggle the theme dropdown menu, adding the "**open**" class on the parent element (the "**&lt;li>**" element with the "**theme**" class).

And a flip animation made with CSS3 is showed for the "caret" in the button.

The "**makeButton()**" function is also called to dynamically construct the theme menu inside an unordered list (the "**&lt;ul>**" element with the "**subnav**" class) and append it to the "**li.theme.open**" parent element.

Therefore, the "**ul.subnav**" element only exists when "**button.action**" is clicked and the theme menu is unfolded.

The icon on the Theme Switcher Button is Dim by default. It changes according to the selected color scheme, applied by changing a class in the <html> tag. All icons are loaded as SVG symbols with the &lt;use&gt; element from inside the HTML.

No libraries! **NO** dependencies at all.

---
Thanks for watching! 👏
