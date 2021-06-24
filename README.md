🙌 TinyWins Ghost Template
---

Welcome! Here's our Ghost template that we use for our newsletter. Maintained by the 🙌 TinyWins Team. We're happy to share and use it how you want. We made it in 2 days with the use of some awesome resources listed below.👇 Check them all out!

MIT License (There's no warranty and really anything guaranteed with this template, AS-IS)

### Resources

Add Tailwinds to template via [How to create a Ghost theme with Tailwind CSS.](https://www.usepine.com/blog/en/how-to-create-a-ghost-theme-with-tailwind-css/)

[Edition Template by Ghost](https://github.com/TryGhost/Edition) saved a lot of time with shortcuts.

[TailwindsCSS](https://tailwindcss.com/)

[tailwindcomponents](https://tailwindcomponents.com/)


### Development Notes from [Ghost Starter](https://github.com/TryGhost/Starter/blob/master/README.md)

> I just took what they did with Gulp from here.

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

### PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.
- [Color Mod](https://github.com/jonathantneal/postcss-color-mod-function)