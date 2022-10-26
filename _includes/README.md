# Divyang Mittal's website

**Note: This webpage has been upgraded to use Jekyll plugins. If you are using Github pages you will have to build the website with the Rakefile in the project root directory! My Rakefile is adopted from ones like [this.](https://blog.sorryapp.com/blogging-with-jekyll/2014/01/31/using-jekyll-plugins-on-github-pages.html)**

This is my statically-generated Jekyll/Liquid/Bootstrap-based website.
I started with the [Allan lab](https://www.allanlab.org/) webpage and modified it into a personal academic webpage that met my requirements.
I worked in a unique set of the features that I desired and could not find in publicly available templates elsewhere.
Some examples are:

* Automatically-generated buttons for DOI/PDF/ARXIV/BIB/Abstract information
  * via jekyll scholar
* Bibliography information and abstracts open in drown down wells via buttons
* Fontawesome icons (email, CV, Google scholar, ResearchGate, GitHub, etc.)
* Dark color scheme via Bootswatch
* Consistent and attractive `About me` page

I encourage the use of this webpage as a template for your own academic website.
The remainder of this document describes how to do this.
Broadly speaking, there are three steps:

* [Fork](#fork-and-build)
* [Customize](#customization)
* [Host](#hosting)

## Fork and build

* Fork [this repository](https://github.com/sbryngelson/sbryngelson.github.io) by clicking the `fork` button in the top-right corner of its Github page.
* Install [Jekyll](https://jekyllrb.com/docs/installation/)  (version less than 4.0 required) on your local computer
    * On MacOS, you will need to upgrade your Ruby version from the depricated v2.3 that is shipped. Follow the above Jekyll instructions closely.
* Run `$ bundle exec jekyll serve` in the repository root directory
* Your site is now hosted locally at `localhost:4000`, which you can access with your web browser.
   * It will be automatically re-built as you save changes to the files it contains.
   Refreshing your web browser reveals these changes.

## License

Copyright 2020, Spencer H. Bryngelson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
