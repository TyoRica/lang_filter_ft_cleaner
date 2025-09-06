# lang_filter_ft_cleaner
language filter for cleaning datesets.
# Language Filter (FastText)

A lightweight script to filter datasets by language, using **fastText** language identification.

## Features
- Uses [fastText lid.176 model](https://fasttext.cc/docs/en/language-identification.html)
- Configurable allowed language (default: English `"en"`)
- Filters datasets and removes non-target languages

## Example
```bash
python lang_filter.py
