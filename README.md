# hibiscus_dict_data
Datasets for the Hibiscus Korean Dictionary App

Hibiscus Korean Dictionary (槿花辭典 · 근화 사전) is an offline Korean dictionary for Android, made by The Coldscholar Studio. This repository is the public home of its dictionary data and of its privacy policy.

## The dataset

The app's dictionary is an adaptation of the four works listed below. It reformats, cleans and merges them into SQLite databases. The adapted data is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International licence](LICENSE) (CC BY-SA 4.0).

**Coming with version 1.** The dataset is not here yet. It will be published as a release asset of this repository with the app's first release: the base database and the five definition-language packs (Chinese, Japanese, Vietnamese, French and Spanish), each with its sha256. The files are built from that release, so they match the data the app ships.

## Sources

- **Korean Basic Dictionary (한국어기초사전)** by the National Institute of Korean Language (국립국어원), [krdict.korean.go.kr](https://krdict.korean.go.kr), licensed under [CC BY-SA 2.0 KR](https://creativecommons.org/licenses/by-sa/2.0/kr/). The headwords, definitions, examples, pronunciations and conjugated forms, and the equivalents in English and the five pack languages. Reformatted, cleaned and merged with the sources below. Audio, images and video are not included.
- **English Wiktionary** by Wiktionary contributors, [en.wiktionary.org](https://en.wiktionary.org), licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), as extracted by [kaikki.org](https://kaikki.org) (wiktextract, Tatu Ylonen). Words marked "Wiktionary", Hanja readings, and some Hanja forms. Selected and reformatted.
- **CC-KEDICT** by Masato Hagiwara and contributors, [github.com/mhagiwara/cc-kedict](https://github.com/mhagiwara/cc-kedict), licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). TOPIK 1 vocabulary tags.
- **Unihan Database** © Unicode, Inc., [unicode.org](https://www.unicode.org), under the [Unicode License v3](https://www.unicode.org/license.txt). English meanings and sounds for some Hanja characters.

The app marks which source each entry's content comes from. The release will carry the full text of each source's licence, including the Unicode License v3's copyright and permission notice.

## Using the data

Under CC BY-SA 4.0 you may share and adapt the dataset for any purpose, including commercially, on these terms:

- **Attribution.** Credit the sources above and this dataset, link to the licence, and indicate whether you made changes.
- **ShareAlike.** If you remix, transform or build on the data, distribute your contributions under the same licence.
- **No additional restrictions.** Do not apply legal terms or technological measures that restrict others from doing anything the licence permits.

[LICENSE](LICENSE) holds the full legal code, and it governs.

## Privacy policy

The app's privacy policy is [PRIVACY_POLICY.md](PRIVACY_POLICY.md), with a Korean translation in [PRIVACY_POLICY.ko.md](PRIVACY_POLICY.ko.md); the English text governs. The app bundles these same files and shows them offline. The policy gives the address for privacy questions.
