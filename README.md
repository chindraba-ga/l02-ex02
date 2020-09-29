# l02-ex02

-  Status: Final
-  CodePen: <https://codepen.io/chindraba-ga/pen/mdPymwo>
-  Live page: <https://fewd.chindraba.work/lessons/l02-ex02/project_page.html>

## Contents

-  [Description](#description)
-  [Copyright and License](#copyright-and-license)
   -  [The MIT License](#the-mit-license)

---
## Description

### Lesson 2: Computers Out: CSS Exploration

This example contains a real piece of of a website. Apply all you've learned
with CSS and experiment. Remember, there's more than one right answer!

The starter code was:

#### HTML

    <!-- ## CSS Experimentation

    We've gone over some good properties to use but they are hard to grasp without actually using them. Included in this assignment is a  (mostly) REAL chunk of a website I've built.

## Style time

    The goal here is to take 30 minutes and really get to know the world of stylesheets. Use the cheatsheet guide, notes from class and resources that have been recommended in class. Some ideas to get you going:

    - Try to use font, background and text classes
    - Move the images around the page
    - Change the color of some of the words
    - Make text align differently

    There is no right answer to this, just experiment.

## Use the following HTML  -->

    <!doctype html>
    <html class="no-js" lang="en">
      <head>
        <meta charset="utf-8">
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>AA Sample Page</title>

        <link rel="apple-touch-icon" href="apple-touch-icon.png">
        <link rel="stylesheet" href="main.css">
      </head>
      <body>

      <main class="aa">


        

        <!-- Homepage News Layout -->
        <section class="hp-news-container">
          <div class="hp-news-block-container hp-news-block-container-1">
            <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/aa_sample_3_sized.jpg" alt="F-22 landing on aircraft carrier" />
            <span class="hp-news-category">News Item</span>
            <h2 class="hp-news-title">Duis luctus et ipsum et porta Vivamus quis quam sed felis imperdiet pharetra</h2>
            <h3 class="hp-news-author">Author Last Name</h3>
            <h4 class="hp-news-date">June 2016</h4>
          </div>
          <div class="hp-news-block-container hp-news-block-container-2">
            <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/aa_sample_9_sized.jpg" alt="Electronic chip board" />
            <span class="hp-news-category">News Item</span>
            <h2 class="hp-news-title">Morbi orci lorem aliquam ultrices magna at</h2>
            <h3 class="hp-news-author">Author Last Name</h3>
            <h4 class="hp-news-date">June 2016</h4>
          </div>
          <div class="hp-news-block-container hp-news-block-container-3">
            <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/aa_sample_7_sized.jpg" alt="Racially diverse board meeting" />
            <span class="hp-news-category">News Item</span>
            <h2 class="hp-news-title">Fusce ac mollis sapien</h2>
            <h3 class="hp-news-author">Author Last Name</h3>
            <h4 class="hp-news-date">June 2016</h4>
          </div>
        </section>
      </main>

      <footer class="footer-container">
        <div class="footer-block-container footer-block-container-1">
          <p>Content TBD. Proin vehicula varius aliquet. In ut aliquet nibh. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Pellentesque laoreet rutrum tincidunt. Maecenas non ullamcorper ipsum. Ut ut velit a justo porttitor posuere ut posuere lacus. Cras id vehicula tortor, a tincidunt ligula. Pellentesque sed semper sapien.</p>
        </div>
        <div class="footer-block-container footer-block-container-2">
          <p>Content TBD. Proin vehicula varius aliquet. In ut aliquet nibh. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Pellentesque laoreet rutrum tincidunt. Maecenas non ullamcorper ipsum. Ut ut velit a justo porttitor posuere ut posuere lacus. Cras id vehicula tortor, a tincidunt ligula. Pellentesque sed semper sapien.</p>
        </div>
        <div class="footer-block-container footer-block-container-3">
          <p>Content TBD. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In dolor elit, facilisis in justo in, faucibus aliquet dolor. Suspendisse eget lacus felis. Nullam convallis massa vel sem porta efficitur ut sit amet lorem. Morbi auctor pellentesque lectus in elementum. Donec feugiat ex tellus, ac placerat leo hendrerit at. Morbi porttitor sapien vel purus faucibus, lacinia ultricies dui dapibus. Donec elementum, massa vitae volutpat hendrerit, sem neque ornare risus, a suscipit lacus tellus eu turpis.</p>
        </div>
      </footer>

      </body>
    </html>

#### CSS

    /* Just one way you could style things */

    .aa {
    background-color: #292929;
    padding: 30px;
    }

    .hp-news-category {
    display: block;
    font-size: 18px;
    text-transform: uppercase;
    font-family: Arial, sans-serif;
    font-weight: bolder;
    line-height: 1;
    color: #fff;
    }
    .hp-news-title {
    font-size: 48px;
    line-height: 1;
    margin: 5px 0;
    font-weight: lighter;
    color: #fff;
    }

    .hp-news-author, .hp-news-date  {
    color: #fff;
    text-transform: uppercase;
    font-family: sans-serif;
    line-height: .1;
    }

    img {
    width: 100%;
    }

[TOP](#contents)

---
## Copyright and License

Copyright © 2020  Chindraba (Ronald Lamoreaux)

<[upskill@chindraba.work](mailto:upskill@chindraba.work?subject='l02-ex02')>

— All Rights Reserved

### The MIT License
    
    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the "Software"),
    to deal in the Software without restriction, including without limitation
    the rights to use, copy, modify, merge, publish, distribute, sublicense,
    and/or sell copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGE MENT. IN NO EVENT SHALL
    THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE.

[TOP](#contents)
