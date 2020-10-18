# Distributed Language Database Schema

At the moment, this repository contains XML schemas necessary for keeping
consistency between language repositories within
[Zonal Constructed Languages Development Group](https://github.com/z-langs).

The current schema definitions are in "proof of concept" stage to raise
discussions and stimulate cooperation between developers working on
constructed zonal languages.

* [synset.xsd](xml/synset.xsd) - XML schema definition for storing
[synsets](https://en.wikipedia.org/wiki/WordNet), being a compromise option:
readable enough by humans, machine-processable and consumable by Git version
control system.
* [entry.xsd](xml/entry.xsd) - XML schema definition for storing vocabulary
entries with their metadata, morphology, phonology and other grammatical
attributes. It **does not** include any semantic information about the words.

**Do not rely on this schemas prior to `1.0.0` version release.**
