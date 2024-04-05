# JavaScript 2 Practice Assessment - Coding Portion

Welcome to the second practice assessment!

The coding portion of this practice assessment continues to test your
understanding of basic JavaScript.

Your objective is to implement the functions in the __problems__ directory so
that all specs pass. Each spec is worth 1 point.

You will have **2 hours and 40 minutes** to complete the practice assessment
(including the multiple choice portion).

## Points breakdown

* __Multiple Choice Section:__ 9 points total
* __Coding Problem Section:__ 8 points total

__Total Possible Points:__ 17 points

## Resources

For this assessment, you are allowed to use the following resources:

* [MDN]
* A whiteboard or paper to work out problems/code, but they must be within
  camera range
* VScode or a console for testing and experimentation during any part of the
  test, including multiple-choice questions
* Node
* Postman (when useful)

You are **NOT** allowed to refer to any other resources, including--but not
limited to--other websites (e.g., AA Open, StackOverflow), communication apps
(e.g., Slack, Discord), search engines, notes, or any of your previously
written code.

## Setup

1. Clone this starter repo and open it in VS Code.
2. Run `npm install` in the root directory.
3. Run `npm test` to see all the specs you need to pass.

## Running the specs for individual problems

To run specs for only a single problem, add the path of the test file that
corresponds to the problem you want to test. For example, to test the function
in the __problem/03-shopping-list.js__ file by itself, you would run `npm test
test/03-shopping-list-spec.js`.

Here are the commands to run each of the five test files individually:

```sh
npm test test/01-key-adder-unique-val-spec.js
npm test test/02-dupe-char-min-count-spec.js
npm test test/03-shopping-list-spec.js
npm test test/04-picky-my-map-spec.js
npm test test/05-filter-user-profiles-spec.js
npm test test/06-sentence-maker-spec.js
```

## Submission (ONLY FOR ACTUAL ASSESSMENT)

> The following are the submission instructions for the actual assessment. They
> will not work for submitting the practice assessment but are printed here so
> you can familiarize yourself with them.

When you are ready to submit:

1. Run `npm test` to re-run all of the unit tests.

2. Fix any syntax errors that cause the tests to crash. **If a unit test crashes
   or the tests fail to complete their run, you will receive a 0 for the coding
   portion of this assessment.** You can fail specs, but all the tests have to
   be able to finish running.

   **Tip:** If you run out of time to debug, just comment out any code that is
   causing your programs to crash.

3. Add, commit, and push your changed files:

   ```sh
   git add .
   git commit -m "Finish the assessment (or some such descriptive message)"
   git push
   ```

   **Note:** The first time you run `git push`, git will tell you to run a more
   complete version of the command:

   ```sh
   git push --set-upstream origin <your branch>
   ```

You can run tests, `add` files, and `commit` files as often as you wish, but
only your first **two pushes** will be graded. (If for some reason you need more
than two pushes, you must plead your case to an Instructor.)

[MDN]: https://developer.mozilla.org/en-US/
