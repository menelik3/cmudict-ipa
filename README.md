# cmudict-ipa
CMU Pronouncing Dictionary converted to IPA by Alexander Piperski

cmudict-0.7b-ipa.txt includes all the entries from the CMU Pronouncing Dictionary (version 0.7b; http://www.speech.cs.cmu.edu/cgi-bin/cmudict) automatically converted to the International Phonetic Alphabet (IPA). Each line contains a headword separated by a tab symbol from its transcription(s); variant forms are separated by ", ".

Examples:

- ALPINE  ˈælˌpaɪn
- APPALACHIAN ˌæpəˈleɪtʃən, ˌæpəˈleɪʃən, ˌæpəˈlætʃən
- HIMALAYAN ˌhɪməˈleɪən, ˌhɪməˈlaɪən

Apart from the standard Arpabet to IPA conversion rules (https://en.wikipedia.org/wiki/Arpabet), the following ones were observed:

- AH is converted to ʌ when bearing primary stress and to ə otherwise (AH1 -> ʌ; AH0, AH2 -> ə)
- Vowel length is indicated (AA -> ɑː, ER -> ɝː, IY -> iː, UW -> uː). However, unstressed word-final ER and IY are short (i.e., ER0 -> ɝ and IY -> i when word-final).
