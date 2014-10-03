# Documentation

Software programmers and developers like to write code but many still consider writing "documentation" for their code as a chore. In large corporate teams, this work is outsourced to a team of technical writers, but smaller projects cannot afford this luxury. The lack of documentation is easily discernable on the most popular code hosting service - Github, which has tons of open source software repo's but only a fraction of these are well-documented. The downside? Thanks to the lack of proper documentation within their codebase, many Free/Open Source Software (FOSS) projects struggle to find new contributors. 

Lets say, a user wants to fix a bug but writing the code patch and testing it isnt enough. Inaddition to fixing the bug, she has to wade through your complex codebase to figure out what each function, class or module does. That seems quite unreasonable given that volunteers are after-all unpaid contributors who are trying to help fix things. And then there is the [bus factor](http://en.wikipedia.org/wiki/Bus_factor) that can halt a FOSS project in its tracks, leading to code decay.

Some points in favor of documentation:
- Software code is always in a state of flux thanks to bugs, and documentation helps the next programmer get up to speed quickly.
- Maintaining software for dependency hell is crucial due to the version churn, else your package may become obsolete and unusable.
- Documenting the design, API specifications, with code comments can help the team fix and ship the product quickly.
- Manual pages help the user as well as the programmer understand software features and use/fix them as intended.
- Proper documentation helps teach good programming practices to newbie programmers who will someday inherit the mantle of the lead/core developer of the FOSS project.



### Documentation Generator Tools
There are quite a few free documentation generator tools to help programmers write software reference documentation and since the documentation written is part of the program code, it can be easily extracted by tools like [Doxygen](http://www.stack.nl/~dimitri/doxygen/index.html), written in C++ and [Sphinx](http://sphinx-doc.org/), written in Python. They support other languages too and are easy to setup and use. Besides these two, there are many other generators and Wikipedia has nice list [comparing the features of each document generator](http://en.wikipedia.org/wiki/Comparison_of_documentation_generators) for your reference. 

Now that you have created documentation, you would need to host it somewhere for your community users. If you find it a hassle to create, host and maintain a website only for documentation, fear not, there exist free online services that will host your documentation - [ReadTheDocs](https://readthedocs.org/) is one such service that allows you to host your documentation as a git repo on github and even creates a nice UI theme for reading the documentation. 

