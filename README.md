# corpus-extendum-vault-01

Storage for [Corpus Extendum](https://github.com/drsamonline/corpus-extendum), the public-domain library.

**State:** open · 26 books · 138 MB · cap 600 books / 2.5 GB

This repository holds book files and nothing else. There is no website here, deliberately: GitHub Pages caps a published site at 1 GB, and this vault is built to reach 2.5 GB. The library serves these files through jsDelivr and `raw.githubusercontent.com`.

## Layout

```
index.txt        plain-text catalogue of this vault — one line per book
manifest.json    the same, machine-readable
books/<slug>/    <slug>.pdf · <slug>.epub · <slug>.txt · cover.jpg · meta.json
```

`meta.json` in each folder is the authoritative record: title, author, translator, year, subjects, source URL, rights basis, file hash and text hash. Everything the library shows comes from these files.

## Do not edit by hand

Files arrive through the ingest script in the library repo. A sealed vault is read-only for good. If a record's rights basis is wrong, open an issue on the library — the fix is a commit to `meta.json` and one line removed from `index.txt`.

Every book here is public domain in India and the United States. Text from Standard Ebooks (CC0 editions), the Gutenberg mirror, or archive.org; PDFs typeset by us; covers as credited per record.
