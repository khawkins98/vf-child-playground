# vf-child

This project is a template to easily make use of core Visual Framework patterns,
override them, and add your own.

Why use a child theme? So you can programatically use (and update from)
Visual Framework core patterns, while maintain complete flexibility in the look
and function of your patterns (in addition to the Visual Framework's style
isolation principles (add link)).

## Take a few minutes to read the basics of the Visual Framework;


## Clone the Visual Framework Child Theme template

(todo: link to vf-core guide on installing dev dependencies)

- `git clone git@github.com: ... .git` (add repo url once ready)
- `cd vf-child`
- `npm install`

## Decide on project name

### 1. Set a name

Open `factal.js` and change

```
fractal.set('project.title', 'Visual Framework Child Theme');
```

Examples:

- My Company Name theme
- Visual Framework for My Company Name

### 2. Pick a prefix

Custom patterns will be prefixed by a short abbreviation or phrase. So, your
custom pattern for a countdown timer might be `acme-countdown-timer` or if you're
building for Bob's Pizza, `bp-countdown-timer`.

We'd encourage you to make it:

- unique
- no longer than four letters

Once you've picked a prefix, you'll want to save it to the pattern generator:

1. Open `/tools/component-generator/templates/index.js`
2. Set `namespace`

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
