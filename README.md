# GerDraCor (German Drama Corpus, in TEI-P5)

We're rebuilding our German Drama Corpus here. So far, we've been working with an
[intermediary format](https://github.com/dlina/project/tree/master/data/zwischenformat)
to conduct [our research](https://dlina.github.io/talks/). This format only holds
structural information, not the texts themselves, which is why we do the rebuilding.

By now, the 465 files we took from the TextGrid repository have been structurally cleaned
(too many non-semantic DIV wraps, etc.). We're now working on getting all IDs right and
will enhance character information in the ```particDesc``` section (gender info, etc.).

Btw, the 666 dramas contained in the TG repo can be found [here](https://github.com/DLiNa/project/tree/master/data/textgrid-repository-dramas)
in their unaltered state. The 201 files we didn't integrate in our corpus yet
because they didn't fit our criteria (no fragments, and only plays from 1730–1930),
will be reintegrated later, too.

(This Readme was updated on Aug 4, 2017.)
