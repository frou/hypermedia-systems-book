This fork of the book's repo is modified to help me successfully build the PDF.

# Notes

* Libertinus fonts from [here](https://github.com/alerque/libertinus/releases) have been added to the `./fonts` directory.
* In `lib/definitons.typ`, `#let mono-font = ...` has been changed to `SF Mono` because I don't have (and am not interested in) `Berkeley Mono`.
* In `lib/style.typ`, a tweak has been applied for compatibility with newer versions of Typst (tip from [here](https://github.com/bigskysoftware/hypermedia-systems-book/issues/33#issuecomment-3092147702)).

# Instructions

1. Install `just` and `typst` (e.g. from Homebrew).
2. Run `just build-pdf` from the root of this repo. This should result in `./HypermediaSystems.pdf` being built, with no errors/warnings.
