# Reg-expressions-guide

Regular expressions reference guide

A Regular Expressions or \(regEx\) as referenced in this guide, is a description of a pattern of characters, strings, letters or symbols. The examples used here have all been tested using this [online resource](https://regex101.com/ "Online regex tester"). Head over there and learn by doing.All the examples can be found [here](https://regex101.com/library/OyXLME).

---

## Below is a reference of metacharacters and their meaning

* **The dot\(.\) **- Any character. It represents only one character. This metacharacter is will match anything `b. ` will match anything following the letter b, ie ` bi , be ` but not `beg`  you want to match more than one character like any two characters after b, use the `b..` .

* **The range \[  \]** - match any character within the range. **p\[aeoui\]d** will match any word which starts with letter p, has one vowel and ends with letter d. **G\[1-5\]** will watch anything that has G followed by any number between 1-5. G\[1-59\] will match G followed by any number between 1-5 or 9 i.e 1,2,3,4,5,9. Notes only one character within the range is matched.

* **The caret \[^ \]**  - Match character not within the range. The caret in this case is metacharacter, which represents any character not within the range characters provided. Using the previous example, **p\[^aeoui\]d **adding a caret will match anything starting with the letter p followed by any letter that is not within the range i.ea consonant, then the letter d. The following are just a few matches, pgd, ptd, ppd, pdd.

* **The multiplier \***  - Match a character certain number of times, Zero or more times. In the first metacharacter we covered, . \(the dot\), if you want to match more than one any character, you would add dots representing the number of characters which can be tedious, **\*** to your rescue. b.\* , would match any number of any characters after letter b.  
* **The +** - Match one or more times.
* **The ?**  -  Match zero or one time
* **The {N}**  - Match _**N** _times
* **{P, Q}**  - Match _**P-Q**_ times



