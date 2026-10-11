# WeaverAI — organization profile

This repository holds the public profile for the WeaverAI GitHub organization. GitHub renders
[`profile/README.md`](./profile/README.md) on the organization's overview page.

## Structure

```
.
├── profile/
│   ├── README.md                       # Public organization profile
│   └── assets/
│       ├── weaverai-logo-official.svg  # Primary logo, for light backgrounds
│       ├── weaverai-logo-negative.svg  # Negative logo, for dark backgrounds
│       └── favicon.ico                 # Favicon (48×48)
└── README.md
```

## Brand assets

The profile selects the logo variant from the viewer's colour scheme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="weaverai-logo-negative.svg">
  <img src="weaverai-logo-official.svg" alt="WeaverAI">
</picture>
```

| Colour | Hex |
| --- | --- |
| Navy | `#26247A` |
| Orange | `#EF7B22` |
| Green | `#048945` |

Both logos use outlined type and render without external fonts.
