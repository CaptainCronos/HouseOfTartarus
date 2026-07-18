# Asset Naming Standard

## General format

Use lowercase snake_case:

```text
category_subject_variant_state_size.ext
```

Examples:

```text
button_primary_idle_large.png
button_primary_hover_large.png
frame_window_gold_large.png
badge_rank_founder.png
divider_ruby_long.png
texture_leather_black.png
```

## Required rules

- Use lowercase ASCII letters, numbers, and underscores only.
- Do not use spaces.
- Do not use `final`, `new`, `copy`, `latest`, or numbered duplicate suffixes such as `(1)`.
- Use a stable descriptive variant when multiple versions are intentional.
- Use two-digit numbering only when a family requires neutral numbered variants: `divider_gold_01.png`.
- Do not include `transparent` in filenames. Transparency is an export property.

## State names

Use these standard UI states where applicable:

```text
idle
hover
pressed
active
selected
disabled
focus
```

## Size names

Use these size labels where applicable:

```text
xs
small
medium
large
xl
```

Avoid embedding pixel dimensions in the main filename unless exact dimensions are part of the asset contract.
