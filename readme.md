## What is this?

I followed a guide about using NPM as a build tool. [This guide]("https://medium.com/javascript-training/introduction-to-using-npm-as-a-build-tool-b41076f488b0").

It includes setting up **mocha** with **should** and **jsHint**.

### Changes I made

*   I chose to use **esLint** instead of **jsHint**.
*   I am using the air-bnb style guide
*   Also added some rules to eslint to match my current skill level.
*   Added rules for typescript too.
*   created .eslintignore to ignore node_modules/, lib/ and public/ folders
*   Included **Babel** and **Babelify**, configured on .babelrc

### Where can I see the changes?

*   In the .eslintrc.json
*   there is comment in the test.js file to ignore that **should** is not being "used" (it is but not as a variable)
