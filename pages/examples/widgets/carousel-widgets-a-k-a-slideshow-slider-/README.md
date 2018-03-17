---
layout: layout
title: "Carousel widgets (a.k.a. slideshow, slider)"
navigation_title: "Carousel widgets (a.k.a. slideshow, slider)"
position: 6
lead: "Very similar to tablists, carousels also help to split up a page's content into smaller and thus more digestible parts which can be toggled visible one at a time."
---

# Carousel widgets (a.k.a. slideshow, slider)

![Typical carousel](_media/typical-carousel.png){.image}

Carousels are sometimes also called "slideshows", or "sliders". We call them "carousels" this rather exotic term to avoid confusion with [sliders](/examples/widgets/slider-widgets-a-k-a-ranges-minmax-){.page title="Slider widgets (a.k.a. ranges, min/max)"}.

Carousels offer a list of controls (usually on top of the element) which allow to toggle the visibility of corresponding panels.

Only a single control can be active at a time, so exactly one panel is visible and all others are hidden. As such, carousels are pretty identical with the pattern behind standard radio buttons.

# Similarities with accordions and tablists

Before you continue, please read [Tablist widgets (a.k.a. tab panels, tabs)](/examples/widgets/tablist-widgets-a-k-a-tab-panels-tabs-){.page} to understand why carousels simply are extended variants of tablists, providing additional controls like previous/next buttons, and autoplay functionality.

# Requirements

In addition to the tablists' requirements:

- Autoplay functionality must be pausable

(Unlike most other common widget patterns, the [WAI-ARIA Authoring Practices)](https://www.w3.org/TR/2013/WD-wai-aria-practices-20130307) don't offer a section about carousels.)

# Proof of concept

See: [What is a "Proof of concept"?](/examples/widgets/what-is-a-proof-of-concept){.page}

Based on the tablists' proof of concept:

- Additional controls (previous/next panel, autoplay) are implemented as buttons

@code(/examples/widgets/carousel-widgets-a-k-a-slideshow-slider-/_examples/proof-of-concept-carousel/){.code}

TODO: Autoplay not available yet!

In addition to the tablists' features:

- Additional controls (previous/next panel, autoplay) simply change the currently active radio button

# 3rd party widgets

Find below some ready-to-use 3rd party widgets that satisfy our requirements regarding to accessibility. See [How we evaluate JavaScript widgets](/examples/widgets/how-we-evaluate-javascript-widgets){.page}.

TODO