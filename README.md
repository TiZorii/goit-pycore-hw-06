## Home task. Working with Files and Modular System

#### Task Description

> In this homework, we will continue developing our virtual assistant with a CLI interface.

Our assistant already can interact with the user through the command line, receiving commands and arguments, and executing the necessary actions. In this task, we will work on the internal logic of the assistant, on how data is stored, what data is stored, and what can be done with it.

> We will apply object-oriented programming for these purposes. First, let's define several entities (models) that we will work with.

The user will have an address book or contacts book. This contacts book contains entries. Each entry contains a certain set of fields.

Thus, we have described the entities (classes) that need to be implemented. Next, let's consider the requirements for these classes and establish their relationships, rules under which they will interact.

The user interacts with the contacts book by adding, deleting, and editing entries. The user should also be able to search the contacts book for entries by one or more criteria (fields).
About fields, it can also be said that they can be mandatory (name) and optional (phone or email, for example). Entries can also contain multiple fields of the same type (several phones, for example). The user should be able to add/remove/edit fields in any entry.
