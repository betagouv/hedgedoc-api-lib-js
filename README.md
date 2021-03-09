pad
=========

Simple library wrapper around basic hedgedoc/codimd commands

It contains a Pas Class with fhe following methods: 

- getNoteWithId
- createNewNoteWithContent
- createNewNoteWithContentAndAlias

The class is expecting email, password, and url in the following order as parameters
```
const pad = new PAD(email, password, url);
```

where email and password are identification params of an account, and url the base url where is running hedgedoc/codimd.
