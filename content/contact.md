---
title: "Contact"
description: "Get in touch with me."
---

Feel free to reach out to me using the form below. Whether you have a question, a project proposal, or just want to say hi, I'll try my best to get back to you!

<script type="text/javascript">var submitted=false;</script>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" 
onload="if(submitted) { window.location='https://nepalsaurav.github.io/'; }"></iframe>

<form action="https://docs.google.com/forms/d/e/1FAIpQLSeAsXShbCBH65J1uhe7oiaANMvcvOeCUMa6QscKEi0ZE6gTRQ/formResponse" 
      method="POST" 
      target="hidden_iframe" 
      onsubmit="submitted=true;"
      class="contact-form">

  <div class="form-group">
    <label for="name">Full Name</label>
    <input type="text" id="name" name="entry.602297319" required class="form-control">
  </div>

  <div class="form-group">
    <label for="email">Email Address</label>
    <input type="email" id="email" name="entry.648988333" required class="form-control">
  </div>

  <div class="form-group">
    <label for="phone">Phone Number (Optional)</label>
    <input type="text" id="phone" name="entry.1302564263" class="form-control">
  </div>

  <div class="form-group">
    <label for="message">Your Message</label>
    <textarea id="message" name="entry.342039661" rows="5" required class="form-control"></textarea>
  </div>

  <button type="submit" class="submit-btn">
    Send Message
  </button>
</form>

<style>
.contact-form {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    margin-top: 2rem;
    max-width: 600px;
}
.form-group {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
}
.form-group label {
    font-weight: 600;
    color: var(--primary);
}
.form-control {
    padding: 0.75rem;
    border: 1px solid var(--border);
    border-radius: var(--radius);
    background: var(--entry);
    color: var(--primary);
    font-family: inherit;
    font-size: 1rem;
    transition: border-color 0.2s;
}
.form-control:focus {
    outline: none;
    border-color: var(--primary);
}
.submit-btn {
    padding: 0.75rem 1.5rem;
    background: var(--primary);
    color: var(--theme);
    border: none;
    border-radius: var(--radius);
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
    transition: opacity 0.2s;
    align-self: flex-start;
}
.submit-btn:hover {
    opacity: 0.8;
}
</style>
