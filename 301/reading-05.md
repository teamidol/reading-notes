## **301 READING CLASS 05**

#### **REACT DOCS - THINKING IN REACT**

* *Single responsibility principle* is a technique that follows in having a component ideally only do one thing. And if it grows, it should be decomposed  into smaller subcomponents.

* *Static* version of an app is the version where it renders a data model in which to build on components that reuse other components and pass data using props.  

* Once the static application is built, interactivity can be added using components and props.

* If answer to question is "yes," then it's not a *state.*
1. Does it remain unchanged over time?
2. Is it passed in from a parent via props?
3. Can you compute it based on existing state or props in your component?

* To identify where a state needs to live....
1. Identify every component that renders something based on that state.
2. Find their closest common parent component—a component above them all in the hierarchy.
3. Decide where the state should live...common parent, above parent, or new component above common - parent solely for holding the state.

#### **HIGHER-ORDER FUNCTIONS**

* "Higher-order functions" are functions that operate on other functions, either by taking them as arguments or by returning them.

* return a boolean if m is greater or less than n.

* A *map* or *reduce* function operates as higher-order functions by producing new results from arrays produced by other functions. Perhaps there's array that's filtered by a filter function. A *map* function can further produce modified contents of the filtered array.



:thinking: ## Things I want to know more about. 