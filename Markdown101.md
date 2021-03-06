This file contains the getting started guide for beginner to start thier journey of mastering markdown files. We will be covering the basics of markdown files starting from headings, paragraphs, text formatting, links, images, list and finally tables.

## Heading

Well perhaps this is the most easiest in markdown files. As we already know in HTML we have headings ranging from h1 to h6. Similarly in markdown files we have heading from h1 to h6 sizes denoted by a single (#) for a h1 heading and six (#) to denote h6 heading.

# h1
## h2
### h3
#### h4
##### h5
###### h6

## Paragraph

This is how we normally type paragraph. But when it comes to line spacing between two seperate paragraphs we need a hard enter(one line in between) the para's else it will be inline.

Here is an example:
This will be inline

Whereas this will go to the next line as a seperate paragaraph.

## Formatting Text : Bold and Italics

**This is bold, it is enclosed between double astricks**

__Double underscores enclosed text are also formatted as bold text.__

_This is italics, it is enclosed within a single underscore._

*Another way to make text italic is to enclose them with single astricks*

## Lists in Markdown

### Unordered List using asterisk

* One
* Two
* Three

### Unordered List using plus sign

+ One
+ Two
+ Three

### Unordered List using minus sign

- One
- Two
- Three

### Ordered List using a single number

1. One
1. Two
1. Three

### Ordered List using incrementing number

1. One
2. Two
3. Three


### Task List (unordered)

- [x] Be Positive
- [ ] Success on the way
- [ ] Hustle

### Task List (ordered)

1. [x] Hustle
1. [ ] Success on the way
1. [ ] Be Positive

## Images In Markdown Files

![Random Image 1](https://picsum.photos/200)


![Random Image 2](ttps://picsum.photos/200/200)


![Random Image 3](https://picsum.photos/200/200 "On Hover")

## Links In Markdown Files
[Let's Connect On LinkedIn](https://www.linkedin.com/in/humzahasannit/)


[Check Out My Instagram Page][insta]


[insta]:https://www.instagram.com/codewithbravopy

## Code Blocks in Markdown Files

Code Block without language syntax highlighting
```
var name = 'Humza';
var username = 'Bravopy';
console.log(`Hey, this is ${name} aka ${username}`);
```


Code Block with language specific syntax highlighting
```
javascript
var name = 'Humza';
var username = 'Bravopy';
console.log(`Hey, this is ${name} aka ${username}`);
```


This is how we put inline code `git push origin main`


## Tables in Markdown Files


Tables in Markdown are enclosed between vertical bar (pipe) symbol. The content can be aligned left, right and center using colon symbol.

| Left columns  :| Right columns |
| ------------- |:-------------:|
| Default     | I am in center     |


| Left columns  | Right columns |
| -------------: |:-------------|
| I am in right     | I am in left |
  

  