Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git


Changes to HTML files:
- Moved all non-inline css to a separate file
- Imported fonts from google
- Made the links in the table of contents refer to sections of the document locally, rather than redirecting to an internet address (to prevent the ToC from sending users to the original project gutenburg chapter online)
- Removed the inline styling for the Table of Contents and replaced it with a class so I could center the ToC on the page.
- Added an svg tag to make cool ink effect a la https://andyjakubowski.com/tutorial/ink-bleed-effect-with-svg-filters

CSS Added:
- Old paper effect
    - 2 overlaid background images that repeat vertically on soft-light blending mode
    - linear gradient, radial gradient on multiply blend mode
    - solid color in the center
- Text
    - Fancy first letter in (ideally) parchment font, 500%
    - Separate fonts for headers, paragraphs, and the gutenbutg boilerplate stuff
    - More redish font color
    - two font shadows, one for an ink smudge effect, another for the effect of aged discolored ink
    - combination of blur and threshold to get lo-fi print effect to the font
    - center paragraphs in divs while keeping text left aligned in paragraphs
- Images
  - Rounded corners
- Misc.
  - Random details polished where they would otherwise be off to leave alone
    - e.g. Footnotes getting the first letter effect, among other minor "bugs", for lack of better word.

License/Copyright
=================

Small bits of code in svg tags in html files are from https://andyjakubowski.com/tutorial/ink-bleed-effect-with-svg-filters
Background image textures on the gutenburg html files from/by https://www.photoshopsupply.com. Their license is in the folder with images in question.
gutenburg ebooks from https://www.gutenburg.org, licenses in the html files.
Wood texture in homepage/good.html is from https://architextures.org/textures/729 Free for education and personal use, full details: https://architextures.org/terms
Lens flare in bad_style.css is by Shimin Zhang from https://css-tricks.com/add-a-css-lens-flare-to-photos-for-a-bright-touch/

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license by Sean Meyers (C) 2023. Anything originally by gutenburg or other mentioned parties here is by them.

Photographs of people are (C) 2023 CC BY-NC-ND 4.0 Sean Meyers.
gutenburg1.png, gutenburg2.png, gutenburg3.png are (C) 2023 CC BY-SA 4.0 Sean Meyers.
Any other images not mentioned here are (C) 2023 CC BY-NC-SA 4.0 Sean Meyers unless otherwise specified.


