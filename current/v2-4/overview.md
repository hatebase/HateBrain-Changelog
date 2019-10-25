# HateBrain v2.4

~~~
Deployed October 2019
~~~

## Features

### Variable sensitivity

Although certain terms with ambiguous meanings have previously been prevented from passive automated search, [API queries](https://github.com/hatebase/Hatebase-API-Docs) have included these terms in resultsets. This can still be accomplished, but requires a specific API input parameter, which means that most resultsets will increase in accuracy by excluding terms with a high likelihood of false positives.

### Improved detection of clinical usage

Additional exclusion parameters have been added to detect terms used in an apparently clinical or analytical manner, including detection of quotations.

### Anti-pilotfish

Certain ambiguous terms can now be eliminated as false positives if accompanied by words which are statistically likely to NOT indicate a hate speech context. So in a sense, this is the application of our pilotfish methodology in reverse. An example would be: if "pussy" is accompanied by "cat", it probably doesn't indicate a disparaging reference to the female anatomy.

### Authorship bug fix

A bug in the previous version of HateBrain occasionally generated false positives when the screen name of a post's author was erroneously detected. This bug has been fixed.
