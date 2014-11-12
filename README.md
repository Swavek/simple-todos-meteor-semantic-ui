Simple Todos with Meteor and Semantic UI
===============================

Simple Todos starter app using Meteor framework. Extends simple-todos tutorial to use Semantic UI. http://simple-todos-semantic.meteor.com

# Introduction

At OpenStart we are really liking what Meteor 1.0 has to offer, specifically for rapid prototyping full-stack mobile-web, reactive apps, or minimum viable products (MVP).

Meteor also makes it relatively easy to add your UI library of choice when building a nice looking frontend.

Meteor team has already done a great job of making their sample apps look really cool visually. We wanted to extend that coolness with more comprehensive UI frameworks.

Semantic UI is a refreshing alternative to Twitter's popular Bootstrap framework. The UI is more modern, and the class naming cleaner.

This project extends Meteor's simple-todos app that results from their [official tutorial](https://www.meteor.com/install).

# Setup instructions

Install meteor framework. All commands use terminal.

```
curl https://install.meteor.com/ | sh
```

Pull/clone/fork this repository.

```
https://github.com/open-start/simple-todos-meteor-semantic-ui.git 
```

Add Semantic UI package.

```
meteor add nooitaf:semantic-ui
```

Add accounts-ui package for authentication.

```
meteor add accounts-ui accounts-password
```

Make app secure

```
meteor remove insecure
```

Add publish-subscribe.

```
meteor remove autopublish
```

