---
layout: post
title: Contact
permalink: /contact/
---
<style>
.contact-li {
    list-style: none;
}

.contact-input {
    width: 100%;
}

.contact-input:focus {
    outline:none;
    border-bottom: 1px solid #37c376;
}

.contact-label {
    display: block;
}

ul.contact-ul {
    margin: 0;
    padding: 10px;
}

 #submit {

    background-color: #37c376;
    opacity: 0.8;
    color: #eee;
    border: none;

}

#submit:hover {
    opacity: 1;
    cursor: pointer;
} 


#contact-form {
    border: 1px solid #aaa;
    margin-bottom: 1em;
}

</style>

You can send me your feedback or suggestion here. If there is something missing in the theme then you can ask me to add. 

Also, if you are willing to add it yourself then feel free to open a pull request after making changes.

<form id="contact-form"
      action="https://formsubmit.co/canofworms23@yahoo.com"
      method="POST">

  <!-- 防機器人 honeypot，必填但藏起來 -->
  <input type="text" name="_gotcha" style="display:none" />
  <!-- 自訂提交後跳轉頁面，可改成你自己的 thank-you.html -->
  <input type="hidden" name="_next" value="/thank-you.html" />

  <ul class="contact-ul">
    <li class="contact-li">
      <label class="contact-label" for="name">Name:</label>
      <input type="text"    id="name"    name="name"    class="contact-input" placeholder="Your name" required />
    </li>
    <li class="contact-li">
      <label class="contact-label" for="email">Email:</label>
      <input type="email"   id="email"   name="email"   class="contact-input" placeholder="Your email" required />
    </li>
    <li class="contact-li">
      <label class="contact-label" for="message">Message:</label>
      <textarea id="message" name="message" class="contact-input" rows="4" placeholder="Your message" required></textarea>
    </li>
  </ul>

  <button type="submit" id="submit">Send</button>
</form>

Just update the email: in config.yml to make this form work.


Add a contact form
