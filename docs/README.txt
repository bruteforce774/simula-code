================================================================================
SIMULA CHAPTER 9 CODE EXAMPLES
Object-Oriented Programming With Simula by Bjørn Kirkerud (1989)
================================================================================

This collection contains code examples extracted from Chapter 9: "Objects and 
Classes" of the classic Simula textbook.

CONTENTS
--------
1. Place.sim                    - Basic class with variables and procedures
2. Budget.sim                   - Class with arrays and multiple procedures
3. Country.sim                  - Class with parameters
4. Person.sim                   - Class with imperatives (initialization)
5. Point.sim                    - Class with reference parameters
6. Chord.sim                    - Class using other classes
7. Polygon.sim                  - Class with array of references
8. distant_corners.sim          - Procedure with reference parameters
9. reference_transmission.sim   - Examples of parameter transmission
10. reference_comparison.sim    - Reference equality examples
11. object_equality.sim         - Object value equality examples
12. object_copying.sim          - How to copy objects
13. inspect_examples.sim        - Using the inspect statement
14. class_hierarchy.sim         - Basic inheritance example
15. place_hierarchy.sim         - Practical inheritance hierarchy
16. inheritance_demo.sim        - Demonstrating inherited attributes
17. CONCEPTS_SUMMARY.txt        - Comprehensive concept summary

FILE NAMING CONVENTION
----------------------
All Simula source files use the .sim extension (common convention).

ABOUT SIMULA
------------
Simula (1967) was the first object-oriented programming language. It introduced
concepts that became fundamental to OOP:
- Classes and objects
- Inheritance
- Polymorphism
- Virtual methods
- Garbage collection

These concepts influenced all subsequent OOP languages including Smalltalk,
C++, Java, and C#.

SYNTAX NOTES FOR MODERN DEVELOPERS
-----------------------------------
If you're familiar with C++/Java/C#, here are key Simula syntax differences:

    Simula                      Modern Equivalent
    -------------------------   ---------------------------------
    ref(ClassName)              ClassName* or ClassName&
    :-                          = (for references)
    :=                          = (for values)
    ==                          == (identity check only)
    =/=                         !=
    none                        null/nullptr
    new ClassName               new ClassName()
    begin ... end               { ... }
    ! comment                   // comment
    procedure                   method/function
    class AA; ... end of AA;    class AA { ... }
    AA class BB; ...            class BB extends AA { ... }

Note: Some examples in this collection are code fragments that show syntax
and concepts rather than complete runnable programs.

LEARNING PATH
-------------
Recommended order for studying these examples:

Beginners:
1. Start with CONCEPTS_SUMMARY.txt for overview
2. Study Place.sim - simplest complete class
3. Study Budget.sim - adds arrays and multiple procedures
4. Study Person.sim - shows initialization
5. Study class_hierarchy.sim and place_hierarchy.sim - inheritance basics

Intermediate:
6. Study Point.sim, Chord.sim, Polygon.sim - reference parameters
7. Study reference_comparison.sim and object_equality.sim
8. Study inspect_examples.sim - the inspect statement
9. Study Country.sim - parameterized classes

Advanced:
10. Study reference_transmission.sim - parameter passing semantics
11. Study inheritance_demo.sim - detailed inheritance behavior
12. Study distant_corners.sim - complex reference manipulation

KEY CONCEPTS INTRODUCED
-----------------------
1. Classes as templates/patterns for objects
2. Objects as instances of classes
3. Attributes (data members and methods)
4. References (pointers to objects)
5. Object generation (instantiation)
6. Remote access (dot notation)
7. Inspection (temporary direct access to attributes)
8. Parameters to classes
9. Imperatives in classes (constructors)
10. References as parameters and return values
11. Reference vs. value equality
12. Subclasses and inheritance
13. Class hierarchies

AUTHOR'S NOTE
-------------
These examples are extracted from the 1989 textbook. Some conventions and
practices reflect the era in which they were written. Modern OOP has evolved
these concepts further, but the fundamentals remain the same.

The author, Bjørn Kirkerud, advised readers not to try to digest all concepts
at once, but to study examples and try exercises before mastering all theory.
This remains excellent advice!

================================================================================
Extracted and compiled by: Claude (Anthropic AI Assistant)
Edited by: Daniel Andreas Wang
Source: "Object-Oriented Programming With Simula" by Bjørn Kirkerud (1989)
Chapter 9: Objects and Classes (pages 229-251)
Year: 2025
================================================================================
