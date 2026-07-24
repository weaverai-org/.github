# `.github` — WeaverAI organization profile

This is WeaverAI's special **`.github`** repository. GitHub renders
[`profile/README.md`](./profile/README.md) as the public profile page shown on the
organization's account at `github.com/weaverai`.

## Structure

```
.
├── profile/
│   ├── README.md            # ← the public org profile (what visitors see)
│   └── assets/
│       ├── logo.svg         # full horizontal logo (wordmark + mark)
│       ├── icon.svg         # square app/avatar mark
│       ├── icon-512.png     # 512px avatar — upload as the org avatar
│       ├── icon-192.png     # 192px icon
│       ├── favicon.svg      # scalable favicon
│       ├── favicon.ico      # multi-res favicon (16/32)
│       ├── favicon-16.png
│       ├── favicon-32.png
│       └── apple-touch-icon.png
└── README.md                # this file
```

## Using the brand assets

- **Org avatar:** upload `profile/assets/icon-512.png` in
  *Organization settings → Profile → Profile picture*.
- **Favicon (for any WeaverAI website):**
  ```html
  <link rel="icon" href="/favicon.ico" sizes="any">
  <link rel="icon" href="/favicon.svg" type="image/svg+xml">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  ```

## Brand

| Token | Value |
| --- | --- |
| Indigo | `#6366F1` |
| Violet | `#8B5CF6` |
| Cyan | `#22D3EE` |
| Ink (dark) | `#111827` |

Tagline: **"Weaving intelligence into everything we build."**
