# Documentation

Software programmers and developers like to write code but writing "documentation" for their code is considered a chore. This is easily discernable on the most popular code hosting service - Github, which has tons of open source software repo's but only a fraction of these are well-documented. The downside? Thanks to the lack of proper documentation within their codebase, many Free/Open Source Software (FOSS) projects struggle to find new contributors. And then there is the [bus factor](http://en.wikipedia.org/wiki/Bus_factor) that can halt a FOSS project in its tracks.

Lets say, a user wants to fix a bug but writing the code patch and testing it isnt enough. Inaddition to fixing the bug, she has to wade through your complex codebase to figure out what each function, class or module does. That seems quite unreasonable given that volunteers are after-all unpaid contributors who are trying to help fix things. 

Some points in favor of documentation:
- Code is always in a state of flux thanks to bugs, and documentation helps the next programmer get up to speed quickly.
- Documenting the design, API specifications, with code comments can help the team fix and ship the product quickly.
- Manual pages help the user as well as the programmer understand software features and use/fix them as intended.

### Documentation Generator Tools
There are quite a few free documentation generator tools to help programmers write software reference documentation and since the documentation written is part of the program code, it can be easily extracted by tools like [Doxygen](http://www.stack.nl/~dimitri/doxygen/index.html) and [Sphinx](http://sphinx-doc.org/). Wikipedia has a [comparision of document generators](http://en.wikipedia.org/wiki/Comparison_of_documentation_generators) list for reference. There also exist free online services to host your documentation - [ReadTheDocs](https://readthedocs.org/) is one such service that allows you to host your documentation as a git repo on github and create a nice UI for reading the documentation.

