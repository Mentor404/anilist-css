# Anilist-CSS

Enhance your Anilist profile with this customizable CSS library.

## Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Applying CSS to Your Profile](#applying-css-to-your-profile)
- [Customization](#customization)
- [Contributing](#contributing)
- [Versioning](#versioning)
- [License](#license)
- [Preview](#preview)

## Getting Started

Follow these instructions to apply the project's CSS to your Anilist profile.

### Prerequisites

Before you begin, ensure you have [Automail](https://github.com/hohMiyazawa/Automail) installed.

Activate it by navigating to:

![Apps](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/apps.png)

Then, in your profile settings, ensure this option is checked:

![Enable CSS](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/enable.png)

### Applying CSS to Your Profile

1. In the profile tab, locate the CSS input field:

   ![CSS Field](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/css.png)

2. Choose how to apply the CSS:
   - For the full CSS:
     ```css
     @import url(https://mentor404.github.io/anilist-css/main.css);
     ```
   - For specific components:
     ```css
     @import url(https://mentor404.github.io/anilist-css/files/area-name-here.css);
     ```
   - Example:
     ```css
     @import url(https://mentor404.github.io/anilist-css/files/color-theme.css);
     @import url(https://mentor404.github.io/anilist-css/files/background.css);
     ```

   To explore all available styles, [**click here**](https://github.com/Mentor404/anilist-css/tree/main/files).

## Customization

For significant changes, clone this repository. Follow the instructions to [Fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo) and enable [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).

For minor modifications, copy and paste the desired CSS file content after the `@import` in your profile's CSS field and customize as needed.

![Customization](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/custom.png)

## Contributing

Interested in contributing? Please read [CONTRIBUTING.md](https://github.com/Mentor404/anilist-css/blob/main/CONTRIBUTING.md) for guidelines on how to contribute and our code of conduct.

## Versioning

We use [SemVer](http://semver.org/) for version control. For available versions, see the [tags in this repository](https://github.com/Mentor404/anilist-css/tags).

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Mentor404/anilist-css/blob/main/LICENSE) file for details.

## Preview

### [Main.css](https://github.com/Mentor404/anilist-css/blob/main/main.css)
![Main.css Preview](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/preview.png)

```css
@import url(https://mentor404.github.io/anilist-css/main.css);
```

### [Neon.css](https://github.com/Mentor404/anilist-css/blob/main/neon.css)
![Neon.css Preview](https://raw.githubusercontent.com/Mentor404/anilist-css/main/img/neon-css.png)

```css
@import url(https://mentor404.github.io/anilist-css/neon.css);
```

