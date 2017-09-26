## What is this?

I followed a guide about using NPM as a build tool. [This guide]("https://medium.com/javascript-training/introduction-to-using-npm-as-a-build-tool-b41076f488b0").

It includes setting up **mocha** with **should** and **jsHint**.

### Changes I made

*   I chose to use **esLint** instead of **jsHint**.
*   I am using the air-bnb style guide
*   Also added some rules to eslint to match my current skill level.
*   Added rules for typescript too.
*   created `.eslintignore` to ignore `node_modules/`, `lib/` and `public/` folders
*   Included **Babel** and **Babelify**, configured on `.babelrc`

### Where can I see the changes?

*   In the `.eslintrc.json`
*   there is comment in the `test.js` file to ignore that **should** is not being "used" (it is but not as a variable)
*   in the `package.json` file, look for **babelify** and **eslint**
*   the `app.ts` file has a rule to ignore class-methods-use-this eslint rule

### How to use this sample

*   First clone it, then do a `npm install`.
*   TypeScript stuff goes in `./src/typescript/app.ts` and gets compiled to `./lib/app.js`
*   JS stuff goes in `./client/js/myModule.js` and `./client/js/app.js` and gets compiled to `.public/js/bundle.js`
*   LESS stuff goes in `.client/less/style.less` and gets compiled to `.public/css/style.css`
*   If you need to compile more **LESS**, **TypeScript** or **JS** files be sure to change the build commands accordingly.
*   the `.gitignore` file already ignores `node_modules` and all folders used to place compiled stuff
*   `.eslintignore` also ignores folders used for compiled stuff
*   examine `.eslintrc.json` to review the **eslint** rules I set
*   examine `package.json` to see what commands can `npm run`
*   Have fun!

## Contributing

1.  Fork it!
1.  Create your feature branch: git checkout -b my-new-feature
1.  Commit your changes: git commit -am 'Add some feature'
1.  Push to the branch: git push origin my-new-feature
1.  Submit a pull request :D

## History

Version 0.1 (2015-05-23) - adding Devise and core Rails functionality
Credits

## License

##### The MIT License (MIT)

###### Copyright (c) 2017 Edmundo Sanchez

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
