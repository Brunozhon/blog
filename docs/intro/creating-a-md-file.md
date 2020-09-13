# Creating a `.md` file

## Simple example

```markdown
# Heading 1

Hello, my name is Bruno. I am 7 years old.

![Me!](https://brunozhon.github.io/image.jpg)

## Heading 2

[Blog](https://brunozhon.github.io/blog/)

[Comminuty](https://brunozhon.github.io/community/)

### Heading 3

`Inline code`

#### Heading 4

|Header 1|Header 2|
|--------|--------|
|Content 1|Content 2|

1. List items
2. List items
   1. Minor list items
   2. Minor list items
      1. Super minor list items
      2. Super minor list items

##### Heading 5

- Tick list item
- Like me!
  - Higher
  - Like me 
  
* \*'s work just as well
* Like me!
  * And like me!

###### Heading 6

We're done!

####### Heading 7; it won't work!
```

Add into the _config.yml file:

```yml
theme: personal-github-theme
title: your-title # Title is optional
```

`personal-github-theme` should be a github theme you know. `your-title` could be a title, like "Welcome to Bruno Zhong's website!".

We set it to:

```yml
theme: jekyll-theme-hacker
```

Save it in a file called `index.md`
