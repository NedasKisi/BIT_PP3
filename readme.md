### Sprint 3/ PP3 (Reuse of PP2)

## Web CV- upload to github using GIT CLI + minimal improvements

## _Please note: !IMPORTANT! problems that occured during process are listed at the bottom_

# Install Sass

## By extension

- If you are using VS code you can go to extensions on the left side of navigation or by using default shortcuts <b>CTRL+SHIFT+X for Windows</b> or <b>CMD+SHIFT+X for Mac </b>.
  - Once you open up extensions in the search bar type <b>Live sass compiler</b>, clink on the extension and click install.
  - At the bottom of VS Code <b>Watch Sass</b> button will appear. Click that and you are done.

## By downloading package or adding it to your path:

- You can install Sass by downloading the package for your operating system [from GitHub](https://github.com/sass/dart-sass/releases) or [adding it to your `PATH`](https://katiek2.github.io/path-doc/).

## By using node

If you use Node.js, you can also install Sass using [npm][] by running

[npm]: https://www.npmjs.com/

```
npm install -g sass
```

**However, please note** that this will install the pure JavaScript
implementation of Sass, which runs somewhat slower than the other options listed
here. But it has the same interface, so it'll be easy to swap in another
implementation later if you need a bit more speed!

See [the Sass website](https://sass-lang.com/install) for more ways to install
Sass.

Once you have Sass installed, you can run the `sass` executable to compile
`.sass` and `.scss` files to `.css` files. For example:

```
sass source/stylesheets/index.scss build/stylesheets/index.css
```

# Project tasks

- Create a website with at least 3 pages.
- Upload to github
- Keep the code clean - structure ,validity, website, github.
- Create readme.md with installation instructions.

# Project workflow

- Added blank html pages as initial commit (to check if it works).
- Added layout, nav and content.
- Added gallery and images + missing form.scss file.
- Added footer, progress bar, rwd.
- Created new branch "updates".
- Added 3rd column to footer and zoom in on hero image on hover.

- Original website uploaded to github manually, can be accessed:[Sprint3/PP3](https://nedaskisi.github.io/BIT_PP3/)

# Goal

- Implement SCSS or Bootstrap in a project.
- Use GIT CLI commands to push project on Github.
- Minimum requirement: 2 branches and 5 commits.
- Must detalize installation process and how to launch.

## About The Project

- Learning project: SCSS responsive web design.
- Project is done using SCSS. Reusing PP2 with minimal improvements.

## Problems that occured

- Could not install live Sass compiler (kept getting error). Managed to do it manually.
- SCSS (Watch SASS) kept restarting and not compiling, caused internal crashes. Managed to fix it by using old files.
- Wanted to do major improvements like: Dark mode, calendar and local time. Lost some code due to crash. Discarded the idea this time to not get behind on current topics during lectures.
- Kept running into problems when using js (lack of knowledge got in the way to code efficiently and effectively).
