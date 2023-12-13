# Git OR Github

- Git and Github are two different things.
- Git is the version control system.
- GitHub is a service for hosting Git repos that helps people collaborate on writing software.

# Similar Service

- GitLab
- BitBucket

# What is a repository?

- A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a README file, a file with information about your project. README files are written in the plain text Markdown language.

# What are branches?

- By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the main source of code.

- Have you ever saved different versions of a file? Something like:

  - story.txt
  - story-edit.txt
  - story-edit-reviewed.txt

Making and commiting changes

- Two ways
- Using git bash
  - About this in command's section.
- Using github
  - Give a demo.

# What is a Commit?

- A commit is when you tell Git to save these staged changes.

# What is a Pull Request?

- When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch.

- Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

## Mention username in pull request

    `@username`

# How to merge a pull request?

- At the bottom of the pull request, click Merge pull request to merge the changes into main.

# Forks

- Github forks local copy of a project folder/repository.
- You can make a relevant chanages ask the owner to review changes

![Github-fork](./Github-fork.gif "How does Fork work")

<center>@TAPAS ADHIKARY FreeCodeCamp</center>

# About Markdown

- Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents.

## Why use markdown

- Simplicity, Readability, Speed, Widely Supported

## How does markdown work

![md-working](./md-working.png "How does markdown work")

## Basic Syntax

- Heading

  - # H1
  - ## H2
  - ### H3

- Bold Text

  - **bold Text**

- Italic Text

  - _Italic Text_

- Blockquote

  > Blockquote

- Ordered List

  1. Item 1
  2. Item 2

- Unordered List

  - Item 1
  - Item 2

- Code

  `console.info('Block of code!')`

- Horizontal Rule

  ***

- Link
  [title](https://www.example.com)

- Image
  ![alt text](image.jpg)

## Extended Syntax/ Advanced Syntax

- Table

<!-- | ------ | ---------- | -->

| Sr. No | First Name |
| :----- | :--------: |
| 1      | John Cena  |
| 2      |  CM Punk   |

- Emoji

  That is so funny! :joy:

  :warning: **Warning:** Do not push the big red button.

- Fenced Code Blocks

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

- Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

- Heading IDs

  ### My Great Heading {#heading-id}

- Definition Lists

  First Term
  : This is the definition of the first term.

- Strikethrough
  ~~The world is flat.~~ We now know that the world is round.

- Task List

  - [x] Write the press release
  - [x] Update the website
  - [x] Contact the media

- Highlight

  I need to highlight these ==very important words==.

- Subscript & Superscript

  H~2~O

  X^2^

- Comments

  Here's a paragraph that will be visible.

  [This is a comment that will be hidden.]: #

- Some things markdown does not support natively

  - underline
    - <ins>will be underlined</ins>.
  - ident
    - &nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.
  - center
    - <center>This text is centered.</center>
    - <p style="text-align:center">Center this text</p>
  - color

    - <font color="red">This text is red!</font>

  - Image size, image caption and more

# Install Git

- Windows: Download

# Three section of a Git Project

- Git directory
  - Git stores everything it needs to accurately track the project.
- Working directory
  - User makes local changes to a project.
- Staging area
  - Information about what will go into your next commit.

## Command's

1. Check git version

  ```
  git -v
  ```

  ```
  git --version
  ```

2. Get git help

  ```
  git -h
  ```

  ```
  git --help
  ```

3. To Know the username

  ```
  git config user.name
  ```

4. To Know the email

  ```
  git config user.email
  ```

5. Git init

    - Create an empty Git repository or reinitialize an existing one

        ```
        git init
        ```

    - Only print error and warning messages; all other output will be suppressed.

        ```
        git init -q
        ```

        ```
        git init --quite
        ```

    - Use the specified name for the initial branch in the newly created repository.

        ```
        git init -b master
        ```

        ```
        git init --initial-branch master
        ```

    - Specify the directory from which templates will be used. (See the "TEMPLATE DIRECTORY" section below.)

        ```
        git init --template ./
        ```

    - use if repo will be shared with multiple users

        ```
        --shared
        ```

6. Git clone

7. Git add

    - Add file contents to the index

        ```
        git add .
        ```

        ```
        git add all
        ```

        ```
        git add filename
        ```

8. Git status

    ```
    git status
    ```

- Git diff

- Git commit


