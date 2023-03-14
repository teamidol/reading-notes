## **301 READING CLASS 03**

#### **REACT DOCS - LISTS AND KEYS**

* A *.map()* returns an array.

* To loop an array and display each value in JSX we'd have to have them as elements of list items.

* Each list item needs a unique *key.*

* A *key* is a special string attribute needed to include when creating a list of elements.

#### **THE SPREAD OPERATOR**

* *Spread operator* is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments.

* Spread operator can
1. add to an existing array
2. pass elements of an array as arguments to a function
3. copy arrays
4. concatenate arrays

* Combining 2 arrays.  

arr1 = [1,2,3];
arr2 = [4,5,6];
arr1 = [arr1, ...arr2];

* Adding object in an array.

const loneGuy = ['guy'];
const coolGrp = ['reece','ryans','audrey',...loneGuy];

* Combining 2 objects.

const object1 = {okie};
const object2 = {dokie};
const object3 = {...object1, ...object2};

#### **HOW TO PASS FUNCTIONS BETWEEN COMPONENTS**

* The first thing the developer in the video did to pass a function between components is to create a function.

* The *increment* provides an updated count when a person is clicked.

* A method can be passed from a parent component into a child component by *this.props.*

* The child component invokes a method passed from the parent component by *onClick.*

:thinking: ## Things I want to know more about. 