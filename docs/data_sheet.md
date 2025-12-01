Data set name: PMST Lamkang

Data set developer(s): Jonathan Reich, Sandra Auderset

Data sheet author(s): Jonathan Reich, Sandra Auderset

Others who contributed to this document: Shobhana Chelliah, Rex Rengpu Khullar


# Motivation

**For what purpose was the dataset created?**

This data set was created to investigate the dynamics of person marking in Lamkang and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. (in prep).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.
This Lamkang dataset consists of data published by the following research team in this journal article:
Chelliah, Shobhana L., David A. Peterson, Tyler P. Utt, and Evaline Blair. 2019. “Lamkang Verb Conjugation.” Himalayan Linguistics 18 (1): 8-25. doi.org/10.5070/H918143199

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.


# Composition

This Paralex dataset documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Lamkang, it is a version of the community orthography used by speakers.

**How many instances are there in total?**

-   Number of inflected forms: 298

-   Number of unique inflected forms: 169

-   Number of unique scenarios (person, number, TAM, polarity combinations): 158

-   Number of inflected forms per paradigm and subparadigm:

| **Paradigm** | **n** | **Tags**           | **n** |
|--------------|------:|--------------------|------:|
| Pronouns     |     6 | default            |     6 |
| NFUT.AFF     |    91 | default            |    38 |
|              |       | past               |    37 |
|              |       | past, opt.pl       |     1 |
|              |       | unspec.var         |    11 |
|              |       | unspec.var, past   |     2 |
|              |       | sociolect.var      |     2 |
| NFUT.NEG     |    94 | default            |    36 |
|              |       | past               |    37 |
|              |       | opt.pl             |     2 |
|              |       | past, opt.pl       |     1 |
|              |       | unspec.var         |    12 |
|              |       | unspec.var, past   |     6 |
| FUT.AFF      |    61 | default            |    38 |
|              |       | unspec.var         |    22 |
|              |       | unspec.var, opt.pl |     1 |
| FUT.NEG      |    46 | default            |    38 |
|              |       | unspec.var         |     4 |
|              |       | unspec.var, opt.pl |     4 |


**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: lamk1238

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**

The data was taken primarily from published sources. The data presented there was collected in the state of Manipur, Chandel district.

**Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 

The dataset contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the dataset (see below for explanation).

**Is any information missing from individual instances?** 

No.

**Are there any errors, sources of noise, or redundancies in the dataset?** 

No.

**Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)?** 

The dataset is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this dataset to those of the vocabularies (eg. inexact language code) ?**

NA

**Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The dataset pertains to small or indigenous language communities, namely those of the Lamkang people in Manipur.
The data are taken from published sources.


# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other datasets ?** 

The data comes primarily from published sources. Some forms were checked and/or elicited with native speaker Rex Khullar. Segmentation was based on the published sources but adjusted to our design principles by Jonathan Reich.

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**What is the expertise of the contributors with the documented language ?** 

Jonathan Reich: linguist specializing in South-Central Trans-Himalayan morphosyntax

Rex Khullar: native speaker and community language documenter

Shobhana Chelliah: linguist and specialist in South-Central Trans-Himalayan languages

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 

Please consult the published sources for details.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**

All forms were collected from speakers. See above.

**How were the phonological or phonemic transcriptions obtained?** 

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes, the underlying data of the published sources is partially archived and available at CORSAL (https://digital.library.unt.edu/explore/collections/SAALT/).

**Is the software that was used to preprocess/clean/label the data available?** 

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the dataset been used for any published work already?** 

Yes, the underlying data was used in Chelliah et al. 2019 (see sources.bib).

**What (other) tasks could the dataset be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the dataset should not be used?**

No.


# Distribution.

**Will the dataset be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the dataset was created?**

No.

**How will the dataset be distributed (for example, tarball on website, API, GitHub)?** 

The dataset is available on GitHub at X and on Zenodo as part of the Paralex collection at X.

**Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 

The dataset is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?** 

For suggestions or error reports please open an issue on GitHub.