---
layout: post
title: The Buzz
thumbnail-path: "img/thebuzz.png"
image-class: "macbook-pro"
tagline: Get the buzz with this collaborative app!
short-description: The Buzz allows users to share knowledge by creating and collaborating on wikis. For a small charge, users can upgrade their membership to Premium, allowing them to view, create, and collaborate on private wikis.


---

{:.center}
![]({{ site.baseurl }}/img/thebuzz.png)

{:.center}
<h5>
  <a href="http://thebuzzz.herokuapp.com" class="button">
    Heroku Demo
  </a>  
  <a href="https://github.com/rachelcolby11/TheBuzz" class="button">
    Source Code
    <i class="fa fa-fw fa-github"></i>
  </a>
</h5>

{:.center}
### Overview

The Buzz is a Ruby on Rails application that allows users to create wikis and collaborate on other wikis -- like a smaller, trendier version of Wikipedia where users share knowledge and read what everyone's buzzing about. For a small charge, users can upgrade their membership to Premium, allowing them to view, create, and collaborate on private wikis.

{:.center}
### Features
* Users can create a standard account in order to create, edit, and collaborate on public wikis using Markdown syntax; anyone can view public wikis.
* Users can pay to upgrade their account to Premium in order to view and create private wikis.
* Premium users can allow others to view and collaborate on the private wikis they create.
* Premium users can downgrade their account back to Standard.
* When a user downgrades his or her account, his or her private wikis will automatically become public.

{:.center}
### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools and Gems:**

* Devise for user authentication
* SendGrid for email confirmation
* Redcarpet for Markdown formatting
* Pundit for authorization
* Stripe for payments

{:.center}
<h5>
  <a href="/portfolio/3-ticktocktoe/" class="button next-project">
    Next: Tick-Tock-Toe
    <i class="fa fa-chevron-right"></i>
  </a>
</h5>
