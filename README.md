# Xelasrecords' AO3 Site Skins
**IMPORTANT:** Complete information and preview on the skins' features are on my Tumblr [@xelasrecords](https://xelasrecords.tumblr.com/). Send me an ask there if you encounter any issues.

## Tutorial:
1. On my Github, go to the "css" folder, select the desired [skin-name].css, then copy the code.
2. On AO3, go to “Hi, [username]” > “My Dashboard” > “Skins” > “Create New Skin”.
3. Insert a unique title that nobody has used.
4. Paste the code into the CSS text area on AO3.
5. Press “Submit”.
6. Apply the skin on the “Skins” page.

## Notes:
1. Try creating the skin on desktop if errors occur after applying it on mobile.
2. If you prefer the default font size, you can revert it by deleting this block of code:
   ```
   #workskin {
    font-size: 130%;
   }
   ```
   You can also tweak the percentage to your liking instead.
3. If you want the links you’ve pressed before to stay grey, go to the code below and replace the hex code with the alternative colour written next to it:
   ```
   a.tag:visited, .blurb h4 a:visited {
    color: #xxxxxx !important; /*alternative #xxxxxx is placed like this*/
   }
   ```
Don’t delete anything unless you know what you’re doing. Copy and paste is enough.
