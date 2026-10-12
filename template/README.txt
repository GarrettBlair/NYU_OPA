POSTDOC WEBSITE TEMPLATE
========================

A one-page personal website with sections: About Me, Recent News,
Publications, Presentations, Resources. No coding experience needed.

QUICK START
-----------
1. Double-click index.html to preview the site in your web browser.
2. Open index.html in a plain text editor (Notepad, TextEdit in plain-text
   mode, or VS Code - NOT Microsoft Word).
3. Search (Ctrl+F) for ">>> EDIT <<<". Each one marks text you should change.
4. Replace the placeholder text, save, and refresh the browser to see it.

WHAT TO CHANGE
--------------
Text       Type over the placeholder text. Leave anything inside < > alone.
Links      Change the web address inside href="...".
Photos     Replace the files in the "images" folder with your own, keeping the
           same file names (or update the name in index.html):
             avatar.jpg   small photo in the left menu (square, ~400x400)
             profile.jpg  photo next to your intro (~400x500)
             banner.jpg   wide banner on each section (~2000x600)
             thumbs/      small images for news items (~400x300)
             poster.jpg   large image opened from Presentations
             favicon.png  small icon in the browser tab
CV         Put your CV in the "docs" folder and name it CV.pdf
           (or change the name in index.html).
Colors     Open assets/css/theme.css - the colors are listed at the top.
           Change the #xxxxxx codes.

ADD / REMOVE THINGS
-------------------
- News item / publication / presentation: copy an existing block (the comments
  show exactly where it starts and ends), paste it, and edit it.
- Remove a section: delete its <section ...> ... </section> block AND its
  line in the menu (the <nav> list near the top).
- Remove a social icon: delete its <li> ... </li> line.
- Available icons: https://fontawesome.com/v5/search?m=free (use the
  "fa-name" class, with "brands" or "solid" as in the existing icons).

PUBLISHING
----------
Upload the whole folder to any web host. Free options: GitHub Pages,
Netlify Drop (drag-and-drop the folder), or your university's web hosting.
Your main file must be named index.html.

CREDITS
-------
Design: "Read Only" by HTML5 UP (html5up.net), CCA 3.0 license. See LICENSE.txt.
