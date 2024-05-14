---
layout: post
category: python
---

What is the Python data model?
It is essentially a framework for interacting with the building blocks of the Python language. 
I had some serious trouble finding a point of reference to understand the python data model. Each time I tried to come up with a good explanation the concept eluded me leaving me with a big questionmark. I knew how to adhere to some rules and what makes my code 'interact' with the python data model (namely special methods or syntactic sugar) but I still could not explain the concept of the data model. While writing and thinking more about the concept of the data model I realized that the syntax of python is like the vocabulary of the language. You can make yourself understood by speaking certain words and phrases like in a normal human spoken language. But if you want to truly understand a language and speak like a native, you need to understand the grammar, the culture, proverbs and certain combination of words to sound like a native. These things are somewhat the equivalent to the Python Data Model.
The Data Model is the way the python language is modeled. It's Data types and structures, how objects are defined and how the interpreter treats things.

For effectively using Python one must have a certain level of knowledge of the data model the language is built upon. 

I think I still have a very limited understanding of the Data Model. Till know I suppose it is fundamental to get a good grasp of the built-in data types, sequences and special methods. 

Special methods lets the Python interpreter work with our own classes as if it was interacting with built in data types of the language. Special methods otherwise known as dunder methods (double underscore) or magic methods, are implemented in our classes. They are always declared specifically and with leading and trailing double underscores. The names of the special methods are chosen from a list of possible methods in regard to the needed function or supported language perk. 

All python keywords or how the interpreter works with certain phrases have special methods under the hoods. For example accessing an element in a list via square brackets is implemented via the special method __ getitem __ . Through the implementation of the dunder getitem method an object also allows for looping through the element. There are many more special methods to use and which usage I will not and also am not able to explain in this blog post. But understanding what the Python Data model is is also very useful in understanding the Python documentation.

Python is an object oriented programming language and the data model is the how it is an object oriented programming language.