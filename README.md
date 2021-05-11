# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.


**Assement update!**



**Decorator**
**•	what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example**
o	Decorator design pattern tends to add more dynamics to the feature implementation.
o	Say for example, you have a function named “calloverphone” -> Without Decorator and “calloverphonewithringtone” is with decorator. 
o	Here the function “calloverphonewithringtone” extends the function “calloverphone” with an attribute say “ringtone”
**•	how the pattern works, what the basic idea of the pattern is**
o	This pattern basically works by adding new behaviors to the object by placing the new attribute within the objects dynamically. 
**•	what the main advantage and what the main disadvantage is of using this pattern**
o	Advantage : Its Dynamic and pretty cool to see since its result oriented
o	Disadvantage: Complex coding!
**•	Write a short summary :**
o	As a developer/Tester I use Decorator to enhance dynamic feature to my work product to improve the user experience. This pattern shall be used to improve the work product behavior with your coding skills and approach



**Interpreter**
**•	what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example**
o	Interpreter are widely used while working across different compiler sets to code.
o	Say for example, a piece of code is written which asks for user inputs, and the user input can vary multiple languages or spells. You shall have an interpreter integrated in your environment which makes the needed conversion to process the next actions. This can also be with number types or it can also be with build definitions, code optimizations...Etc in actual use cases.
**•	how the pattern works, what the basic idea of the pattern is**
o	Interpreter pattern is a solution oriented design which analyzes and provides definite and tested solutions for a problem statement. 
o	One can define the rule and implement it as interpreter and use it in the software.
•	what the main advantage and what the main disadvantage is of using this pattern
o	Easy to create
o	Difficult to maintain every extensions made
**•	Write a short summary :**
o	The work product shall use the interpreter if a specific feature is requested by the customer for code optimizations, compiler optimizations etc.,
o	Specific Language conversion, ASCII to binary conversion, in such use case also the interpreter shall be used.



**Memento pattern**
**•	what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example**
o	Memento Design pattern is used when complex result oriented product is built.
o	Say for example you own a continuous Testing environment and you want to reproduce an issue which was seen in older code change. Here, you can try to go back to any snapshots, to view and perform the activity.
o	History is preserved and updated. Also if any unintended changes are pushed this class works as Undo the changes or rollback
**•	how the pattern works, what the basic idea of the pattern is**
o	Memento Pattern works with create->Save->Restore->(Undo If requested) 
PS: I am explaining these concepts completely as a leman example without technical terms!  I hope this is fine!
**•	what the main advantage and what the main disadvantage is of using this pattern**
o	Provides flexibility to the coder
o	Its slow, time consuming
**•	Write a short summary :**
o	One shall use the Memento pattern when complex algorithm has to be met. When Many contributors to the feature this shall be implemented. History graph usage and rollback feature are incorporated in this pattern!



**Proxy**
**•	what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example**
o	Proxy as the word means having a replica (Duplicate) of your function/product or anything buildable.
o	For example, say you are a component owner and your component is in continuous delivery environment. SO any changes you make if you have a proxy environment, push it there check the behavior and then flow to actual component.
**•	how the pattern works, what the basic idea of the pattern is**
o	Create a real work product
o	Create a Proxy work product
o	Develop on work product
o	Deliver to Proxy work product
o	Verify 
o	All Good?
o	Then, Deliver to real work product! :)
**•	what the main advantage and what the main disadvantage is of using this pattern**
o	Build developer trust, acts as test suit
o	You need to maintain two components/product etc..,
**•	Write a short summary :**
o	If the work product is under deployment or strict validations or many stake holders, it is always best to have a quality instance to verify the change before final Delivery to the production instance of work product.
o	In such scenario’s I shall implement the proxy pattern


