CSS Introduction
  CSS stands for Cascading Style Sheets
  CSS describes how HTML elements are to be displayed on screen, paper, or in other media
  CSS saves a lot of work. It can control the layout of multiple web pages all at once
  External stylesheets are stored in CSS files
CSS Syntax
  A CSS rule-set consists of a selector and a declaration block:
  The selector points to the HTML element you want to style.

  The declaration block contains one or more declarations separated by semicolons.

  Each declaration includes a CSS property name and a value, separated by a colon.

  A CSS declaration always ends with a semicolon, and declaration blocks are surrounded by curly braces.

CSS Selectors
  CSS selectors are used to "find" (or select) HTML elements based on their element name, id, class, attribute, and more.

  The element Selector
    CSS selectors are used to "find" (or select) HTML elements based on their element name, id, class, attribute, and more.
  The id Selector(#)
    The id selector uses the id attribute of an HTML element to select a specific element.

    The id of an element should be unique within a page, so the id selector is used to select one unique element!

    To select an element with a specific id, write a hash (#) character, followed by the id of the element.
  The class Selector(.)
    The class selector selects elements with a specific class attribute.

    To select elements with a specific class, write a period (.) character, followed by the name of the class.

    HTML elements can also refer to more than one class.
  Grouping Selectors
    It will be better to group the selectors, to minimize the code.

    To group selectors, separate each selector with a comma.

CSS How To

  Three Ways to Insert CSS
    There are three ways of inserting a style sheet:
      External style sheet
      Internal style sheet
      Inline style
    External Style Sheet
      With an external style sheet, you can change the look of an entire website by changing just one file!

      Each page must include a reference to the external style sheet file inside the <link> element. The <link> element goes inside the <head> section
    Internal Style Sheet
      An internal style sheet may be used if one single page has a unique style.

      Internal styles are defined within the <style> element, inside the <head> section of an HTML page
    Inline Styles
      An inline style may be used to apply a unique style for a single element.

      To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property

Cascading Order
  What style will be used when there is more than one style specified for an HTML element?

  Generally speaking we can say that all the styles will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

    1.Inline style (inside an HTML element)
    2.External and internal style sheets (in the head section)
    3.Browser default
  So, an inline style (inside a specific HTML element) has the highest priority, which means that it will override a style defined inside the <head> tag, or in an external style sheet, or a browser default value.