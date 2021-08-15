# Code Refactor Starter Code

## Description

This is a project where I was given the index.html and style.css files for a basic website for a business that helps companies manage their online presence. The main purpose was to demonstrate understanding of how semantic elements can be used to structure html, and to show understanding for how to write css in an efficient manner. 

The first issue was that the html needed to be given semantic elements, as most sections of the site were put within <div> elements, which doesn't give any indication about the content of the site. I replaced most of the <div> elements so that the site was broken into header, main, and footer. The header had <nav> added around the navigation links. The main section was also given elements such as <section> to further divide it.

The second issue I fixed was that the link for Search Engine Optimization wasn't working, as the section had no id.

I also cleaned up some of the classes for main content and benefits sections, so that css could be applied to them as groups, rather than individuals.

The css needed to be simplified, with certain rule sets combined when possible. This was done either by adding the appropriate selectors to the rule set, or by using the newly created classes to apply the rule set to a group.

Comments were also added to the css in order to show where the rules were being applied (header, body, footer, etc).

## Installation

To install this project, you can clone the repository by using the command prompt

$ git clone https://github.com/AllysonMcGrath/cbcchallenge1.git

Detailed instructions for cloning GitHub repositories can be found [here.](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)



## Usage

When displaying correctly, website should look like the image below:

![Horiseon website with navigation, images, and sections](Develop/assets/images/mockup.png)

Use standard git commands within this repository.

Examples:

$ git mv index.html ../
$ git add .
$ git commit -m "commit description"
$ git push origin main

## Credits

Trilogy Education Services, LLC, a 2U, Inc. brand

[Coding Boot Camp at UT](https://github.com/the-Coding-Boot-Camp-at-UT)

## License

MIT License

Copyright (c) 2021 Allyson McGrath

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
