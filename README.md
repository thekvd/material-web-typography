# material-web-typography
Material Web's Typography defaults compiled from @material/web's Typescale and Typeface Sass Partials based on Material Design 3.

Based on their suggestions at https://material-web.dev/theming/typography/ I've added these:

``` 
  --my-brand-font: 'Open Sans';
  --my-headline-font: 'Montserrat';
  --my-title-font: 'Montserrat';
  --my-plain-font: system-ui;

  --md-ref-typeface-brand: var(--my-brand-font);
  --md-ref-typeface-plain: var(--my-plain-font);

  --md-sys-typescale-body-font: var(--my-plain-font);
  --md-sys-typescale-display-font: var(--my-brand-typeface);
  --md-sys-typescale-headline-font: var(--my-headline-font);
  --my-sys-typescale-label-font: var(--my-plain-font);
  --md-sys-typescale-title-font: var(--my-title-font);

```

and changed all the default fonts of the scales to point to the ```--md-sys-typescale-<scale>-font``` variable.

I don't plan to maintain this one past the point that they implement it beyond Sass mixins so use this as a jumping off point and go ham!
