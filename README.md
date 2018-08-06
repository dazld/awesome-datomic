# awesome-datomic
Awesome Datomic and Datascript related resources.

## Contributing

Please do contribute, if you have something which you think is awesome! PRs welcome from everyone :)

## Officialish

- [Day Of Datomic Videos](http://www.datomic.com/training.html)
- [Day Of Datomic Code](https://github.com/Datomic/day-of-datomic)
- [mbrainz sample data](https://github.com/Datomic/mbrainz-sample)

## Libraries

- [Spirit](https://github.com/zcaudate/spirit). 'spirit provides a simple, intuitive data layer to access datomic using a document-based syntax, as well as a data-processing pipeline for fine-grain manipulation and access of data.'
- [Datomic-schema](https://github.com/Yuppiechef/datomic-schema). 'datomic-schema' makes it easier to see your schema without sacrificing features'
- [datofu](https://github.com/vvvvalvalval/datofu). 'theres a :db/fn for that'
- [Spec-tacular](https://github.com/SparkFund/spec-tacular). DSL over datomic with schema creation, core.typed aliases, transactions etc.
- [Spectomic](https://github.com/Provisdom/spectomic) - generate datomic schemas from specs
- [datomock](https://github.com/vvvvalvalval/datomock) - Mocking and forking Datomic connections in-memory.
- [umlaut](https://github.com/workco/umlaut) - Generate datomic (and gql, lacinia, etc.) schemas from a neutral format

## Articles

- [This is not the history you are looking for](http://vvvvalvalval.github.io/posts/2017-07-08-Datomic-this-is-not-the-history-youre-looking-for.html): discussion of timetravel feature in datomic in terms of application features vs debugging / development
- [Referentially Transparent Crud](http://cjohansen.no/referentially-transparent-crud/): discussion of referential transparency with CRUD operations
- [Querying across databases](http://cjohansen.no/querying-across-datomic-databases/): using multiple db values in queries
- [Annotating datomic transactions](http://cjohansen.no/annotating-datomic-transactions/): annotating (for example) audit information when transacting
- [Using datomic in your app, a practical guide](https://vvvvalvalval.github.io/posts/2016-07-24-datomic-web-app-a-practical-guide.html).
- [Application architecture with datomic - branching reality](https://vvvvalvalval.github.io/posts/2016-01-03-architecture-datomic-branching-reality.html)
- [Datomic Direct Index Lookup](http://augustl.com/blog/2013/datomic_direct_index_lookup/): explanation of how direct index queries can be faster
- [Using Datomic as a Graph database](https://hashrocket.com/blog/posts/using-datomic-as-a-graph-database): exploration of the classic n degrees of separation scenario with datomic

## Learning

- [Learn Datalog today](http://www.learndatalogtoday.org/)

## Snippets

- [Datomic news updates](https://gist.github.com/stuarthalloway/2948756): Update examples against a social news database
- [Transaction attribute functions](https://gist.github.com/favila/8ce31de4b2cb04cf202687c6a8fa4c94): Datomic transaction functions to "reset" attributes: i.e. make them have a post-transaction value you specify without having to enumerate the retractions.
