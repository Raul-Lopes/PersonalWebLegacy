# Raul Lopes – Legacy Personal Web Page

A snapshot of my early personal website, built with frontend tooling and libraries common around **2017–2018**.

## Tech Stack

- **Framework**: Plain HTML/CSS/JavaScript with modular includes via Gulp
- **Styling**:
    - [Bootstrap 4.1.1](https://getbootstrap.com/docs/4.1/) (with manual asset copying from `node_modules`)
    - [Bootstrap Sass](https://github.com/twbs/bootstrap-sass) (v3.3.7, used during transition)
- **Icons**: [Font Awesome](https://fontawesome.com/v4.7/) (v4, manually copied into project)
- **Build Tool**: [Gulp 3.9.1](https://gulpjs.com/) for automation
- **Gulp Plugins**:
    - `gulp-sass` – Compile Sass to CSS
    - `gulp-autoprefixer` – Add vendor prefixes
    - `gulp-concat`, `gulp-uglify`, `gulp-cssnano` – Bundle and minify assets
    - `gulp-file-include` – Modular HTML templating
    - `browser-sync` – Live reload during development
    - `gulp-imagemin`, `gulp-clean`, `gulp-rename`, `gulp-uncss` – Optimization & cleanup

## Notes

- This project reflects frontend workflows before modern bundlers like Webpack or Vite became standard.
- Assets (Bootstrap, Font Awesome) were manually copied via a `postinstall` script due to limitations in asset handling at the time.
- No framework (React, Angular, etc.)—just static pages enhanced with Gulp automation.

> 💡 A nostalgic look at how frontend tooling has evolved!