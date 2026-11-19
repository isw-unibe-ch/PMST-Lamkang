Data set name: PMST Lamkang

Data set developer(s): Jonathan Reich, Sandra Auderset

Data sheet author(s): Jonathan Reich, Sandra Auderset

Others who contributed to this document: Shobhana Chelliah, Rex Rengpu Khullar


# Motivation

**For what purpose was the data set created?**

This data set was created to investigate the dynamics of person marking in Lamkang and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. 2026. Full citation: Auderset, Sandra \& Brown, Hunter L. \& Reich, Jonathan \& Gerber, Pascal \& Zakaria, Muhammad \& Konnerth, Linda. 2026. A Database of Person Marking in South-Central Trans-Himalayan. Journal of Open Humanities Data 12(1), 58. (doi:https://doi.org/10.5334/johd.505).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.
This Lamkang data set consists of data published by the following research team in this journal article:
Chelliah, Shobhana L., David A. Peterson, Tyler P. Utt, and Evaline Blair. 2019. “Lamkang Verb Conjugation.” Himalayan Linguistics 18 (1): 8-25. doi.org/10.5070/H918143199

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.


# Composition

This Paralex data set documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and/or phonemic sequences?**

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Lamkang, it is a version of the community orthography used by speakers.

**How many instances are there in total?**

* Number of inflected forms: 305
* Number of unique inflected forms: 176
* Number of unique scenarios (person, number, TAM, polarity combinations): 162
* Number of inflected forms per paradigm and subparadigm:

|paradigm |variants_tag  |paradigm_tag |overabundance_tag |  n|
|:--------|:-------------|:------------|:-----------------|--:|
|pron     |unspecified   |             |                  |  6|
|fut.aff  |unspecified   |             |optional_plural   |  1|
|fut.aff  |unspecified   |             |                  | 61|
|fut.neg  |unspecified   |             |optional_plural   |  4|
|fut.neg  |unspecified   |             |                  | 43|
|nfut.aff |sociolect_var |             |                  |  2|
|nfut.aff |unspecified   |pfv          |optional_plural   |  1|
|nfut.aff |unspecified   |pfv          |                  | 40|
|nfut.aff |unspecified   |             |                  | 50|
|nfut.neg |unspecified   |pfv          |optional_plural   |  1|
|nfut.neg |unspecified   |pfv          |                  | 44|
|nfut.neg |unspecified   |             |optional_plural   |  2|
|nfut.neg |unspecified   |             |                  | 50|


**Language varieties**

* BCP-47 language tag: NA
* Glottocode: lamk1238

**Does the data pertain to specific dialects, geographical locations, genre, etc?**

The data was taken primarily from published sources. The data presented there was collected in the state of Manipur (Northeast India), Chandel district.

**Does the data set contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?**

The data set contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the data set.

**Is any information missing from individual instances?**

No.

**Are there any errors, sources of noise, or redundancies in the data set?**

No.

**Is the data set self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other data sets)?**

The data set is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this data set to those of the vocabularies (eg. inexact language code)?**

NA

**Does the data set contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The data set pertains to small or indigenous language communities, namely those of the Lamkang people in Manipur.
The data are taken from published sources.


# Collection process

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any? Are any information derived from other data sets?**

The data comes primarily from published sources. Some forms were checked and/or elicited with native speaker Rex Khullar. Segmentation was based on the published sources but adjusted to our design principles by Jonathan Reich.

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**What is the expertise of the contributors with the documented language?**

Jonathan Reich: linguist specializing in South-Central Trans-Himalayan

Rex Khullar: native speaker and community language documenter

Shobhana Chelliah: linguist and specialist in South-Central Trans-Himalayan languages

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?**

Please consult the published sources for details.


# Preprocessing/cleaning/labeling

**How were the inflected forms obtained?**

All forms were collected from speakers (see above).

**How were the phonological or phonemic transcriptions obtained?**

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?**

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes, the underlying data of the published sources is partially archived and available on CoRSAL at https://digital.library.unt.edu/explore/collections/SAALT/.

**Is the software that was used to preprocess/clean/label the data available?**

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the data set been used for any published work already?**

Yes, the underlying data was used in Chelliah et al. 2019 (see sources.bib).

**What (other) tasks could the data set be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the data set should not be used?**

No.


# Distribution

**Will the data set be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the data set was created?**

No.

**How will the data set be distributed (for example, tarball on website, API, GitHub)?**

The data set is available on GitHub at https://github.com/isw-unibe-ch and on Zenodo as part of the Paralex collection at https://doi.org/10.5281/zenodo.17881855.

**Will the data set be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?**

The data set is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the data set, is there a mechanism for them to do so?**

For suggestions or error reports please open an issue on GitHub.