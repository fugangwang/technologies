## SQLite


|          |        |
| -------- | ------ |
| title    | SQLite |
| status   | 95     |
| section  | TBD    |
| keywords | TBD    |




SQLite is an open source, embedded relational database. Originally
released in 2000, it has outstanding performance in terms of
portability, ease of use, compactness, availability, and
reliability [@www-sqlite].

SQLite has an exquisite, modular architecture and has introduced some
unique methods for relational database management. It consists of eight
independent modules organized in three subsystems [@www-sqlite-archi].
This model divides the query process into several discrete tasks, just
like working on the assembly line. The query is compiled at the top of
the architectural stack, executed in the middle, and the operating
system's storage and interfaces are processed at the bottom.
