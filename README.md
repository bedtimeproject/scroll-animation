# The Bedtime Project - Scroll Animation Module

## Data Structure

```js
const story = {
  defaultBackgroundColor: "#DDDDDD",
  stanzaBackgroundColor: "#8bc9e4",
  animationOverlap: "true",
  title: "A Scroll Animation",
  author: "FostyWally",
  titleCard: "default",
  titleBackground: "#FF0000",
  attributionBackground: "#00FF00",
  attributionCard: "default",
  stanzaCard: "default",
  attribution: "Written by FostyWally\nAnimated by Captain Code 😎",
  body: [
    {
      stanza:
        "It's that time of day, it's the time we sit down.\n\nAnd watch the sun fall on our small mountain town",
      images: [
        {
          component: "Sun",
          positionX: "right",
          positionY: "top",
          animation: "slidedown",
          stanzaCount: 1,
        },
        {
          component: "Mountain",
          positionX: "left",
          positionY: "bottom",
          animation: "fade",
          stanzaCount: 4,
        },
      ],
      background: "#8bc9e4",
    },
    ...
  ]
};
```

## Example

```js
<ScrollAnimation story={story} />
```
