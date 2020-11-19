Support
If you're a user seeking support, here is our support site.

Developing Compatible Dapps
If you're a web dapp developer, we've got two types of guides for you:

New Dapp Developers
We recommend this Learning Solidity tutorial series.
We wrote a (slightly outdated now) gentle introduction on Developing Dapps soon.
Current Dapp Developers
If you have a Dapp, and you want to ensure compatibility, here is our guide on building compatible Dapps
Building locally
Install Node.js version 6.3.1 or later.
Install local dependencies with npm install.
Install gulp globally with npm install -g gulp-cli.
Build the project to the ./dist/ folder with gulp build.
Optionally, to rebuild on file changes, run gulp dev.
To package .zip files for distribution, run gulp zip, or run the full build & zip with gulp dist.
Uncompressed builds can be found in /dist, compressed builds can be found in /builds once they're built.

Running Tests
Requires mocha installed. Run npm install -g mocha.

Then just run npm test.

You can also test with a continuously watching process, via npm run watch.

You can run the linter by itself with gulp lint.

Architecture
Architecture Diagram

Development
npm install
npm start
Build for Publishing
npm run dist
Writing Browser Tests
To write tests that will be run in the browser using QUnit, add your test files to test/integration/lib.
