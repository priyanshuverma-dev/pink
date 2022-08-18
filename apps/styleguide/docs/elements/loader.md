# Loader

```html
<div class="loader"></div>
```

# Loader with Card and Button
Loader inside Card partial with Button partial
- also using utility classes of "ul-flex", "u-gap-16", "u-cross-center" and "u-stretch"
```html
<div class="card u-flex u-gap-16 u-cross-center" style="--p-card-border-radius:var(--border-radius-xsmall); --p-card-padding:1.5rem;">
    <div class="loader"></div>
    <p class="u-stretch">Provide contextual message</p>
    <button class="button is-secondary">
        <span class="text">button</span>
    </button>
</div>
```