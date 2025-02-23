## My resume generator

Github runner is autimatically runs pipeline which generates CV.

Latest Resume is available [here](https://n1md7.github.io/resume)

Only thing you need to do is modifying `RESUME.md`. Everything else happens magically :) 

### How to use locally?

1. Clone/fork the repo
1. Run `npm install`
1. Modify RESUME.md
1. ~~Run `npm run generate`~~ pre-commit hook automatically generates it

It will replace old RESUME.pdf with the new one. 

There is a automated CI/CD which generates artifact automatically and downloadable content can be found under `Action`-s tab. Or even better - it's accessible via URL https:// kaeri-gg.github.io/resume/RESUME.pdf
