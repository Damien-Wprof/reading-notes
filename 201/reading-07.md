# Reading 07

This topic matters because it reinforces what we learned in this class, constuctors are an important tool in any web devs toolkit and essential part in JS knowledge.

## Domain ModelingLinks to an external site.

1. Explain why we need domain modeling.

    We use domain modeling to understand the problem before we write our code, to help us understand what the problem is comprised of and what data those properties need.
    Domain modeling reduces bugs, rewrites and confusion because you design it before you write it.

## HTML Table BasicsLinks to an external site.

1. Why should tables not be used for page layouts?

Tables should be used for data and not layout because they hurt accessibility, readability and maintenance, it also mixes structure with presentation.
This also confuses screen readers.


2. List and describe 3 different semantic HTML elements used in an HTML <table>.

    <thead>
        The head of the table.
    <tbody>
        The body of the table.
    <tfoot>
        Footer of the table.

## Introducing ConstructorsLinks to an external site.

1. What is a constructor and what are some advantages to using it?

    A constructor is a special function used to create objects with the same structure. instead of writing the same object repeatedly, we use constructors.

2. How does the term 'this' differ when used in an object literal versus when used in a constructor?

    In an **object literal**, `this` refers to the object the method is called on, while in a **constructor**, `this` refers to the new instance being created by the `new` keyword.


## Object Prototypes Using A ConstructorLinks to an external site.

1. Explain prototypes and inheritance via an analogy from your previous work experience.

    The object you are creating with inherit from the constructor.

### NOTE: This is a very common front end developer interview question
