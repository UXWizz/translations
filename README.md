# How to

## 1. Variables
Do not translate words between curly braces (eg. `{{count}}`).

## 2. Plurals
Plural is a bit tricky. If the language only has one plural (such as English) plurals can be added like this:

```
"domain": "Domain",
"domain_plural": "Domains",
```

But if the language has multiple plurals (such as Romanian) plurals must be added for all forms:

```
"domain": "Domeniu",  // Singular
"domain_1": "Domenii", // Plural for less than 20 domains
"domain_2": "Domenii", // Plural for more than 20 domains (normally it should be "De domenii" as in "20 De domenii", but "20 Domenii" is acceptable in an UI)
```

## Publishing changes
Ater you edit a translation file you can submit a pull request or, if you create a new file, send it to support [at] usertrack.net and it will be added in the next version.
You can also add a comment or create an issue on Github if you find mistakes in existing translation files.
