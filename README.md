# Conchen Eyewear Sample Development Wizard

A visual-first wizard for preparing eyewear **sample development** specifications for the factory.

## Live application

https://manuelother-ux.github.io/eyewear-development-wizard/

## Main capabilities

- English and Hebrew wizard UI with RTL support
- Visual frame, material, lens-curve and logo-method selectors
- Reference Manager with **Follow / Do Not Follow** instructions
- Frame, size, lens and component specifications
- Interactive logo/marking placement map
- Sample extras and special development instructions
- Local autosave in the browser
- English Sample Development Sheet
- Simplified Chinese Sample Development Sheet
- Print / PDF output
- Excel-compatible export
- Project JSON backup

## Scope

This application is intentionally limited to **sample development**. It does not manage bulk production, shipping, carton packing or mass-production QC.

## Factory defaults

Technical values that have not yet been confirmed as a Conchen factory standard are not invented. The user can leave them for **Development Team Recommendation**.

## Deployment

GitHub Pages deployment is handled automatically by `.github/workflows/pages.yml` on every push to `main`.

## App architecture

The deployed V1 is a dependency-free standalone web application in `index.html`. This makes it fast to deploy, easy to maintain and usable without a backend.
