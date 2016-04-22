# Codeception utilities

A handful of generic helper and utility methods for Codeception.

* **seeLinkInSelector** - looks for a link in a particular CSS or XPath selector.
* **seeElementHasStyle** - see an element has been applied a style. Allows you to check a single element has a CSS style assigned, e.g. you can check that ".icon-r" class is floated right. Requires WebDriver.
* **dontSeeElementHasStyle** -  see element has not been applied a style. Requires WebDriver.

## Installing

Add to your **composer.json**, e.g.

```
{
  "repositories": [
    {
      "type":"vcs",
      "url":"git@github.com:ixis/codeception-utilities.git"
    }
  ],
  "require": {
    "ixis/codeception-utilities": "dev-develop"
  }
}
```
