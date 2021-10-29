# Rhyming Words Mostly
Word lists organized by rhyming according to spelling of end of word

These lists are constructed by grepping through a dictionary of words for certain spellings of word endings. Therefore, these mostly rhyme but are not guaranteed to - each list may have some outliers.

## Source of words
All the words in this repository came from the ```american-english``` dictionary from the [SCOWL/ASPELL package](http://wordlist.aspell.net/). This package was provided in the Linux distro I use at ```/usr/share/dict```

Before categorizing the words into rhyming groups, I made a good-faith attempt at removing profanity, racial slurs, and other offensive language from the above-mentioned dictionary word list. See credits for sources of offensive words I used as filters. However, there is no guarantee that all offensive language is filtered out, and that also depends in part where you draw the line over what is offensive. Therefore, use at own risk; you are responsible for applying your own filters.

## How the rhymes were generated
Rhyming sets were generated via ```grep```, based on the spelling of the end of the word.

## Credits
- `american-english` dictionary from the [SCOWL/aspell package](http://wordlist.aspell.net/) via the standard Debian package manager. See also [https://metadata.ftp-master.debian.org/changelogs//main/s/scowl/scowl_7.1-1_copyright](https://metadata.ftp-master.debian.org/changelogs//main/s/scowl/scowl_7.1-1_copyright)

Words used for filtering out offensive language were sourced from the following:
1. [Banned Word List](http://www.bannedwordlist.com/)
2. [List of Ethnic Slurs](https://en.wikipedia.org/wiki/List_of_ethnic_slurs)
3. [List of Common Nouns Derived From Ethnic Group Names](https://en.wikipedia.org/wiki/List_of_common_nouns_derived_from_ethnic_group_names)
4. [List of LGBT-related slurs](https://en.wikipedia.org/wiki/List_of_LGBT-related_slurs)
5. I also filtered based on some words I thought of, many of which were not offensive per se but could be read the wrong way if put in a certain context. 
