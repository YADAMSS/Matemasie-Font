# Matemasie-Font

[![][Fontbakery]](https://YADAMSS.github.io/Matemasie-Font/fontbakery/fontbakery-report.html)
[![][Universal]](https://YADAMSS.github.io/Matemasie-Font/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://YADAMSS.github.io/Matemasie-Font/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://YADAMSS.github.io/Matemasie-Font/fontbakery/fontbakery-report.html)
[![][Shaping]](https://YADAMSS.github.io/Matemasie-Font/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FYADAMSS%2FMatemasie-Font%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FYADAMSS%2FMatemasie-Font%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FYADAMSS%2FMatemasie-Font%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FYADAMSS%2FMatemasie-Font%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FYADAMSS%2FMatemasie-Font%2Fgh-pages%2Fbadges%2FUniversal.json

The Matemasie display typeface is inspired by  Adinkra symbol Mate Masie from the Akan people; an ethnic group from West Africa, primarily from Ghana and Cote d'Ivoire, with the name meaning “What I hear, I keep.” This symbol represents wisdom and knowledge.

The Matemasie font is a one font style. It will have the Google Fonts GF Latin Core character set, as well as a handful of African-specific characters. It is anticipated to have about 330–350 glyphs, but might have more later for Google Fonts.

Matemasie is designed by Adam Yeo

![Sample Image]([https://github.com/YADAMSS/Matemasie-Font/blob/f06b6bf683c3c8f166d39b6a6c9971d2edf5bd85/documentation/matemasie_cover.jpg](https://github.com/YADAMSS/Matemasie-Font/blob/89d1ea26d8eda5fec3d8eb942890aad463342b99/documentation/matemasie_image_cover1.jpg))
![Sample Image]([https://github.com/YADAMSS/Matemasie-Font/blob/f4bc06678658c105d84c881b201b212b025b5c7b/documentation/matemasie_cover2.jpg](https://github.com/YADAMSS/Matemasie-Font/blob/89d1ea26d8eda5fec3d8eb942890aad463342b99/documentation/matemasie_image_cover2.jpg))

## About

Adam Yeo is a graphic and type designer from Cote d’Ivoire currently based in France. He holds a Doctorate in Art and Design from Nanjing University of the Arts, China. Adam is currently working on developing a typeface for the Bété script within the  ANRT.
He has spoken at the Atypi 2021 All Over conference 2021 and published several articles about African scripts, symbols, and languages. Matemasie is his first Latin typeface.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://YADAMSS.github.io/Matemasie-Font.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**26 May 2021. Version 2.13**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
