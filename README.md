# Style Stage

## Resources used:

[CSS Reset by Andy Bell](https://piccalil.li/blog/a-modern-css-reset/)

[Background gradient from CSS Gradient](https://cssgradient.io)

[Fluid spacing variables from Andy Bell](https://gist.github.com/cynthiateeters/88825c17225ce01ef7461e3cd22997ca)

---

### Available Fluid Code Examples

[Andy Bell's spacing.css - Consistent spacing sizes, based on a ratio, with min and max sizes.](https://gist.github.com/cynthiateeters/88825c17225ce01ef7461e3cd22997ca)

[Andy Bell's text-sizes.css - A minimum and maximum text size allows you to pick the right size from a ratio, depending on the context size.](https://gist.github.com/cynthiateeters/5af47329cbe01e4497b3a0647a5aece4)

### Searching for CSS Reset/Normalize Libraries

[Search GitHub](https://github.com/search?o=desc&q=css+normalize&s=stars&type=Repositories)

[Search CDNJS - search for normalize ](https://cdnjs.com/libraries)

---
## IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.
---
