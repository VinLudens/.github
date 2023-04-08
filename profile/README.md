# Welcome!

I am [VinLudens][VL] and this is my GitHub account/organisation which focusses around music related topics. The majority of my work here consists of the [LilyPond](http://lilypond.org/) source files for my sheets. [GitHub Actions](https://docs.github.com/en/actions) are used to automatically compile and release (on GitHub) the sheets. In that regard, consider this a sort of archive.

LilyPond for music is essentially what [LaTeX](https://www.latex-project.org/) is for written works. I have my workflow in combination with [Neovim](https://github.com/niveK77pur/nvim "my neovim configs") and [nvim-lilypond-suite](https://github.com/martineausimon/nvim-lilypond-suite "A neovim plugin for writing LilyPond scores").

# Organization

## Music Sheets

As it stands, there are 4 classes to which I assign my sheets; the following should help you navigate the repositories.

- [ARR-xxx](https://github.com/orgs/VinLudens/repositories?q=ARR-&type=all&language=lilypond&sort=name) contain sheets for my full-fledged piano ***ARR**angements*/covers.
- [QA-xxx](https://github.com/orgs/VinLudens/repositories?q=QA-&type=all&language=lilypond&sort=name) hold sheets for my ***Q**uick **A**rrangements*, which are of less high calibre.
- [OC-xxx](https://github.com/orgs/VinLudens/repositories?q=OC-&type=all&language=lilypond&sort=name) are all my ***O**riginal **C**ompositions*.
- [MISC](https://github.com/orgs/VinLudens/repositories?q=MISC-&type=all&language=lilypond&sort=name) account for ***MISC**ellaneous* works, most of which are dropped projects. I will take the liberty to rename these projects if the need arises.

Wherever a recording is available, the corresponding repository contains a link to my [YouTube][VL] video. Also, each music sheets repository has *Releases* containing the LilyPond output files. Sharable [jsDelivr](https://www.jsdelivr.com/) links can be found in the `release-assets` branch of these repositories (files in this branch always reflect the latest release).

## GitHub Actions

- [lilypond-reusable-workflows](https://github.com/VinLudens/lilypond-reusable-workflows) attempts to refactor and abstract the workflows' main logic and make them re-used by each [music sheets](#music-sheets) repository.
- [lilypond-workflow-template](https://github.com/VinLudens/lilypond-workflow-template) is the template repository for the music sheets with all the GitHub Actions set up (makes use of the reusable workflows).

## Other

- [VinLudens](https://github.com/VinLudens/VinLudens) A special repository whose README appears in the profile (the one you are reading right now!)

[VL]: https://www.youtube.com/@VinLudens
