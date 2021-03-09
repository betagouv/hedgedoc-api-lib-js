HedgedocApi
=========

Simple library wrapper around basic hedgedoc/codimd commands

Compatible and tested against HedgeDoc 1.7.2.

It contains a HedgedocApi Class with fhe following methods: 

- getNoteWithId
- createNewNoteWithContent
- createNewNoteWithContentAndAlias

The class is expecting email, password, and url in the following order as parameters
```
const ha = new HedgedocApi(email, password, url);
```

where email and password are identification params of an account, and url the base url where is running hedgedoc/codimd.
