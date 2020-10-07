# Contributions to DictionaryHTM

## File Name
The name starts with a capital letter.
One word per file.
For instance : `[FIRST-LETTER]/[Word].htm`

## File Path
Add the word to an existing folder corresponding to the starting letter of the word or create a folder for the word or language.

## HTML File 

The file must contain 3 keys

```
word: Your word 
```

``` 
definitions: One or more definitions
```

``` 
parts of speech: 
One of the following 8 parts of speech the word belongs to 
Noun 
Pronoun
Verb
Adverb
Adjective
Preposition
Conjunction
Interjection 
```

## Example file (Word with one definition) 

<!DOCTYPE html>
<html>
<head> 
<link href="en.css" rel="stylesheet">
</head>
<body>
<div>
<h2> YourWord </h2>
<h4> Defenition </h4>
<p> Example : Example </p>
<p> <i> Parts-of-speech </i> </p>
</div>
</body>
</html>


If the word you want to add is requested in an issue, leave a comment on the issue claiming that you are adding that word. This minimizes conflicts and time wasting.
