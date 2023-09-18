# Hindi_to_Hinglish

# Problem Statement:
We need to translate the sentence from English to Hinglish (Hindi + English).

# Aim:
In that translation,the non-native Hindi speaker should also understand it. So it should be natural and elegant.

# Libraries used:
We have used spaCy for Natural language processing and Translator for the translation.

# How it works?:
***
  1. We have the spaCy English language model ("en_core_web_sm"). This NLP model helps used to filter out the nouns from the input sentence.
    why to filter out the nouns?
      ~ In parts of speech nouns are the first one and easiest one of all. If you can read the noun(person,place or thing). There is a high probability that the person can understand the sentence easily.
  2. We are also translating sentence to Hindi ("hi"), split the input sentence into words, and initialize an empty list to store translated words.
  3. Now we have nouns in one hand and translated sentence which is stored in a list as words in another hand.
  4.We will start a loop that iterates through each word in the input sentence, If a word is found in the nouns list, it is added to the translated_words list as is. If it's not a noun, it is translated into Hindi using the translator object, and the translation is added to the translated_words list.
  5. We will put back the translated words into a single sentence
  6. We will get our required output.
***


<img width="1512" alt="Screenshot 2023-09-19 at 3 23 21 AM" src="https://github.com/ramkumar-mv/English_to_Hinglish/assets/86485511/d245decd-ebfb-43bd-96cf-e08f038bf887">

[Source:] (https://pressbooks.pub/roughwritersguide/back-matter/writing-for-non-native-speakers/)
