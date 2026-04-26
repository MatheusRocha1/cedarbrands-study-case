# Shopify Frontend Developer Case Study

## Overview

This project contains the Shopify sections implemented for the Bloomy landing page case study.

The implementation focuses on creating reusable Shopify sections, matching the provided design where available, and making reasonable layout and responsiveness decisions where the mockup was low-fidelity.

The project follows a Shopify theme structure, with the Bloomy section templates in `sections/`, related styles in `assets/`, and Bloomy sections already configured on the home page template.

## Implemented sections

- `sections/bloomy-hero-banner.liquid` - **Bloomy Hero Banner**: Hero banner section based on the provided Bloomy landing page design, with responsive desktop and mobile imagery, badge support, heading copy, CTA, and attribute items.
- `sections/bloomy-stage-infocards.liquid` - **Bloomy Stage Infocards**: Stage-based card section for presenting developmental age groups with image cards, titles, subtitles, and descriptive copy.
- `sections/bloomy-purposeful-play-banner.liquid` - **Bloomy Purposeful Play**: Full-width image and content banner for introducing purposeful play, including heading, supporting text, body copy, and CTA.
- `sections/bloomy-comparison-table.liquid` - **Bloomy Comparison Table**: Responsive comparison table section based on the low-fidelity annex mockup, comparing purposeful play toys against high-stimulation or pre-programmed toys.

## How to view

The project can be viewed in two ways.

### Option 1: Upload the theme to Shopify

1. Upload the theme files to a Shopify development store.
2. Open the Shopify theme editor.
3. Open the home page template. The Bloomy sections are already added to the home page.
4. Upload or select the required images for the Bloomy sections after the theme upload.
5. Preview the home page on desktop and mobile.

### Option 2: Run locally with Shopify CLI

1. Make sure Shopify CLI is installed.
2. Log in to the Shopify store using Shopify CLI, if needed.
3. Run the theme locally using:

```bash
shopify theme dev -s {storeName}
```

Replace `{storeName}` with the development store name or store domain used by Shopify CLI.
