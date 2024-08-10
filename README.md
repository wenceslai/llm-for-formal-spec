# Synthetic LTL data generation

Unfinished research project that was supposed to fine tune LLMs to translate natural language into formal specifications in Linear Temporal Logic (LTL)

Because there is lack of training data for this problem I created a code that randmly grows tree with LTL symbols according to LTL syntax.

These formulas can be translated into "pseduo natural language" e.g. ~(a V b) into "it's not true that a holds or b holds".

I then try to augument the pseudo language with GPT to get more realistic training data.
