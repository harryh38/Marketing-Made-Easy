# **1. Making the Marketing website more accesible.**

Hello, welcome to this README file which will show you how I turned the marketing website which was put together very basic to a more accesible and
easy to navigate through site for all visitors simply by using semantic HTML elements.


# **2. How the websites code looked previously.**

![Alt text](<assets/images/Screenshot 2023-10-24 at 15.48.14.png>)

As you can see from the coding, div tags where used to break up sections of the code which does work however
this makes it difficult for the software to understand exactly what is happening on the page.

The div tag is used best for styling content on the page.

It is also not good for Search Engine Optimisation as a person could be seeking a certain content on the web but as
there are only div tags on the page it will not show up on search engines even if the content is what the user is looking for.

**How it should look**

![Alt text](<assets/images/Screenshot 2023-10-25 at 16.11.46.png>)

In this example we have used semantic HTML elements to replace the div tags in order for screen readers and search engines to better read the code.


**Example:**

           <div class="header">
           <h1> How to play piano </h1>
           <img = "https://www.pexels.com/photo/close-up-photo-of-person-playing-piano-1246437/">
           <ol>
                  <li> Step 1: Learn the layout of the piano keyboard.</li>
                  <li> Step 2: Start to play piano with the right hand.</li>
                  <li> Step 3: Practice playing piano with your left hand.</li>
                  <li> Step 4: Play piano with two hands.</li>
                  <li> Step 5: Learn to play piano chords.</li>
                  <li>Step 6: Start learning a piano song with chords.</li>
                  <li> Step 7: Play the tune. </li>
            </ol>
            </div>

As you can see from the above code we have used the div tags for the whole piece of content which doesn't give us much to go off in terms
of what the content is meant to be and also for accessibility.

**How it should be:**
 
           <header class="header">
           <h1> How to play piano </h1>
           <figure>
           <img = "https://www.pexels.com/photo/close-up-photo-of-person-playing-piano-1246437/" alt="Picture of piano>
           <figcaption> A picture of hands on a piano </figcaption>
           </figure>
           <ol>
                  <li> Step 1: Learn the layout of the piano keyboard.</li>
                  <li> Step 2: Start to play piano with the right hand.</li>
                  <li> Step 3: Practice playing piano with your left hand.</li>
                  <li> Step 4: Play piano with two hands.</li>
                  <li> Step 5: Learn to play piano chords.</li>
                  <li>Step 6: Start learning a piano song with chords.</li>
                  <li> Step 7: Play the tune. </li>
            </ol>
            </header>

As you will see we have cleaned up the code slightly which makes the content more accessible to users with disablities and also helps with SEO.

We have used the header tag as this is the first indroductory content you will see when first viewing the website.

Also we have added the figure and figcaption elements to explain what the photo is within the content and also the alt attribute to give a description
of the picture.

**Live Website**
https://harryh38.github.io/Marketing-Made-Easy/