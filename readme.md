<img src="square-logo.svg" width=200 height=200 align="right">

This repository contains some example components meant for educational/inspirational
purposes. These are components that we open source to encourage experimentation but
these are components that are **not officially supported**. There will be some tests
as well as some documentation but this project should be considered a community project,
not something that is part of core Rasa.

# Documentation

You can find the documentation for this project [here](https://rasahq.github.io/rasa-nlu-examples/).
# Components

The following components are implemented.

### Meta

- `rasa_nlu_examples.meta.Printer`: a printer that's useful for debugging

### Dense Featurizers

- `rasa_nlu_examples.featurizers.dense.FastTextFeaturizer`: pretrained fasttext embeddings [link](https://fasttext.cc/)
- `rasa_nlu_examples.featurizers.dense.BytePairFeaturizer`: pretrained byte-pair embeddings [link](https://nlp.h-its.org/bpemb/)
