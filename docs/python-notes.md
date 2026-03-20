data model methods
    implement methods that are called upon by the framework
    -Special methods are called upon to perform basic operations
        -Special method names are written with leading and trailing double underscores __getitem__ (dunder)
        -Speicial method names allows your objects to interact with and use basic language contstructs such as iteration, collection, attribute access, operator overloading, functions and methods, object creation and destruction, string representation and formatting, managed contexts (within blocks)
    Pythonic Card Deck
        -use of collections.namedtuple constructs a class that represents individual objects as bundles of attribrutes with no customer methods.
        - use of __getitem__ speicla method allows for iteration and collection etc. by initialising the self and reducing the need for functions that fulfil said purposes.
        -Whilst a class may give objects inherit functions, they are leveraged against the object using the data model and how it is composed. By implementing special methods, we hand off the work of language constructs to a list object.




object representation



clean naming


repr

str

immutability patterns

