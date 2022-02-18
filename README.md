# Horiseon Code Refactor

This is a refactored codebase for the original Horiseon website. The goal was to take in a semi-functioning website with minor bugs and sub-standard code and touch it up a bit. Technologies involved with refactor:

- **HTML**
- **CSS**

# Original Bugs:

The only known technical bugs that prevented some functionality of the website from being carried out are as follows:

- **links**
    - In [**#change:0006**](https://github.com/william-horn/horiseon-code-refactor/blob/main/index.html#LC44) within the change log of the [index.html](https://github.com/william-horn/horiseon-code-refactor/blob/main/index.html) file, there was no id given for the Search Engine Optimization portion of the webpage. This means when trying to navigate to this section through the nav bar, the user wasn't directed anywhere. This has been fixed.

All other issues were non-technical.

# Code Clean-Up

The rest of the changes made were implementing semantic HTML, and improving readability of the code. Such readability changes included:

- Commenting 
    - added change log record in both th **HTML** and **CSS** files
    - utilizing the "better comments" VSCode extension (for those viewing in VSCode)
    - using comments to break up sections of related code

 

* Reducing clutter
    - Replacing unnecessary classes (in [**#change:0003**](https://github.com/william-horn/horiseon-code-refactor/blob/main/assets/css/style.css#LC38) of the [style.css](https://github.com/william-horn/horiseon-code-refactor/blob/main/assets/css/style.css) file) with type selectors

# Live Page

![Landing page for Horiseon](./assets/images/01-html-css-git-homework-demo.png)

Click [here](https://william-horn.github.io/horiseon-code-refactor/) to visit page
