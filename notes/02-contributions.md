Code review is fastest and easiest when clear standards are set beforehand. There are three crucial reasons for this:

 - Clear standards communicate your expectations to your contributors.
 - Once code is written, it is very tempting to assume it's probably okay. Standards defined up front suppress this bias, much like in TDD.
 - A clear scope of standards gives you a checklist to work through when doing code review, so the process has a well defined end - otherwise, you can sit there wondering if the code is 'good' forever.

When a contributor comes to a project, one of the first things they should see is instructions on how to make a contribution, and included in these instructions should be a checklist of things that absolutely must be true before making a pull request. Good things to put on this list are *mechanical* aspects of your coding standards - things that the contributor can check for with a high degree of clarity and low degree of subjectivity. Some popular examples:
 - Code must merge automatically
 - All tests must pass
 - All new code must be tested in the test suite
 - Code must compile
 - No functions longer than n lines (I usually use a pretty loose n = 200, but I've seen as little as n = 50)
 - Code must have an entry in the documentation
 - Code must obey the style guide *clearly defined and linked here*.

 Or whatever other conditions you'd like to impose on contributions before they even arrive. The key here, is that the contributor guidelines should politely but firmly indicate that you should NOT send a code contribution until all these conditions are met. This stops you from having to slog through the same simple mistakes over and over again, and will save you a lot of time; if you ever receive a piece of code that fails to satisfy one of these standards, you are well within your rights to reject it immediately.

Another excellent best practice for contributions, is requiring the contributor to write a clear but concise description of what their new contribution is supposed to be / change / do, and include it with their pull request. This will help speed up your review process, once you accept a submission for deeper consideration. Also, ask your contributors to cut-and-paste the contribution guidelines checklist into their comments, and indicate that they are all complete; this encourages people to examine the list carefully, and lets you know quickly when someone didn't read the instructions *at all*.
