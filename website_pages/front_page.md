---
permalink: /
title: "front_page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html>
<head>
<style>
.center {
  text-align: center;
  color: blue;
}

.large {
  font-size: 300%;
}
</style>
</head>
<body>

<h1 class="center">This heading will not be affected</h1>
<p class="center spacing">This paragraph will be BLUE and center-aligned.</p>
<p class="center large">This paragraph will be red, center-aligned, and in a large font-size.</p> 

</body>
</html>


## Before this content
Additional footnotes?[^add]
Other text.[^footnote].
I didn't think it was possible, but a space inbetween strings?[^spacedfootnote]
One final check for dates [^Author1976]

## After this content

<div class="row">
  <div class="column">
    <div class="card">
      <img src="208.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="../208.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="208.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>


Try another download...

Or a picture from the root? Let's try a full filepath

<a href="https://purpleavatar.github.io/test-website/208.jpg" download="downloadName">DownloadMe</a>

Contact us Here: 
<div id="contact">
        <h2>Get in Touch</h2>
        <div id="contact-form">
                <form action="https://formspree.io/mnqgllnn" method="POST">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Type your message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </div>

Contact form 2: 
<form
  action="https://formspree.io/mnqgllnn"
  method="POST"
>
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>

  <!-- your other form fields go here -->

  <button type="submit">Send</button>
</form>

Contact Replaced #3: 
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/YOUR_EMAIL_HERE" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Aenean lacinia bibendum nulla sed consectetur. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla nullam quis risus." required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>

Contact us! 

<form action="https://formspree.io/mnqgllnn" method="POST">
  <input type="text" name="name">
  <input type="email" name="_replyto">
  <input type="submit" value="Send">
</form>


This is the front page

Link to a youtube video: https://www.youtube.com/watch?v=xYemnKEKx0c&start=225&end=268;

Add some HTML 

<iframe class="spacing" width="640" height="360" src="https://www.youtube-nocookie.com/embed/l2Of1-d5E5o?start=210" frameborder="0" allowfullscreen></iframe>

[^Author1976]: Checking for the author and a number for the year
[^footnote]: Here's the second footnote content
[^add]: Additional content, what about out of order? 
[^spacedfootnote]: actually works? 

Here's some text after the video
