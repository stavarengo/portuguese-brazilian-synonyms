# Portuguese Brazilian Synonyms
Creditis to [http://www.nilc.icmc.usp.br/tep2/index.htm](http://www.nilc.icmc.usp.br/tep2/index.htm) from where I got the original files.

## Details about layout-one.txt
`sequential_number. [category] {comma separated synonyms} <ID of the antonyms in the same file>`

**Example:**
> 1. [VERB] {word1, word2, word3, word4} <200>

This line says: 
 1. This set of words is identified by the number 1.
 2. All of theses four words are verbs.
 3. They are all synonyms of each other.
 4. All the words in this set is antonym of all the words in the set of words 200. (But all the words in the set 200 is synonyms of each other as expected)

## Details about layout-two.txt
`[category] verb_one KIND_OF_RELATION_TO verb_two`

**Example:**
> [ADJECTIVE] word1 SYNONYMOUS_OF word2

This means that "word1" is an ADJECTIVE and that it is a synonym of "word2".

## Categories
1. OTHER
2. ADJECTIVE
3. NOUN
4. VERB
5. ADVERB

## List of KIND_OF_RELATION_TO
1. SYNONYMOUS_OF
2. ANTONYM_OF
