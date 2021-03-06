# Linting Meteor Projects

Linting your files means you check whether you meet the conventions you defined for your code. It's like doing a quality check.

There are several tools you can use to lint JavaScript code:

* [JSHint](http://jshint.com/)
* [JSCS](http://jscs.info/)
* [ESLint](http://eslint.org/)

They have slightly different approaches. They all have in common that they can check whether code adheres to certain quality or styles standards.

If you only wish to pick one, I'd recommend [ESLint](http://eslint.org/).

## Usage

### Prerequisites

Make sure that `npm` is available on your machine as all of these tools come as node packages.

### [JSHint](http://jshint.com/)

JSHint is a tool that helps to detect errors and potential problems in JavaScript code.

### Installation

Issue the following command inside a terminal:

`$ npm install -g jshint`

### Configuration

In order to use JShint you need a `.jshintrc file in the root directory. It can be used to configure [77 options](http://jshint.com/docs/options/).

In order to exclude files or directories from linting you can use a `.jshintignore` file.

### Linting

Inside the root directory of your project issue

`$ jshint . `

## [JSCS](http://jscs.info/) - JavaScript Code Style

JSCS is a code style linter for programmatically enforcing a style guide.

### Installation

Issue the following command inside a terminal:

`$ npm install -g jscs`

### Configuration

In order to use JavaScript Code Style (jscs) you need a `.jscsrc` file in the root directory. It can be used to configure [100 rules](http://jscs.info/rules.html).

In order to exclude files or directories from linting you can set the `excludeFiles` option to an array of files or locations.

### Linting

Inside the root directory of your project issue

`$ jscs . `

## [ESLint](http://eslint.org/)

### Installation

Issue the following command inside a terminal:

`$ npm install -g eslint`

### Configuration

In order to use ESlint you need a `.eslintrc file in the root directory. It can be used to configure [143 rules](http://eslint.org/docs/rules/).

In order to exclude files or directories from linting you can use a `.eslintgnore` file.

### Linting

Inside the root directory of your project issue

`$ eslint . `
