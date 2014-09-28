When faced with the question, 'is this code any good?', even professional programmers will typically stare blankly. What do we mean by 'good code'?

There are endless opinions on standards for good code (see [this talk](http://figshare.com/articles/What_Makes_Good_Code_Good_for_Science_/832498) from the Software Sustainability Institute), but they all get at the same three basic concerns:

 - **Performance - Does it do what it was intended to do?** All code *does* things. Does your code do what it was supposed to? To answer this, three things must be examined:
  - Is it clear what this piece of code was supposed to do?
  - What exactly does this piece of code actually do (in all circumstances)?
  - Are the answers to the above two questions consistent with each other?
 - **Consistency - Does it fit within the project well?** Adding new code to a project is like adding new ingredients to a recipe; you have to examine whether they work together well, or you'll end up with chocolate covered turkey. This means:
  - Does the new code mess up the operation of any of the existing code?
  - Does the new code unnecessarily duplicate the abilities of the rest of the code?
  - Does the new code accomplish things that make the rest of the code better (ie does this code *belong*)?
 - **Clarity - Is it as simple as possible?** Haphazardly slapping bits of code together is a bit like stacking rocks - eventually, the whole thing is going to fall over, if you're not careful. Unclear code can destroy the longevity of a project. Good code should:
  - Follow any patterns found in the rest of the code, so it's easy to read and follow.
  - Be clearly but concisely documented, so new contributors (or you a couple months from now) can quickly learn about what this code does.
  - Does things in as simple steps as possible - this means small functions that each do one thing well.

Some of these questions can be very simple and mechanical, while others are abstract, open ended, and can take over your life if you aren't careful. It turns out, that these questions and the process of reviewing code can be likened to the more familiar exercise of proofreading and editing a piece of writing; in two gross stages:

 - **Check for mechanical mistakes** You'd never send a paper off to the reviewer full of spelling mistakes - in the same way, we can identify a set of simple things to check for that are clearly right or wrong in a piece of code, that should be straightened out before the code is ever submitted for review.
 - **Check for deeper quality** With i's dotted and t's crossed, the paper can go off to the reviewer, whose job it is to examine the finer points in your writing; do all the arguments actually follow logically? Is the evidence presented properly handled and relevant? Does the analysis and conclusion actually address the opening hypothesis? While these are complicated questions, setting up a checklist of things to look for can simplify the process, and speed it up - the same is true when examining code.

In the next few lessons, we'll learn how to set these standards, and perform code reviews quickly and easily.
