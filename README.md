# bulma-io-snippets README

This is still work-in-progress. Check the CHANGELOG.md to see what is alreay available.
## Table Of Content
1. [Overview](##Overview)
   - [Start](###Start)
2. [Modifiers](##Modifiers)
    - [Helpers](###Helpers)
    - [Responsive Helpers](###Responsive-Helpers)
    - [Color Helpers](###Color-Helpers)
    - [Typography Helpers](###Typography-Helpers)
3. [Columns](##Columns)
    - [Basics](###Basics)
    - [Column sizes](###Column-sizes)


## [Overview](https://bulma.io/documentation/overview)

### [Start](https://bulma.io/documentation/overview/start)

Trigger | Description
--- | ---
b:Font.Awesome.5|If you want to use icons with Bulma, don't forget to include (Font Awesome 5)[https://fontawesome.com/]

<p align="right"><a href="#table-of-content">TOC</a></p>

## [Modifiers](https://bulma.io/documentation/modifiers)

### [Helpers](https://bulma.io/documentation/modifiers/helpers)
Trigger | Description
--- | ---
b:is-clearfix|Fixes an element's floating children
b:is-pulled-left|Moves an element to the left
b:is-pulled-right|Moves an element to the right
b:is-marginless|Removes any margin
b:is-paddingless|Removes any padding
b:is-overlay|Completely covers the first positioned parent
b:is-clipped|Adds overflow hidden
b:is-radiusless|Removes any radius
b:is-shadowless|Removes any shadow
b:is-unselectable|Prevents the text from being selectable
b:is-invisible|Adds visibility hidden
b:is-hidden|Hides element
b:is-sr-only|Hide elements visually but keep the element available to be announced by a screen reader
b:is-relative|Applies 'position: relative' to the element.

<p align="right"><a href="#table-of-content">TOC</a></p>

### [Responsive Helpers](https://bulma.io/documentation/modifiers/responsive-helpers)
Trigger | Description
--- | ---
b:is-block|'display: block !important;'
b:is-block-mobile|'display: block !important;' for Mobile (Up to 768px)
b:is-block-tablet|'display: block !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-block-tablet-only|'display: block !important;' for Tablet (between 769px and 1023px)
b:is-block-touch|'display: block !important;' for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-block-desktop|'display: block !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-block-desktop-only|'display: block !important;' for Desktop (between 1024px and 1215px)
b:is-block-widescreen|'display: block !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-block-widescreen-only|'display: block !important;' for Widescreen (between 1216px and 1407px)
b:is-block-fullhd|'display: block !important;' for FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-flex|'display: flex !important;'
b:is-flex-mobile|'display: flex !important;' for Mobile (Up to 768px)
b:is-flex-tablet|'display: flex !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-flex-tablet-only|'display: flex !important;' for Tablet (between 769px and 1023px)
b:is-flex-touch|'display: flex !important;' for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-flex-desktop|'display: flex !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-flex-desktop-only|'display: flex !important;' for Desktop (between 1024px and 1215px)
b:is-flex-widescreen|'display: flex !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-flex-widescreen-only|'display: flex !important;' for Widescreen (between 1216px and 1407px)
b:is-flex-fullhd|'display: flex !important;' for FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-inline|'display: inline !important;'
b:is-inline-mobile|'display: inline !important;' for Mobile (Up to 768px)
b:is-inline-tablet|'display: inline !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-tablet-only|'display: inline !important;' for Tablet (between 769px and 1023px)
b:is-inline-touch|'display: inline !important;' for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-inline-desktop|'display: inline !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-desktop-only|'display: inline !important;' for Desktop (between 1024px and 1215px)
b:is-inline-widescreen|'display: inline !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-widescreen-only|'display: inline !important;' for Widescreen (between 1216px and 1407px)
b:is-inline-fullhd|'display: inline !important;' for FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-inline-block|'display: inline-block !important;'
b:is-inline-block-mobile|'display: inline-block !important;' for Mobile (Up to 768px)
b:is-inline-block-tablet|'display: inline-block !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-block-tablet-only|'display: inline-block !important;' for Tablet (between 769px and 1023px)
b:is-inline-block-touch|'display: inline-block !important;' for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-inline-block-desktop|'display: inline-block !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-block-desktop-only|'display: inline-block !important;' for Desktop (between 1024px and 1215px)
b:is-inline-block-widescreen|'display: inline-block !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-block-widescreen-only|'display: inline-block !important;' for Widescreen (between 1216px and 1407px)
b:is-inline-block-fullhd|'display: inline-block !important;' for FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-inline-flex|'display: inline-flex !important;'
b:is-inline-flex-mobile|'display: inline-flex !important;' for Mobile (Up to 768px)
b:is-inline-flex-tablet|'display: inline-flex !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-flex-tablet-only|'display: inline-flex !important;' for Tablet (between 769px and 1023px)
b:is-inline-flex-touch|'display: inline-flex !important;' for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-inline-flex-desktop|'display: inline-flex !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-flex-desktop-only|'display: inline-flex !important;' for Desktop (between 1024px and 1215px)
b:is-inline-flex-widescreen|'display: inline-flex !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-inline-flex-widescreen-only|'display: inline-flex !important;' for Widescreen (between 1216px and 1407px)
b:is-inline-flex-fullhd|'display: inline-flex !important;' for FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-hidden-mobile|'display: none !important;' for Mobile (Up to 768px)
b:is-hidden-tablet-only|'display: none !important;' for Tablet (between 769px and 1023px)
b:is-hidden-desktop-only|'display: none !important;' for Desktop (between 1024px and 1215px)
b:is-hidden-widescreen-only|'display: none !important;' for Widescreen (between 1216px and 1407px)
b:is-hidden-touch|'display: none !important;' for Mobile (Up to 768px) & Tablet (between 769px and 1023px)
b:is-hidden-tablet|'display: none !important;' for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-hidden-desktop|'display: none !important;' for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-hidden-widescreen|'display: none !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-hidden-fullhd|'display: none !important;' for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
<p align="right"><a href="#table-of-content">TOC</a></p>


### [Color Helpers](https://bulma.io/documentation/modifiers/color-helpers)
Trigger | Description
--- | ---
b:has-text-white|Text Color hsl(0, 0%, 100%)
b:has-text-black|Text Color hsl(0, 0%, 4%)
b:has-text-light|Text Color hsl(0, 0%, 96%)
b:has-text-dark|Text Color hsl(0, 0%, 21%)
b:has-text-primary|Text Color hsl(171, 100%, 41%)
b:has-text-info|Text Color hsl(204, 86%, 53%)
b:has-text-link|Text Color hsl(217, 71%, 53%)
b:has-text-success|Text Color hsl(141, 71%, 48%)
b:has-text-warning|Text Color hsl(48, 100%, 67%)
b:has-text-danger|Text Color hsl(348, 100%, 61%)
b:has-text-black-bis|Text Color hsl(0, 0%, 7%)
b:has-text-black-ter|Text Color hsl(0, 0%, 14%)
b:has-text-grey-darker|Text Color hsl(0, 0%, 21%)
b:has-text-grey-dark|Text Color hsl(0, 0%, 29%)
b:has-text-grey|Text Color hsl(0, 0%, 48%)
b:has-text-grey-light|Text Color hsl(0, 0%, 71%)
b:has-text-grey-lighter|Text Color hsl(0, 0%, 86%)
b:has-text-white-ter|Text Color hsl(0, 0%, 96%)
b:has-text-white-bis|Text Color hsl(0, 0%, 98%)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-background-white|Background Color hsl(0, 0%, 100%)
b:has-background-black|Background Color hsl(0, 0%, 4%)
b:has-background-light|Background Color hsl(0, 0%, 96%)
b:has-background-dark|Background Color hsl(0, 0%, 21%)
b:has-background-primary|Background Color hsl(171, 100%, 41%)
b:has-background-info|Background Color hsl(204, 86%, 53%)
b:has-background-link|Background Color hsl(217, 71%, 53%)
b:has-background-success|Background Color hsl(141, 71%, 48%)
b:has-background-warning|Background Color hsl(48, 100%, 67%)
b:has-background-danger|Background Color hsl(348, 100%, 61%)
b:has-background-black-bis|Background Color hsl(0, 0%, 7%)
b:has-background-black-ter|Background Color hsl(0, 0%, 14%)
b:has-background-grey-darker|Background Color hsl(0, 0%, 21%)
b:has-background-grey-dark|Background Color hsl(0, 0%, 29%)
b:has-background-grey|Background Color hsl(0, 0%, 48%)
b:has-background-grey-light|Background Color hsl(0, 0%, 71%)
b:has-background-grey-lighter|Background Color hsl(0, 0%, 86%)
b:has-background-white-ter|Background Color hsl(0, 0%, 96%)
b:has-background-white-bis|Background Color hsl(0, 0%, 98%)

<p align="right"><a href="#table-of-content">TOC</a></p>

### [Typography Helpers](https://bulma.io/documentation/modifiers/typography-helpers)
Trigger | Description
--- | ---
b:is-size-1|Font-size 3rem
b:is-size-1-desktop|Font-size 3rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-1-fullhd|Font-size 3rem for FullHD (1408px and above)
b:is-size-1-mobile|Font-size 3rem for Mobile (Up to 768px)
b:is-size-1-tablet|Font-size 3rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-1-touch|Font-size 3rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-1-widescreen|Font-size 3rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-2|Font-size 2.5rem
b:is-size-2-desktop|Font-size 2.5rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-2-fullhd|Font-size 2.5rem for FullHD (1408px and above)
b:is-size-2-mobile|Font-size 2.5rem for Mobile (Up to 768px)
b:is-size-2-tablet|Font-size 2.5rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-2-touch|Font-size 2.5rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-2-widescreen|Font-size 2.5rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-3|Font-size 2rem
b:is-size-3-desktop|Font-size 2rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-3-fullhd|Font-size 2rem for FullHD (1408px and above)
b:is-size-3-mobile|Font-size 2rem for Mobile (Up to 768px)
b:is-size-3-tablet|Font-size 2rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-3-touch|Font-size 2rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-3-widescreen|Font-size 2rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-4|Font-size 1.5rem
b:is-size-4-desktop|Font-size 1.5rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-4-fullhd|Font-size 1.5rem for FullHD (1408px and above)
b:is-size-4-mobile|Font-size 1.5rem for Mobile (Up to 768px)
b:is-size-4-tablet|Font-size 1.5rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-4-touch|Font-size 1.5rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-4-widescreen|Font-size 1.5rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-5|Font-size 1.25rem
b:is-size-5-desktop|Font-size 1.25rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-5-fullhd|Font-size 1.25rem for FullHD (1408px and above)
b:is-size-5-mobile|Font-size 1.25rem for Mobile (Up to 768px)
b:is-size-5-tablet|Font-size 1.25rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-5-touch|Font-size 1.25rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-5-widescreen|Font-size 1.25rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-6|Font-size 1rem
b:is-size-6-desktop|Font-size 1rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-6-fullhd|Font-size 1rem for FullHD (1408px and above)
b:is-size-6-mobile|Font-size 1rem for Mobile (Up to 768px)
b:is-size-6-tablet|Font-size 1rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-6-touch|Font-size 1rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-6-widescreen|Font-size 1rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-7|Font-size 0.75rem
b:is-size-7-desktop|Font-size 0.75rem for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-7-fullhd|Font-size 0.75rem for FullHD (1408px and above)
b:is-size-7-mobile|Font-size 0.75rem for Mobile (Up to 768px)
b:is-size-7-tablet|Font-size 0.75rem for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:is-size-7-touch|Font-size 0.75rem for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:is-size-7-widescreen|Font-size 0.75rem for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-text-centered|Makes the text centered
b:has-text-centered-desktop|Makes the text centered for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-centered-desktop-only|Makes the text centered for Desktop (between 1024px and 1215px)
b:has-text-centered-fullhd|Makes the text centered for FullHD (1408px and above)
b:has-text-centered-mobile|Makes the text centered for Mobile (Up to 768px)
b:has-text-centered-tablet|Makes the text centered for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-centered-tablet-only|Makes the text centered for Tablet (between 769px and 1023px)
b:has-text-centered-touch|Makes the text centered for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:has-text-centered-widescreen|Makes the text centered for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-centered-widescreen-only|Makes the text centered for Widescreen (between 1216px and 1407px)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-text-justified|Makes the text justified
b:has-text-justified-desktop|Makes the text justified for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-justified-desktop-only|Makes the text justified for Desktop (between 1024px and 1215px)
b:has-text-justified-fullhd|Makes the text justified for FullHD (1408px and above)
b:has-text-justified-mobile|Makes the text justified for Mobile (Up to 768px)
b:has-text-justified-tablet|Makes the text justified for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-justified-tablet-only|Makes the text justified for Tablet (between 769px and 1023px)
b:has-text-justified-touch|Makes the text justified for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:has-text-justified-widescreen|Makes the text justified for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-justified-widescreen-only|Makes the text justified for Widescreen (between 1216px and 1407px)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-text-left|Makes the text aligned to the left
b:has-text-left-desktop|Makes the text aligned to the left for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-left-desktop-only|Makes the text aligned to the left for Desktop (between 1024px and 1215px)
b:has-text-left-fullhd|Makes the text aligned to the left for FullHD (1408px and above)
b:has-text-left-mobile|Makes the text aligned to the left for Mobile (Up to 768px)
b:has-text-left-tablet|Makes the text aligned to the left for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-left-tablet-only|Makes the text aligned to the left for Tablet (between 769px and 1023px)
b:has-text-left-touch|Makes the text aligned to the left for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:has-text-left-widescreen|Makes the text aligned to the left for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-left-widescreen-only|Makes the text aligned to the left for Widescreen (between 1216px and 1407px)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-text-right|Makes the text aligned to the right
b:has-text-right-desktop|Makes the text aligned to the right for Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-right-desktop-only|Makes the text aligned to the right for Desktop (between 1024px and 1215px)
b:has-text-right-fullhd|Makes the text aligned to the right for FullHD (1408px and above)
b:has-text-right-mobile|Makes the text aligned to the right for Mobile (Up to 768px)
b:has-text-right-tablet|Makes the text aligned to the right for Tablet (between 769px and 1023px), Desktop (between 1024px and 1215px), Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-right-tablet-only|Makes the text aligned to the right for Tablet (between 769px and 1023px)
b:has-text-right-touch|Makes the text aligned to the right for Mobile (up to 768px) & Tablet (between 769px and 1023px)
b:has-text-right-widescreen|Makes the text aligned to the right for Widescreen (between 1216px and 1407px) & FullHD (1408px and above)
b:has-text-right-widescreen-only|Makes the text aligned to the right for Widescreen (between 1216px and 1407px)

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-capitalized|Transforms the first character of each word to uppercase
b:is-lowercase|Transforms all characters to lowercase
b:is-uppercase|Transforms all characters to uppercase
b:is-italic|Transforms all characters to italic

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:has-text-weight-light|Transforms text weight to light
b:has-text-weight-normal|Transforms text weight to normal
b:has-text-weight-medium|Transforms text weight to medium
b:has-text-weight-semibold|Transforms text weight to semi-bold
b:has-text-weight-bold|Transforms text weight to bold

<p align="right"><a href="#table-of-content">TOC</a></p>

Trigger | Description
--- | ---
b:is-family-sans-serif|Sets font family to $family-sans-serif
b:is-family-monospace|Sets font family to $family-monospace
b:is-family-primary|Sets font family to $family-primary
b:is-family-secondary|Sets font family to $family-secondary
b:is-family-code|Sets font family to $family-code

<p align="right"><a href="#table-of-content">TOC</a></p>

## [Columns](https://bulma.io/documentation/columns)

### [Basics](https://bulma.io/documentation/columns/basics)
Trigger | Description
--- | ---
b:columns:2|2 columns of equal width
b:columns:3|3 columns of equal width
b:columns:4|4 columns of equal width
b:columns:5|5 columns of equal width

<p align="right"><a href="#table-of-content">TOC</a></p>

### [Column sizes](https://bulma.io/documentation/columns/sizes)
Trigger | Description
--- | ---
b:is-three-quarters|Column has a width of three quarters
b:is-half|Column has half width
b:is-one-quarter|Column has a width of one quarter
b:is-one-third|Column has a width of one third
b:is-two-thirds|Column has a width of two thirds
b:is-four-fifths|Column has a width of four fifths
b:is-three-fifths|Column has a width of three fifths
b:is-two-fifths|Column has a width of two fifths
b:is-one-fifth|Column has a width of one fifth
b:is-full|Column has full width

<p align="right"><a href="#table-of-content">TOC</a></p>
