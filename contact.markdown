---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Contact
order: 5
permalink: /contact/
---
<script src="https://challenges.cloudflare.com/turnstile/v0/api.js" async defer></script>

<style>
	.comment {
		resize: none;
    height: 100px;
    width: 350px;
  }
</style>

<style>	
	.test{
    height:30px;
    width:80px;
  }

</style>

# Contact Form:

<hr>

<form action="https://submit-form.com/AL5ugzPQ">
  <div class="cf-turnstile" data-sitekey="yourSiteKey"></div>
  <label for="name">Name:</label>
  <br>
  <br>
  <input type="text" id="name" name="name" placeholder="John Doe" required="" />
  
  <br>
  <br>
  <hr>
  
  <label for="email">Email:</label>
  
  <br>
  <br>
  
  <input type="email" id="email" name="email" placeholder="example@example.com" required="" />
  
  <br>
  <br>
  <hr>

  <label for="phone">Phone Number:</label>

  <br>
  <br>

  <input type="tel" name="phone" maxlength="14" minlength="7" placeholder="(123) 456-7890">
  
  <br>
  <br>
  <hr>

  <label for="message">Message:</label>
  
  <br>
  <br>
  
  <textarea
  id="message"
  name="message"
  placeholder="Message"
  required
  class = comment
  ></textarea>
  
  <br>
  <br>
  <hr>
  <br>
  <button class= test type="submit">Send</button>
  <input type="reset" value="Reset form" class=test>
</form>

