[![License: LGPL](https://img.shields.io/github/license/fsanzl/silabeador)](https://opensource.org/licenses/LGPL-2.1)
[![Version: 1.0.2-15](https://img.shields.io/github/v/tag/fsanzl/silabeador)](https://pypi.org/project/silabeador/)
[![Python versions: 3.5, 3.6, 3.7, 3.8, 3.9](https://img.shields.io/pypi/pyversions/silabeador)](https://pypi.org/project/silabeador/)


<h2 align="center">Fonemas</h2>
<h3 align="center">A Python phonologic transcription library for Spanish</h2>


*fonemas* is a Python library of methods and functions for phonologic transcription of Spanish words.

This library is part of the research project [Sound and Meaning in Spanish Golden Age Literature](https://soundandmeaning.univie.ac.at/). Automatic verse scansion required identifying phonologic features that can be used using this library

## Instalation

```bash
pip3 install fonemas
```

## Use

The library provides the function transcribe. It takes a Spanish word  as a single argument and returns a list of strings that represent syllables in IPA format.


```python
>>> from fonemas import transcribe
>>> transcribe('Averigüéis')
['a', 'be', 'ɾi', "'guejs"]
```

## Description

The transcription is done according to the description of the Spanish phonology and phonotactics described by Quilis (2019).


## Contributions

Feel free to contribute using the [GitHub Issue Tracker](https://github.com/fsanzl/fonemas/issues) for feedback, suggestions, or bug reports.


## Licence

This project is under GNU LGPL 2.1 See [LICENSE](https://github.com/fsanzl/fonemas/LICENSE) for details.

## References

Quilis, Antonio, *Tratado de fonología y fonética españolas*. Madrid, Gredos, 2019.
