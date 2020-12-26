## What does this PR do?

Added 2(+1) new homescreen/smallhero images and a new icon/favicon image in 6 differenc colors.
Files are under ./searx/static/logos. A set of copies (hero+icon) renamed to match the predecessors on each bundled theme's directory. No code was modified.

Files included: PNG exports at 400DPI + RGB/16 + alpha channel passed through a compressor to reduce their size, with second set exported in non-rasterized SVG, then a preview PNG and the original .afdesign (Serif Affinity Designer) file for future edits.

## Why is this change important?

It's probably not, it's a refresh of the current logo but now a little less lopsided while still keeping emphasis on the X (as "X marks the spot"; one of the things that I thught the huge X might mean) but using a cursor to (1) literally point to it and (2) be part of it. The colors where taken from the original logo to honor the authors in addition of a new set to pick from.

  The cursor was originally black but it made the X look like a badly-dimmensioned lowercase Y.

There's a very tiny shadow and/or use of alphas to make the objects pop while still blending. It's mostly noticeable only against a non-solid background.

## How to test this PR locally?

There's a preview file but there's really nothing to test as no code was modified except for ./README.rst to update the image. I assume that's fixed when pulling. The strawberry (somewhere between hot pink and red) favicon looks awesome on browser tabs and bookmarks, especially on Chrome where an animation circles it while loading.

## Author's checklist

I fell in love with the project but since I can't code to save my life, hopefully this is good enough, it'd be awesome to help even if the files aren't implemented and left somewhere as a second or third option.

I can always revise things if it's good but not there yet. :)

## Related issues

<!--
Closes #234
-->
