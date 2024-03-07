List of naming standards
- Naming Style
- Grammatical Structure
- Verb Phrase
- Dictionary Terms
- Full Words
- Idioms and Slang
- Abbreviations and Acronyms
- Prefix/Suffix
- Length

#### Naming Style
```cpp
getFullName();
getScriptState();
call_with_default();
garbage_collection();
getfullName(); // bad
getscriptstate(); //bad
```
Popular styles:
camelCase and under_score

Little difference in cognitive load during comprehension

pretty equivalent except that camleCase appears to have a slight advantage

#### Grammatical Structure
``` cpp
registerManagedResource();
managedResourceRegister(); // bad
// verb phrase
drawContentBorder();

// verb phrase with a prepositional phrase
performTesttsFromZipFile();


```

- Functoin names with multiple words need to have grammatically correct sentence strctures

#### Verb phrase
```cpp
manage_cahcing_sizes();

computeProductBlockingSizes()

get_cahced_node();

x_cached_node(); //bad
```

Not only grammtically correct but contain a verb

functions are actions

Dictionary terms
```cpp
findLength();

abcdeg(); //bad

cccc(); //bad

aa2020(); //bad
```

Words used in function name are actualy dictionary terms
Meaningul natural-language terms

2 -> "to"

Limit length to 1 to 5 words

