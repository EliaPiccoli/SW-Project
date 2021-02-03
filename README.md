# Semantic Web Project 2020/2021

The fundamental concepts in an application domain related to *narratives* (intended as stories about a specific topic) are: *events*, *characters*, *objects* and *locations*.
Some of the facts that characterise this domain can be stated as follows:
1. A narrative is composed of one or more events.
2. A narrative is composed exclusively of events.
3. Each event occurs in exactly one location and has exactly one beginning and one ending, both represented as a datetime using the appropriate XSD datatype.
4. A character can be human or not human.
5. Each location can be a real location or a fictional location.
6. Each character, each location and each object have a name (a string).
7. Each event has at least one participating character or object.
8. Each narrative is created by at least one narrator.
9. The narrator has at least one contract with a publisher.
10. A book reports one or more narratives.
11. A book has a title (a string) and it is identified by an ISBN code (a string).
12. A book has exactly one publisher (that is an organisation).
The publisher is identified by a name (a string) and an ID (a positive integer).
13. A publisher publishes more than one book.
14. A book has exactly one price (a positive integer).
15. The publisher sells the books through more than one bookshop.