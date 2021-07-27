---
hide:
  - navigation
title: 
---

This website work as a template for your open source documentation

## Code Documentation
You can use this to document your code like this:

=== "Java"
    ```java
    class User() {
      public String name;
      public String email;

      public User(String name, String email) {
        this.name = name;
        this.email = email;
      }

      public setName(String name) {
        this.name = name;
      }

      public String getName() {
        return this.name;
      }

      public setEmail(String email) {
        this.email = email;
      }

      public String getEmail() {
        return this.email;
      }
    }
    ```

=== "Kotlin"
    ```kotlin
    data class User(name : String, email : String)
    ```

!!! Note
    You can also provide information like this using admonition

## Focus on content

Write your documentation using [markdown](https://www.markdownguide.org/basic-syntax/) without any tweaks on HTML, javascript, or CSS.
You can provide your project dependencies using table like this:

|Name|Version|
|---|---|
|Some Dependencies|`0.1.0`|
|Other Dependencies we need| `1.3.10`|

You can also add footnotes, like this: 
> PHP is the best language[^1]

You can provide list to define things too:

- One Apple
- Two Oranges
- Three Bananas

or even a task lists to define which codebase is the best:

- [x] Android
- [ ] Ios
- [ ] React Native
- [ ] Back-end

## Other
You can see all list of configuration [here](https://squidfunk.github.io/mkdocs-material/) <br/>
Or even a sample of this template [here](https://dev-codebase.web.app/)











[^1]: It's not