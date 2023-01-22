## Universal Résumé Template

### Inspiration

This repo was inspired by WebPraktikos' [`Universal Résumé Template`](https://github.com/WebPraktikos/universal-resume) and [`an
adapted version`](https://github.com/Thomashighbaugh/resume) by Thomas Leon Highbaugh.

## How to run it
Clone the git repository 
```
git clone https://github.com/andreyxdd/resume
```

Navigate to the root:

```
cd resume
```

Install the dependencies:

```
yarn install
```

Start the development server after building the stylesheet out of the Tailwind configuration:

```
yarn build && yarn serve
```

Only generate CSS that is used on the page (results in a much smaller budnndle size):

```
yarn build
```


## Starting Point

`docs/index.html` is the main content file. Add or update sections, subsection, title, etc.


## Custom CSS

Code from `tailwind.config.js` and `tailwind.css` transpiles to `docs/style.css`.


## Printing

### Chrome

Right-click → Print.  

### Firefox

File → Print.
