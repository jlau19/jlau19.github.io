---
layout: essay
type: essay
title: Checkpoint Assignment #3
# All dates must be YYYY-MM-DD format!
date: 2020-12-02
labels:
  - Assignment3
  - InDevelopment
---

<b>Checkpoint A:<br>
Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</b><br>
My site's shopping cart will be displayed on a separate page either cart.html or cart.template. I'm likely to use cart.template and have my server generate this page since that's how I've been displaying my pages in Assignment 2. I plan to use sessions to keep track of all products and quantities that the user wants to purchase. On each of my product pages, instead of a "purchase" button I will have an "add to cart" button instead, that way users can navigate my different product pages and add to their carts at any time, or edit their cart by directly clicking the "cart" button that I will add in my navigation bar. From there, the user can checkout by logging in or registering as a new user.
<br><br>

<b>Checkpoint B:<br>
Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will beused in $_SESSION.</b><br>
I will use sessions to manage my shopping cart as well as making a form sticky. I will save the product quantities in an array as shown in the Assignment 3 examples, such as $_SESSION['cart']['jewelry'] = array(); The data format that will be used is JSON.
<br><br>

<b>Checkpoint C:<br>
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</b><br>
Users can look at my product pages and add quantities when they have not logged in or registered, but in order to purchase they must first log in or register. This will be done with server-side validation, if they successfully log in or register, they will be redirected but if validation fails, error messages will show instead. Some security concerns include making sure that users get the correct invoice, which sessions can take care of because each user should have their own unique sessions ID. Another security concern is users being idle, which puts them at risk for others snooping while they are logged in. This can be prevented by implementing an expiration for cookies.
<br><br>

<b>Checkpoint D:<br>
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):</b><br>
Upon a successful login, I plan to display the username in a welcome message and have it displayed for all pages that the user browses thereafter. When directed to the invoice page, the user's username will show, and upon purchase and confirmation that the invoice will be emailed, the username will also be present.
<br><br>

<b>Checkpoint E:<br>
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</b><br>
I will not be working with a partner.
<br><br>

<b>Checkpoint F:<br>
How are you approching Assigment 3 differently than Assignment 2?</b><br>
I'm approaching Assignment 3 differently because to start, I created a prototype of what I want each page of my website to look like. I know that things may change and it's a work in progress, but I feel a lot more organized going into this assignment. I feel that I will probably make changes along the way, but I think I'm off to a good start because I'm spending more time thinking and planning things out rather than jumping right into it. I also plan to keep my file architecture from Assignment 2, so for this assignment I plan take the advice and modify my Assignment 2 with minimum extra coding, if done right.
