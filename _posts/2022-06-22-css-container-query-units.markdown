---
layout: post
title:  "CSS Container Query Units"
date:   2022-06-22 08:38:31 +0900
categories: CSS
---
<https://caniuse.com/css-container-query-units>  
<https://ishadeed.com/article/container-query-units>

```css
.card {
    /* The stacked, base style */
}

.card__title {
    font-size: 1rem;
}

/* The horizontal style, v1 */
@container (min-width: 400px) {
    .card__title {
        font-size: 1.15rem;
    }
}

/* The horizontal style, v2 */
@container (min-width: 600px) {
    .card__title {
        font-size: 1.25rem;
    }
}

/* The hero style */
@container (min-width: 800px) {
    .card__title {
        font-size: 2rem;
    }
}
```

<p class="ciu_embed" data-feature="css-container-query-units" data-periods="future_1,current,past_1,past_2" data-accessible-colours="false">
<picture>
<source type="image/webp" srcset="https://caniuse.bitsofco.de/image/css-container-query-units.webp">
<source type="image/png" srcset="https://caniuse.bitsofco.de/image/css-container-query-units.png">
<img src="https://caniuse.bitsofco.de/image/css-container-query-units.jpg" alt="Data on support for the once-event-listener feature across the major browsers from caniuse.com">
</picture>
</p>
