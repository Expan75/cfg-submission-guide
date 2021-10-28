# Homework Formatting Guide

This is a markdown file!

The nice thing about markdown files is that they can be written
on any os, on any editor, AND they are both commentable and render in GitHub.
This enables an instructor to submit feedback on a specififc pnt in the file (e.g. commenting on the typo in the word "point").

## Syntax Examples

# Header
## Smaller header
### Smaller header
#### Smaller header
##### Smallest header

A list can be defined in a dot format or by number order:
1. Item One
2. Item Two
3. Item Three

- Some item
- Another item
- And then some!

## Homework X Sample Submission

### Questions

1. Question goes here? If there a multiple sections (say both SQL and Python theory),
you can split these into 

Answer goes here. Can be a chunk of text, paragraphs or a list:

2. Can you indent a list?
   - Yes
   - You can!

### What about images and code? 

It is possible to inject both code AND images if you need too. 
Generally though, you will be fine with submitting python files (.py) and
a markdown file (.md) for the text based questions.

#### Image

If you find the need for an image, you can create an image directory in 
the same directory as your markdown file and use the following syntax:

![A cat](images/cat.jpg "Cat")

#### Code

If you want to code instead you just need to indent the code:

    worlds = [1,2,3]
    for world in worlds:
        print(f"hello world #{world}!")