##### How did you determine which rules should be placed in each new CSS file?

I added the really global styles to base.css (* and body).  I added nav, footer and aside styles to layout.css because they are still large level styles, but not as global as * and body.  I added all the individual styles for smaller elements to modules.css.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I refactored the footer section p into footer p, since section is just as general and there is only 1 section in footer and one p. I also refactored the margins for the footer section and article to modules, because they were more specific than the previous statement.
