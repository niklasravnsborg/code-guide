# Code Guide

All code in any code-base should look like a single person typed it, no matter how many people contributed.

## General

* write **DRY** (Don't repeat yourself) Code
* do document and comment your code
* consistent naming scheme per language (further defined in the language guidelines)
* avoid deep nesting of code
* keep short line length

## Tabs versus spaces

* Use tabs for indenting to visualize your codes hierarchy
* Use spaces for indenting to align your code


**Tabs for hierarchy**
```javascript
function alertSomething() {
»   alert('Something!');
}
```

**Spaces for aligning**

```javascript
var foo = '',
····bar = '',
····baz = '';
```

**Both mixed**

```javascript
function alertSomething() {
»   var foo = 'Something',
»   ····bar = '!';

»   alert(foo + bar);
}
```

This is a really helpful practice. Code can be aligned and it will still be aligned for any monospaced font but you also preserve the semantic tab and every developer can decide his tab size by personal preference.

## Version Control (e.g. Git)

### Commit Message Format (inspired by [Angular Contributing Guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md))
Each commit message consists of a **header** and a **body**:

```
<type>: <subject>
<body>
```

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier to read on GitHub as well as in various Git tools.

### Type
Must be one of the following:

* **feat**: A new feature
* **fix**: A bug fix
* **docs**: Documentation only changes
* **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing
  semi-colons, etc)
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **perf**: A code change that improves performance
* **test**: Adding missing tests
* **chore**: Changes to the build process or auxiliary tools and libraries such as documentation
  generation

### Subject
The subject contains succinct description of the change:

* use the imperative, present tense: "change" not "changed" nor "changes"
* don't capitalize first letter
* no dot (.) at the end

### Body
Just as in the **subject**, use the imperative, present tense: "change" not "changed" nor "changes".
The body further specifies what changed and may include the motivation for the change and contrast this with previous behavior.

## Frontend Code HTML and CSS

* follow [codeguide.co](http://codeguide.co)

## JavaScript

* follow [Google JavaScript Style Guide](http://google.github.io/styleguide/javascriptguide.xml)

## PHP

* follow [PSR-2](http://www.php-fig.org/psr/psr-2)

## Ruby

* follow [GitHub Ruby Styleguide](https://github.com/styleguide/ruby)
