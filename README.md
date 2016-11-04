# cmudict-ipa
CMU Pronouncing Dictionary converted to IPA by Alexander Piperski

**cmudict-0.7b-ipa.txt** contains all the entries from the CMU Pronouncing Dictionary (version 0.7b; http://www.speech.cs.cmu.edu/cgi-bin/cmudict) automatically converted to the International Phonetic Alphabet (IPA). Each line consists of a headword and its transcription(s) separated by a tab symbol; variant forms are separated by ", ".

Examples:

- ALPINE  ˈælˌpaɪn
- APPALACHIAN ˌæpəˈleɪtʃən, ˌæpəˈleɪʃən, ˌæpəˈlætʃən
- HIMALAYAN ˌhɪməˈleɪən, ˌhɪməˈlaɪən

Apart from the standard Arpabet to IPA conversion rules (https://en.wikipedia.org/wiki/Arpabet), the following ones were observed:

- AH is converted to ʌ when bearing primary stress and to ə otherwise (AH1 -> ʌ; AH0, AH2 -> ə)
- Vowel length is indicated (AA -> ɑː, ER -> ɝː, IY -> iː, UW -> uː). However, unstressed word-final ER and IY are short (i.e., ER0 -> ɝ and IY -> i when word-final).

**brown-frequency-list-with-ipa.txt** contains 33862 words occurring in the Brown Corpus of American English (https://archive.org/details/BrownCorpus) sorted by their frequency of occurrence. This list may be of use to English learners willing to pronounce most frequent words correctly.
