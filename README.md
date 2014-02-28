# HTML, CSS, and Accessibilty
  
    * Humans are responsible for using these in accessible ways.
    * Easy to make accessible web pages; more work to make them inaccessible.
    * Always ask: What do these design/development decisions do for
    accessibility?

# What is HTML?

    * A markup language to add structure and meaning to documents.
    * Helps a browser read/interpret a document
    * Helps other tech understand/interpret your document.
        * #1 user of your site has no arms, legs, eyes, ears, etc: Search Engines

```html
<!-- A HTML comment -->

<tagname attribute="value">Tag content</tagname>

<tagname attribute="value"/>

```

# What is CSS?
    
    * A style language to government presentation of specific parts of a
      document.
    * Helps a browser display a document
    * Separation helps you establish rules to use across documents.
    * Selectors help you pick specific parts of a document for styles

```css

/* A CSS Rule */

selector {
    property: value;
}

```

* How do you use them together?
    * Separation of powers: HTML for structure, CSS for presentation

* Accessibility and HTML

    * Simple page structure
        * Semantics
        * Aria roles
    
    * Multimedia
        * Images
        * Video
        * Audio

    * Navigation
        * Nav
        * role="navigation"

    * Forms
        * Good markup
            * LABELS!!!!
            * textarea
            * input
                * text
                * email
                * telephone
                * search
            * attributes
                * placeholder
                * required


* Accessibility and CSS

    * Link styling

    * Hiding content
        * display:none;
        * visibility: hidden;
        * better CSS to hide content visually but keep accessible.

    * Colors and Contrast

    * Typography
        * Web fonts instead of images of text
        * Google web fonts
    * Layouts for various devices and screen resolutions = Media Queries

    * Separate CSS = possible to provide alternative style sheets

# Advanced Topics and Tools

* Platform/browser sniffing, capability sniffing is in!
    * [Modernizr](http://modernizr.com) helps you test browser support
      for specific features.

* CSS resets and normalization
    * Eric Meyer's CSS Reset
    * Normalize
    * Good ol' * {margin:0; padding:0;}

* CSS Preprocessors
    * [Sass](http://sass-lang.com/)
    * [Compass](http://compass-style.org/)
    * [Susy](http://susy.oddbird.net/)

