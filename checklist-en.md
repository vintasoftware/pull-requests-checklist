## 1. Pull request workflow
  * [ ] Read thoroughly the feature description to check if everything is implemented.
  * [ ] Run the code and use it as the end user would. Double check requested feature’s description.

## 2. Creating the pull request
  * [ ] Create Pull Request (but don't assign it yet).
  * [ ] Describe how to test the PR: urls, environment variables and other needs.
  * [ ] Refer to issue(s)/Trello card(s) the PR solves.
  * [ ] Refer back to the PR on Trello card(s).
  * [ ] Merge the target branch into the PR branch. Fix any conflicts that might appear.
  * [ ] Add screenshots of the new behavior, if applicable.
  * [ ] Add a description including the context and the chosen implementation strategy.
  * [ ] Explain code lines which the reviewer might not understand correctly:
    * Don't do it in the description, do it in the code itself as comments.
    * Consider refactoring and changing variable/function/method names to make it clearer.

## PR Self Review: 
#### Look for the following problems:

  * [ ] Code is not following code style guidelines (add links to your guidelines here when copying this checklist).
  * [ ] Bad naming: make sure you would understand your code if you read it a few months from now.
  * [ ] KISS: Keep it simple, Sweetie (not stupid!).
  * [ ] DRY: Don't Repeat Yourself.
  * [ ] YAGNI: You aren't gonna need it: check that you are not overcomplicating something for the sake of 'making it future-proof'.
    * PS: Fowler said "Yagni only applies to capabilities built into the software to support a presumptive feature, it does not apply to effort to make the software easier to modify".
  * [ ] Architecture errors: could there be a better separation of concerns or are there any leaky abstractions?
  * [ ] Code that is not readable: too many nested 'if's are a bad sign.
  * [ ] Performance issues (if that's a real concern for your application).
  * [ ] Complicated constructions that need refactoring or comments: code should almost always be self-explanatory.
  * [ ] Forgotten TODOs and noop lines: make sure they're mapped in your Trello/Issues board.
  * [ ] Grammar errors.
  * [ ] Continuous Integration errors, including tests and coverage (configure CI to send you an e-mail when tests are done).
  * [ ] If the feature needs regression tests, write them.
  * [ ] Other possible improvements (add to this Checklist if it's a general concept - it's open source!).
  * [ ] Once all problems are addressed, allocate the reviewer.

## Responding to feedback
  * [ ] If any problem hasn’t been addressed and the PR needs to be accepted ASAP, create new issues for remaining problems.
  * [ ] Respond all of the reviewer's comments ASAP:
    * Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.").
    * Don't take it personally. The review is of the code, not yourself.
    * Try to understand the reviewer's perspective.
  * [ ] Once you receive feedback and address all issues, merge and close the PR/branch.
