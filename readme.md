# Setup
- Make sure [node.js](http://nodejs.org) and [roots](http://roots.cx/articles/getting-started) are installed.
- Clone this repo down and `cd` into the folder.
- Run `npm install`.
- Run `roots watch`. This will will perform all watch tasks, spin up a server, and point your browser to `localhost:1111/`

# Technologies / Dependencies
- **[Roots](http://roots.cx)** – Roots is a fast, simple, and customizable static site compiler and task runner. It is responsible for all minification, concatination, and watch tasks for dev.
- **[Stylus](http://learnboost.github.io/stylus/)** – Stylus provides extremely fast, expressive, powerful, and robust pre-processing for our CSS. Also accepts Sass, or vanilla css.
- **[Axis](http://axis.netlify.com)** – Stylus mixins and utlities
- **[Lost](https://github.com/corysimmons/lost)** – Fractional grid system, successor to [Jeet](http://www.jeet.gs).
- **[Rupture](http://jenius.github.io/rupture/)** – Stylus media query utility for clean breakpoints

# Deploying
- If you just want to compile the production build, run `roots compile -e production` and it will build to public.
- To deploy your site with a single command, run `roots deploy -to XXX` with `XXX` being whichever [ship](https://github.com/carrot/ship#usage) deployer you want to use.
