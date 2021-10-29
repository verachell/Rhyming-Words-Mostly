# Rhyming Words Mostly
English word lists organized by rhyming according to spelling of end of word

These lists are constructed by grepping through a dictionary of words for certain spellings of word endings. Therefore, these mostly rhyme but are not guaranteed to - each list may contain some outliers which have a similar spelling but are pronounced differently.

## Source of words
All the words in this repository came from the ```american-english``` dictionary from the [SCOWL/ASPELL package](http://wordlist.aspell.net/). This package was provided in the Linux distro I use at ```/usr/share/dict```

Before categorizing the words into rhyming groups, I made a good-faith attempt at removing profanity, racial slurs, and other offensive language from the above-mentioned dictionary word list. See credits for sources of offensive words I used as filters. However, there is no guarantee that all offensive language is filtered out, and that also depends in part where you draw the line over what is offensive. Therefore, use at own risk; you are responsible for applying your own filters.

## How the rhymes were generated
Rhyming sets of word lists in plain text format were generated from the abovementioned words via ```grep``` on Linux. The grep command involved the spelling of the end of the word, with examples and naming conventions as shown below.

### Examples
The ```Ong.txt``` list contains words ending in 'ong'. 

The ```AmeAim.txt``` list contains words ending in 'ame' and words ending in 'aim'.

Certain rhyming lists were omitted from this repository for various reasons, for example:
```Ine.txt``` was omitted because many of the words within did not rhyme (e.g. pine vs magazine)
```Omp.txt``` was omitted because there were only a few words in that list
```IckIc.txt``` was omitted because many words did not rhyme (e.g. arctic vs aristocratic).

## Limitations
- This is not an exhaustive list of every possible set of rhyming sounds. I came up with the rhyming sounds used here manually, so there are certainly many sounds that I have not thought of yet. 

- Also, no attempt has been made to categorize the rhyming words into parts of speech.

> To sum up, this repository should be considered a subset of mostly rhyming words in the English language.

## Credits
The words came from the `american-english` dictionary from the [SCOWL/aspell package](http://wordlist.aspell.net/) via the standard Debian package manager. See also [https://metadata.ftp-master.debian.org/changelogs//main/s/scowl/scowl_7.1-1_copyright](https://metadata.ftp-master.debian.org/changelogs//main/s/scowl/scowl_7.1-1_copyright)

Words used for filtering out offensive language were sourced from the following:
1. [Banned Word List](http://www.bannedwordlist.com/)
2. [List of Ethnic Slurs](https://en.wikipedia.org/wiki/List_of_ethnic_slurs)
3. [List of Common Nouns Derived From Ethnic Group Names](https://en.wikipedia.org/wiki/List_of_common_nouns_derived_from_ethnic_group_names)
4. [List of LGBT-related slurs](https://en.wikipedia.org/wiki/List_of_LGBT-related_slurs)
5. I also filtered based on some words I thought of, many of which were not offensive per se but could be read the wrong way if put in a certain context. 
