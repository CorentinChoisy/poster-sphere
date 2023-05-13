# Poster SPHERE

Forked from https://www.overleaf.com/latex/templates/poster-template-for-nottingham-centre-for-geomechanics/tmpkbjdnxwrr

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

2. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

3. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

4. Run `make` to build your poster

