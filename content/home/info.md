---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Talk Information Submission
subtitle:

# content:
#   form:
#     provider: formspree
#     formspree:
#       id: https://formspree.io/f/xayknjgk
#       method: 

# design:
#   background:
#     color: black
#     text_color_light: true
#   columns: '1'
#   # css_style: 'padding-top: 0'
---

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xayknjgk"
  method="POST"
>
  <label for="full-name">Name</label>  <br />
    <input type="text" name="name" id="full-name"> <br /><br />
    <label for="email-address">Email Address</label> <br />
    <input type="email" name="_replyto" id="email-address"> <br /><br />
    <label for="title">Title</label> <br />
    <input type="text" name="title" id="title"> <br /><br />
    <label for="Abstract">Abstract<br /></label> <br />
    <textarea rows="10" name="Abstract" id="Abstract" ></textarea> <br />
    <button type="submit">Send</button>
</form>

