# Yet Another Pig Latin Converter

### Converts strings into pig latin

Exposes a single function, `changePhrase`, that accepts a string argument, and returns a pig-latinised string.

Examples:

    var pigLatin = reqiure('yapiglatin').changePhrase;
    
    console.log(pigLatin('test')) // esttay
    console.log(pitLatin('Hello World')) // ellohay orldway
    
### Todo:

  - non-english characters
  - hyphenated words and other punctuation
  - are there any situations where 'y' counts as a vowel?
  - how to handle silent consonents at the beginnings of words
  - capitalised characters
