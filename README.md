# PressNotePropagation

## Sequence of running scripts:

* `converter.py`
* `runner.py`
* `tagger.py`
* `translator.translate_tags.py`
* `cluster_tagged.py`

```Bash
CLIENT_ID=... CLIENT_SECRET=... python -m translator.tests.test_translate_tags
```

```Bash
python -m translator.translate_tags tags tags_translated
````

## Results

[Results in jupyter notebook](jupyter/press%20notes.ipynb).
