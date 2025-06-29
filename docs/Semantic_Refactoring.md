Client: Agnia Sergeyuk, Jetbrains <agnia.sergeyuk@jetbrains.com>

In many agile projects, the source code provides the master
documentation of system functionality. When customers and users change
their minds, refactoring tools help to adjust the source code structure,
but one important documentation element can be neglected - the
identifier names of variables, types, classes, and functions. In early
versions of the code, these are usually clear and consistent. But after
months or years of change negotiation, the names themselves get muddled,
so that nobody can remember what has been agreed. Your task is to make a
semantic refactoring tool, probably based on LLM technology, that
updates all the identifier names in a code base, for internal
consistency and to ensure agreement with user interfaces, tutorials, and
contract documentation.