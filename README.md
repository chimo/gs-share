# Note

I'm done with this. If someone wants to maintain it send me a note and I'll transfer the repo. Or just fork it, or whatever.

# 'Share' widget for GNU social

This adds links/buttons to your page so that visitors can share it on
GNU social.

### HTML

Add the following in the `<head>` of your page (if necessary, change the path
to point to the stylesheet).

    <link rel="stylesheet" href="styles.css">

Add the following where you want the links/buttons to appear.

    <div class="gs-share">
      <button data-url="URL-from-data" data-title="TITLE-from-data" class="js-gs-share gs-share--icon">Share on GNU social</button>
    </div>

The "data-title" and "data-url" attributes are optional. If they are not set,
the "title" will be the title of the current page and the "url" will be the
URL of the current page.

Add the following at the bottom of your page (if necessary, change the path
to point to the JS file).

    <script src="gs-share.js"></script>

## Demo

https://chromic.org/gs-share/

## Server-side fallback

For an example of a server-side fallback, see the "php" branch in this repo.

