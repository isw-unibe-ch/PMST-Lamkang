# Person Marking in South-Central Trans-Himalayan: Lamkang

This PARALEX set contains person markers in Lamkang, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ
as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source\_form column in the forms file contains the data exactly as it appears with in the source. This may include a lexical verb stem (listed in lexemes). In the orthographic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Lamkang

* Tone: Lamkang has contrastive tone. In the orthography tone is not marked. In scholarly articles both accent marks (low tone is marked with a grave accent and high tone with an acute accent) and tone numbers are found. In the IPA representation, tones are represented with numbers (1 = low, 5 = high). Thus, tones are not always marked in the source materials and the analysis is not standardized across sources yet.
* Mapping between database paradigm labels and Lamkang descriptive labels:
Database label = Language-specific descriptive label
fut.aff = future affirmative
fut.neg = future negative
nfut.aff = nonfuture affirmative
nfut.neg = nonfuture negative
nfut.aff + "past" tag = past affirmative
nfut.neg + "past" tag = past negative
* Variation and tagging: In the source article Chelliah et al. 2019 lots of variation in forms for individual scenarios is listed (up to 5 different forms for one scenario). In those cases all forms but one are given in square brackets. Those latter forms reportedly represent "Observed variants" (Chelliah et al. 2019: 13). The nature of this variation is so far unclear. Therefore, all forms have been tagged as "unspecified". The only exceptions to this are two instances of clear sociolectal variation which are hence tagged as "sociolect\_var".





## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.



Chelliah, Shobhana \& Peterson, David A. \& Utt, Tyler P. \& Blair, Evaline \& Khular, Sumshot. 2019. Lamkang verb conjugation. Himalayan Linguistics 18(1). 8–25. (doi:https://doi.org/10.5070/H918143199)

