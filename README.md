# Interoperable Design System API (IDSAPI)
The goal of this project is to build an [Interoperable](https://en.wikipedia.org/wiki/Interoperability) Design System API which empowers consumers to seamlessly switch from one design system to another.

https://twitter.com/joeseifi/status/979898260142739457

## Preface
We are starting to see really advanced design systems being built on top of [React](https://github.com/facebook/react) and [CSS-in-JS libraries](https://github.com/MicheleBertoli/css-in-js). This is great for now but as the number of publicly available Design Systems grow, we will end up with a large set of design systems that are not interoperable. Meaning the cost of moving from one to the other will be too high due to the lack of a shared specification.

The goal of this project is to build a common API, similar to the HTML spec, for UI components, to be adopted by Design Systems developers. Each system would implement their component internals, and only expose a common IDSAPI to consumers.

## Challenges
- Standardizing on a highly opinionated API 

## List of Existing Design Systems using React
A case study to see if this is feasible by surveying a list of existing DS's
- https://github.com/auth0/cosmos (Styled Components)
- https://github.com/seek-oss/seek-style-guide (CSS Modules and PostCSS)
- https://github.com/mui-org/material-ui (JSS)

## Inspiration
- https://github.com/cssinjs/istf-spec
- https://github.com/css-modules/icss
- https://www.youtube.com/watch?v=bLgZwFRYTJ4
- https://github.com/mrmartineau/design-system-utils
- https://airbnb.design/building-a-visual-language/

