Chaining selector (no space) e.g .class.second-class
Descendant combinator (the empty space) e.g .class .second-class
Child combinator e.g .class > .second-class
When comparing selectors, you may come across special symbols for the universal selector (*) as well as combinators (+, ~, >, and an empty space). These symbols do not add any specificity in and of themselves.

An 'id' specificity is higher then class, and class is higher than a type selector

Inheritance refers to certain CSS properties that, when applied to an element, are inherited by that element’s descendants, even if we don’t explicitly write a rule for those descendants. Typography based properties (color, font-size, font-family, etc.) are usually inherited, while most other properties aren’t.
The exception to this is when directly targeting an element, as this always beats inheritance.

Let’s say that after every other factor has been taken into account, there are still multiple conflicting rules targeting an element. Whichever rule was the last defined is the winner.