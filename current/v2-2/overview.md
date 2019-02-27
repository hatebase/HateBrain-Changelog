# HateBrain v2.2

~~~
Deployed February 2019
~~~

## Features

### Insults and threats

In addition to xenophobic references and general intensifiers, HateBrain now also recognizes multilingual insults and threats as unique categories of pilotfish.

### "Other terms"

While the previous version of HateBrain listed the first of any additional hate speech terms, this version lists all additional terms found.

### Increased probability for multiple additional terms found

While the previous version of HateBrain increased probability a single time if any additional hate speech terms were found, this version increases probability with each additional term found.

### Pilotfish detection even when no hate speech

If no hate speech terms are found, HateBrain will still do a preliminary scan for possible pilotfish to assist in general content moderation.

### Reduced scoring for terms with high likelihood of multiple meanings

Detected terms which have a high likelihood of duplicate or multiple meanings (e.g. "queen") will no longer automatically increase their probability when accompanied by pilotfish, since this imbues false confidence that the term is hate speech (e.g. "fucking queen"). The only exception to this rule is when the pilotfish found is a xenophobic reference, since this is considered unambiguous enough to imply that the term is being used in a hate speech context.
