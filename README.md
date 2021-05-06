# Frontend Mentor - Crowdfunding product page

![Design preview for the Easybank landing page coding challenge](./design/desktop-preview.jpg)

## The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

- See hover states for all interactive elements on the page

## Lessons learnt

Creating full width images need not be a nightmare. Approaches for two scenarios, assuming the content is centered in the middle column of a three column grid:

- 💡 If the element with the background color/image that you want to span the full screen is a direct child of the grid set on the body, then set `grid-column: 1 / -1`. On the same element add the `center-content` class to position its child elements and wrap all these children in a `container` to align the padding.

- 💡 If the element is not a direct child of the grid set on the body, the following works: set the `width: 100vw;` on the element you want to span the full screen, followed by `margin-left: calc(50% - 50vw)`. As above, setting the `center-content` class on the element will realign it's content, and adding a `container` will align the padding.

## Future development

✏️ More work is needed to properly understand both `img` and the `background-position` property, and `.svg` files, in particular:

- `img` how to resize and work images of different sizes and aspect rations in order to be able to organise a number of separate elements so that they appear to have the same size `img` (e.g. in a card component)
- `background-position` I spent so much time trying and failing to position the background images on this challenge. I need to find a better way or get a better understanding of how to use this property.
- `.svg` I was able to achieve some basic interaction and hover colour changes, but again I have no solid understanding of how these work. They are such a common feature that this knowledge gap also needs addressing.
