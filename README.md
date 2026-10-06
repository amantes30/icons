# Icons & Visual Assets

A personal collection of **icons, logos, and visual assets** in multiple formats for use across web projects, applications, interfaces, and other digital work.

The repository acts as a centralized asset library, keeping commonly used visual resources organized by file type and style.

## Contents

The repository currently contains the following asset collections:

| Directory     | Description             |
| ------------- | ----------------------- |
| `GIF/`        | Animated GIF assets     |
| `Gold Icons/` | Gold-themed icon assets |
| `ICO/`        | ICO/favicon assets      |
| `JPG/`        | JPG image assets        |
| `PNG/`        | PNG image assets        |
| `SVG/`        | SVG vector assets       |

Additional assets are stored in the repository root when they are project-specific, such as:

```text
vswork-logo.png
```

## Repository Structure

```text
icons/
├── GIF/
├── Gold Icons/
├── ICO/
├── JPG/
├── PNG/
├── SVG/
├── vswork-logo.png
├── .gitignore
└── README.md
```

## Why This Repository Exists

Instead of keeping commonly used visual assets scattered across different projects and local folders, this repository provides a single place to store and organize them.

It can be used as a personal asset library for:

* Web applications
* Developer portfolios
* UI/UX projects
* Desktop applications
* Branding
* Logos
* Favicons
* Documentation
* Presentations
* Prototypes

## Using the Assets

Clone the repository:

```bash
git clone https://github.com/amantes30/icons.git
```

Then navigate to the desired asset collection:

```bash
cd icons
```

Assets can be copied directly into another project or referenced from the repository when appropriate.

### SVG

SVG assets can be used directly in HTML:

```html
<img src="./SVG/example.svg" alt="Example icon">
```

They can also be embedded directly into HTML when modification or styling is required.

### PNG

```html
<img src="./PNG/example.png" alt="Example image">
```

### GIF

```html
<img src="./GIF/example.gif" alt="Animated image">
```

### ICO

ICO files can be used as website favicons:

```html
<link rel="icon" href="./ICO/favicon.ico">
```

## Asset Formats

### SVG

Best suited for:

* UI icons
* Logos
* Scalable graphics
* Web interfaces

SVG files can scale without losing quality and are generally preferable for interface icons when available.

### PNG

Best suited for:

* Transparent images
* Logos
* UI assets
* Images requiring lossless quality

### JPG

Best suited for:

* Photographic images
* Large raster images
* Assets where transparency is not required

### GIF

Used primarily for:

* Animations
* Small visual effects
* Animated UI assets

### ICO

Primarily used for:

* Website favicons
* Windows application icons

## Adding New Assets

When adding new assets, place them in the directory corresponding to their file format.

For example:

```text
new-icon.svg
```

should be placed in:

```text
SVG/
```

while a PNG asset should be placed in:

```text
PNG/
```

For assets that belong to a particular visual collection, use the appropriate collection directory rather than creating unnecessary new categories.

## Naming

Where possible, use descriptive filenames so assets can be found easily.

Prefer:

```text
github-icon.svg
search-icon.svg
user-profile.png
```

over:

```text
icon1.svg
image2.png
newnew.png
```

For existing assets, filenames are preserved where changing them could break references in projects that already use them.

## Using Assets in Other Projects

This repository is intended primarily as a convenient personal asset collection.

Before redistributing an asset publicly or using it in a commercial project, **verify the original asset's license and usage restrictions**.

Not every image or icon in an asset collection necessarily has the same licensing terms.

## Organization

The repository intentionally separates assets primarily by file format:

```text
GIF
│
├── animated assets
│
Gold Icons
│
├── gold-themed icons
│
ICO
│
├── favicon/application icons
│
JPG
│
├── raster images
│
PNG
│
├── raster images
│
SVG
│
└── vector icons and graphics
```

This keeps the repository simple and makes it easy to locate an asset without requiring a build system or package manager.

## License

No repository-wide open-source license is currently specified.

Because this repository contains visual assets that may originate from different sources, **individual asset licensing should be checked before redistribution or commercial use**.

## Author

**amantes30**

GitHub:
https://github.com/amantes30
