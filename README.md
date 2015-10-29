## The Predication Project

This repo contains work relevant to RSA models of predication.

### Existant predication models

| Model			| Subject		| Predicate | Features |  
| --- | --- | --- | --- | --- |
| [Gradable adjectives](http://forestdb.org/models/adjectives.html) | single object | gradable adjective | infer threshold |  
| [Plural predication](http://forestdb.org/models/plural-predication.html) | plurality | gradable adjective | infer interpretation |
| [Generics](https://github.com/mhtess/generics) | category | property | coerce to threshold semantics |
| [Hyperbole](http://forestdb.org/models/hyperbole.html) | single object | gradable adjective | infer state and valence |
| [Metaphor](http://forestdb.org/models/metaphor.html) | single object | nominal | infer speaker goal |
| [Scalar implicature](http://forestdb.org/models/scalar-implicature.html) | ?? | property | alternative utterances |
| [Irony](http://forestdb.org/models/irony.html) | single state | property | infer valence and arousal |

#### Types of entities

- Real-world objects (*the boxes are heavy*)
- Categories (i.e., kinds) of real-world objects (*boxes are heavy*)
- States (*it's raining*)
- Events (*that was quick!*)

All of these may be either singular or plural.

#### Types of referential expressions

(from [Kehler 2015](http://onlinelibrary.wiley.com/doi/10.1002/9781118882139.ch20/summary))

- Indefinite *a*: Congress passed *a bill* today
- Indefinite *this*: Congress passed *this bill* today (you won't bleieve what's in it)
- Definite *the*-NP: *The bill* cuts tazes for the middle class
- Familiar *that*: Congress passed *that bill* today [spoken discourse-initially]
- Demonstratives: *That bill* was pretty bad, but *this one* is downright awful
- Pronouns: Congress finally passed *it* this afternoon
- Proper names: Congress ousted *Boehner* last week

All of these may be either singular or plural.

#### Types of predicates

- Verbs: John *ran*
- Adjectives: John is *stupid*
- Gradable adjectives: John is *tall*

Predicates may ascribe **binary properties**, **gradable properties**, participation in **events**, or **generic** information.


### Semantic composition

Some options in the composition of meaning

#### Treat predicates as such

- A predicate takes its subject as an argument (via **Functional Application**)

#### Treat predicates as properties; privilege predication

- We need a special **predication** relation to do the work for us




