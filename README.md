# Visual Framework Child Theme template

Clone this project as a template to easily make use of core Visual Framework patterns,
override them, and add your own.

Why use a child theme? Programatically use (and update from)
Visual Framework core patterns, but with complete flexibility in the look
and function of your patterns (in addition to the Visual Framework's [style
isolation principles](https://blogs.embl.org/communications/2018/09/12/faster-scientific-websites-through-reusability/)).

## Know the basics

If you've not already, take a few minutes to [read the basics of the Visual Framework](https://github.com/visual-framework/vf-core#visual-framework-20).

## Clone the Visual Framework Child Theme template

*(You'll need gulp and node; [head here if you don't know what those are](https://github.com/visual-framework/vf-core/blob/develop/SETTINGUP.md))*

- `git clone https://github.com/khawkins98/vf-child-playground.git` (add repo url once ready)
- `cd vf-child-playground`
- `npm install`

## Decide on project name

### 1. Set a name and namespace

Open `pacakage.json` and edit:

```
"vfConfig": {
  "childThemeNamespace": "vct-",
  "childThemeName": "Visual Framework Child Theme"
},
```

- `childThemeName` examples:
  - My Company Name theme
  - Visual Framework for My Company Name
- `childThemeNamespace` prefix:
  - Custom patterns will be prefixed by a short abbreviation or phrase. So, your
    custom pattern for a countdown timer might be `acme-countdown-timer` or if you're
    building for Bob's Pizza, `bp-countdown-timer`. We'd encourage you to make it:
    - unique
    - no longer than four letters

## Launch the local pattern library

`gulp dev`

## Make and edit patterns

### Override `vf-core` patterns

### Install additional patterns

You can install patterns from vf-core or from other Visual Framework-compliant themes.

To add additional Visual Framework core patterns, find one you like and use npm;
for example, the `vf-heading` pattern:

```
npm install --save @visual-framework/vf-heading
```

If a pattern you wish to use isn't available on npm, copy it to your `/components`
directory.

In either case, after adding the pattern you'll needed to refernce the Sass in
your `/assets/scss/styles.scss`

### Learn how to create new patterns

`gulp component`

More to come.

## Customise the layout of the pattern library by editing the Fractal theme in `tools/frctl-mandelbrot-vf-subtheme`;

## Put your patterns into use

### Generate CSS and JS for your website

### Consume patterns as Sass

Follow example in `assets/scss/styles.scss`

### Deploy your pattern library

### Contribute new patterns back to the global `vf-core`;

## Ask the community for help or open an issue; and
