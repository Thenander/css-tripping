# CSS trippin

My plan was to do a css-loader.  
Well, that escalated quickly.

---

Code example

```
@for $i from 1 to 10 {
  &:nth-child(#{$i}) {
    filter: hue-rotate($i * 40deg);
    animation-delay: $i * 0.2s;
  }
}
```

[Online DEMO](https://microlab.se/css-tripping)
