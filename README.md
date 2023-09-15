# Uconn Module 1 Challenge

## Challenge for this module
### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## How this was accomplished

> Semantic elements used
> - `div` elements were switched for semantic elements like `header` and `article`
> - This improves accessability

> CSS Attributes Consolidated
> - `div` elements switched in `style.css` for their new semantic elements
> - Many elements used the same attributes in different selectors so they were consolidated to central elements such as general `h1` headers for all elements
> - `style.css` was commented on thoroughly

> Accessibility
> - All images and icons were given alt text
> - A title was given to the website

> Functionality
> - Inspect Element was used on the original sample code to grab attributes and test to make sure styling was maintained
> - Navbar links were kept functional by giving a unique `id` to all main articles
> - New heading styles, a general `h3` and `h4` were added to maintain consistent styling with the original while still using best practice.

## Deployed Website

Here is a link to the [deployed website]().

### Screenshot

![Screenshot of deployed website](/assets/images/Screenshot_1.jpg)

