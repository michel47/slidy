  #SLIDY
  Good speech deserves time it takes
  Save time for speech
  Leave presentation to *Slide*

  #Focus on content
  Learn 5 markup rules
  to make content look great

  # #1
  Each paragraph is a slide

  # #2
  Headers start with #

  # #3
  Emphasize *words*
  surrounding them with **asterisks**

  # #4
  Indent code with 2 spaces
    /* Day of week: Sakamoto's algorithm */
    int dow(int y, int m, int d)
    {
      static int t[] = {0, 3, 2, 5, 0, 3, 5, 1, 4, 6, 2, 4};
      y -= m < 3;
      return (y + y/4 - y/100 + y/400 + t[m-1] + d) % 7;
    }

  # #5
  Lines starting with a dot
  disable markup such as
  headlines, code or blank lines

  ↵  = new slide
  .# = headline
  ** = emphasize
  ␣␣ = monospace
  .. = escape

  # Styling with CSS

  # Selectors
  ..slide
  ..slide h1
  ..slide strong
  ..slide pre
  .
  ..slide-N, where N is slide number

  # Example
  .
    .slide-10 h1 {
      color: #fff;
      text-shadow: 1px 1px 3px #453029;
    }
  .

  # CSS backgrounds
    .slide-12 {
      background: url("icon.png"),
                  url("bg.png");
      background-repeat: no-repeat, repeat;
      background-size: 40%, auto;
      background-position: bottom right;
    }


  # Print mode
  You can print slide thumbnails
  to practice your speech

  Slide for Android
  .
  .
  .

  # Links
  <a href=https://github.com/michel47/slidy>https://github.com/michel47/slidy</a>
  http://trikita.co/slide
  https://github.com/trikita/slide
  https://github.com/trikita/slide-html
  https://play.google.com/store/apps/details?id=trikita.slide
