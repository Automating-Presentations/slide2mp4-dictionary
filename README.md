# slide2mp4-dictionary
Dictionary text files for [slide2mp4](https://github.com/automating-presentations/slide2mp4).  

A dictionary file for slide2mp4 is a text file containing words and pronunciations, and the words and pronunciations must be separated by tabs or spaces. In a dictionary file, lines starting with "#" are recognized as comments.  

If you would like to extend this "slide2mp4-dic-XX.txt", run the following command. Please note that if the word and pronounciation in your lexicon file contain spaces and tabs, the spaces and tabs will be removed.

```
git clone https://github.com/automating-presentations/slide2mp4
chmod u+x slide2mp4/tools/*
./slide2mp4/tools/lexicon2dic.sh YOUR_LEXICON_FILE slide2mp4-dic-XX.txt
```
