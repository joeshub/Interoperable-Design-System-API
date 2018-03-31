# Interoperable Design System API (IDSAPI)
The goal of this project is to build an [Interoperable](https://en.wikipedia.org/wiki/Interoperability) Design System API which empowers consumers to seamlessly switch from one design system to another.

https://twitter.com/joeseifi/status/979898260142739457

## Preface
We are starting to see really advanced design systems being built on top of [React](https://github.com/facebook/react) and [CSS-in-JS libraries](https://github.com/MicheleBertoli/css-in-js). This is great for now but as the number of publicly available Design Systems grow, we will end up with a large set of design systems that are not interoperable. Meaning the cost of moving from one to the other will be too high due to the lack of a shared specification.

The goal of this project is to build a common API, similar to the HTML spec, for UI components, to be adopted by Design Systems developers. Each system would implement their component internals, and only expose a common IDSAPI to consumers.

Creating a design system built on top of IDSAPI does not require building a full UI component list and their respective APIs. The only thing you should need to worry about is how those components look and behave.

## Goals
* Start with IDSAPI documentation
* Start small. We can start by creating the API for shared [atoms](http://bradfrost.com/blog/post/atomic-web-design/) used in all Design System.
* Consumers should be able to install and use parts from multiple design systems simultaneously.
* Components should have common similar APIs for callbacks, variations and data exchange.
* Across all components similar props should be consistent.

## Challenges
- Standardizing on a currently highly opinionated API
- Designs systems may have internal dependencies which would need to be installed

## List of Existing Design Systems using React
A case study to see if this is feasible by surveying a list of existing DS's
- https://github.com/auth0/cosmos (Styled Components)
- https://github.com/seek-oss/seek-style-guide (CSS Modules and PostCSS)
- https://github.com/mui-org/material-ui (JSS)
- https://github.com/pluralsight/design-system (Glamor & PostCSS)
- https://github.com/salesforce/design-system-react (Plain CSS)

## Inspiration
- https://github.com/cssinjs/istf-spec
- https://github.com/css-modules/icss
- https://github.com/diegohaz/arc
- https://github.com/jxnblk/rebass
- https://github.com/johnpolacek/design-system-playground
- https://www.youtube.com/watch?v=bLgZwFRYTJ4
- https://github.com/mrmartineau/design-system-utils
- https://airbnb.design/building-a-visual-language/

