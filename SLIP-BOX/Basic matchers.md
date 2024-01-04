---
tags: type/note
aliases: null
lead: Regex basic string matchers
created: 2023-08-24T12:17
modified: 2023-07-28, 12:51
template-type: Note
template-version: "1.7"
updated: 2023-08-27T12:48
---

# Basic matchers

Tags: #regx 
Date: 2023-07-28, 12:51

---

The absolute basic matcher, as is shown in [Regex type system](Regex%20type%20system.md) is just a simple **word** that the sentence contains. Another essential thing is picking the whole sentence, this can be useful when manipulating the text afterwards, here is an example:

```regex
/./g 
```

Then there are the character sets. This means that you can chose multiple words that differ, for example, in one character only for this we use *[some charaters her]*. Here is and examaple, fuck:

```regex
/ b[abcd]r /g
```

Then there is fucking string negation ahhhhh. This means that the string will not be included. Its done using *[^]*. Notice that you can combine this with the previous example. Exmaple bitches:

```regex
b[^eo]r
```

Then there is a way to include a rang of letters. For this we use *-*. Common this is basic shit I don't need to explain this to you. Exaampleee:

```regex
[e-o]
```

There is more. For now you are in lessen nine of regexlearn

## Personal attachment 

This is the essential basic shit, if you don't know it you are screwed and your time is more like shit in the sewer.


## References

[Learn regex](https://regexlearn.com)

[Personal knowledge management](Personal%20knowledge%20management.md)