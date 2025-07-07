# TKLTA Core 100

This repository contains **TKLTA Core 100**, a multilingual collection of short sentence sets compiled by Talkalotta. Each CSV file holds around one hundred examples for a specific language or dialect. The data is useful for studying common sentence structures and everyday conversation across languages.

## Dataset structure

The corpus consists of files named `TKLTA_<CODE>_100.csv`, where `<CODE>` identifies the language. Every file uses comma‑separated values with a header row followed by about 100 entries. The columns are:

- `Category` – the type of example. Typical categories include:
  - **Grammar Core** – sentences illustrating key grammar or verb tenses
  - **Conversational Data** – snippets of natural dialogue
  - **Paraphrased & Augmented Sentences** – alternative phrasings and variations
- A second column containing the sentence text in the relevant language.

Some files use native scripts or region‑specific orthographies. Lines may not be strictly normalized, so minor formatting differences are expected.

## Licensing

All data forms part of the **Talkalotta Corpora** and is released under the [Creative Commons Attribution‑ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). You are free to share and adapt the material as long as you provide appropriate credit and distribute your contributions under the same license. See the [`LICENSE`](LICENSE) file for the full terms.

When redistributing or reusing this data, please include a credit such as:

> "**TKLTA Core 100 – <language code>** by **Talkalotta**, part of the Talkalotta Corpora, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)"

## Repository contents

- Multiple `TKLTA_<CODE>_100.csv` files containing the sentence data
- [`LICENSE`](LICENSE) – license text and attribution guidelines
- [`README.md`](README.md) – this overview file

## Contributing

Corrections and improvements are welcome. By submitting a pull request you agree that your contributions will be shared under the same CC BY-SA 4.0 license.

## Citation

If you make use of this dataset in research, consider citing it as:

```
Talkalotta. *TKLTA Core 100* [Data set]. CC BY-SA 4.0.
```

---

This dataset is provided "as is" without warranty. It is intended for language learning, linguistics research, and natural language processing experiments.
