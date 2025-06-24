---
title: Shop
layout: layout.njk
---

# Shop

Here’s a selection of available works:

{% include "product-card.njk" with {
  id: "traveller-print",
  title: "Traveller (Print)",
  description: "A limited edition print of 'Traveller'. Signed.",
  price: "60",
  image: "/images/traveller.jpg"
} %}

{% include "product-card.njk" with {
  id: "pit-original",
  title: "The Pit (Original)",
  description: "Graphite on paper. Unframed. Comes with certificate.",
  price: "400",
  image: "/images/pit.jpg"
} %}
