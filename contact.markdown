---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Contact
order: 5
permalink: /contact/
---

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

<hr>

<form action="https://submit-form.com/AL5ugzPQ">
  <label for="name">Name:</label>
  <br>
  <br>
  <input type="text" id="name" name="name" placeholder="" required="" />
  
  <br>
  <br>
  <hr>
  
  <label for="email">Email:</label>
  
  <br>
  <br>
  
  <input type="email" id="email" name="email" placeholder="" required="" />
  
  <br>
  <br>
  <hr>
  
  <label for="message">Message:</label>
  
  <br>
  <br>
  
  <textarea
  id="message"
  name="message"
  placeholder=""
  required=""
  class = comment
  ></textarea>
  
  <br>
  <br>
  <hr>
  <br>
  <button class= test type="submit">Send</button>
</form>

