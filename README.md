# Wordlists

This is a set of word frequency lists that I find useful for learning languages.

* `pl_processed.txt` - This is from the opensubtitles.net 2018 list (https://github.com/hermitdave/FrequencyWords), processed against the SGJP dictionary (sgjp.pl)
* `pl_top_1000_with_conjugations.txt` - This is the top 1000 words from the above list, with all conjugations/declensions
* `rs_processed.txt` - This is from the opensubtitles.net 2018 list (https://github.com/hermitdave/FrequencyWords) processed against ParCoLex (https://github.com/aleksandra-miletic/serbian-nlp-resources)

## Why word frequency dictionaries?

Word frequency dictionaries are a fantastic resource for language learning. If you can learn the most commonly use 1,000-2,000 words in a language then you can hold a basic conversation in a wide range of situations. The simplest way to build one of these is to take a large corpus of text (books, movie subtitles, magazines, transcripts of radio/TV shows), and count every word you find.

## When an apple is not an apple

In a language like English, this is a fairly simple task. There isn't a lot of morphology as there are no genders, minimal use of cases, and simple verb conjugation. That means we can find where the word "look" is used in the following sentences:

* Look at me!
* He looks at her
* I looked at her
* She looked at me
* We are looking at him
* I would look

Nouns and adjectives are also easy, take the word "car" for example

* We are at the car
* I like cars
* I am thinking about my car
* We drove my car to your house

With other languages, this isn't so easy, slavic languages in particular. Take Polish for example. The word "look" is "patrzeć", let's see how it conjugates:

* Patrz na mnie!
* On patrzy na nią
* Patrzyłem na nią
* Ona patrzyła na mnie
* Patrzymy na niego
* Patrzyłbym

Lots of work to unwind these. Remember in the english example, we count the word "look", "looks", "looked", and "looking", and these are the only 4 ways to conjugate the word "look". In Polish there are a few more:

* niepatrzenia
* niepatrzeniach
* niepatrzeniami
* niepatrzenie
* niepatrzeniem
* niepatrzeniom
* niepatrzeniu
* niepatrzeń
* niepatrząca
* niepatrzące
* niepatrzącego
* niepatrzącej
* niepatrzącemu
* niepatrzący
* niepatrzących
* niepatrzącym
* niepatrzącymi
* niepatrzącą
* patrz
* patrzcie
* patrzenia
* patrzeniach
* patrzeniami
* patrzenie
* patrzeniem
* patrzeniom
* patrzeniu
* patrzeń
* patrzmy
* patrzono
* patrzy
* patrzycie
* patrzyli
* patrzyliby
* patrzylibyście
* patrzylibyśmy
* patrzyliście
* patrzyliśmy
* patrzymy
* patrzysz
* patrzyć
* patrzył
* patrzyła
* patrzyłaby
* patrzyłabym
* patrzyłabyś
* patrzyłam
* patrzyłaś
* patrzyłby
* patrzyłbym
* patrzyłbyś
* patrzyłem
* patrzyłeś
* patrzyło
* patrzyłoby
* patrzyłobym
* patrzyłobyś
* patrzyłom
* patrzyłoś
* patrzyły
* patrzyłyby
* patrzyłybyście
* patrzyłybyśmy
* patrzyłyście
* patrzyłyśmy
* patrzą
* patrząc
* patrząca
* patrzące
* patrzącego
* patrzącej
* patrzącemu
* patrząco
* patrzący
* patrzących
* patrzącym
* patrzącymi
* patrzącą
* patrzę

So this complicates things. We have the same problem with nouns and adjectives. In the above example, we have the word "car", and its plural "cars". In Polish we have the following:

* samochodach
* samochodami
* samochodem
* samochodom
* samochodowi
* samochodu
* samochody
* samochodzie
* samochodów
* samochód

It gets worse - you need to guess things from context. The word "list" means letter, and "lista" means list. The genitive plural of "lista" is "list" though... so the sentence "mam list" means "I have a letter", but "nie mam list" means "I don't have lists"... For examples like this, I've not bothered to be too clever, but others are more important. The word "mnie" translate as "me", but it is also the word for "crimp". "On mnie mnie" means "he crimps me" - not a sensible sentence, but should be obvious from the context. In cases like this, I've chosen to use keep the word "mnie" translating to "me" and override the verb conjugation.

The lists of exceptions for each wordlist are in the `exceptions/` folder

## You can count on me

How do we build a list of the top 1,000 Polish words then? If we count words as we find them, we still get a very good list, but we end up with a bunch of duplicates in there. Hermit Dave's work on compling these lists is very useful and much appreciated though - they're great on their own, but a bit of tweaking can make them even better. What I've done with my list is used the base frequency list, converted the words to their root words. These lists are a work in progress, but I'll release more as my confidence grows.

## Get in touch

If this is something you're interested in working with or contributing to then let me know - I'm a huge fan of word frequency lists as a language tool, and have used them to learn German and Polish, and am currently using one to learn Serbian (more on this at www.slowserbian.com).

