+++
title = "Contact the German Reproducibility Network"

# This page needs a template attribute so as not to be rendered as a section
template = "page.html"
+++

# We'd love to hear from you!

You're warmly invited to write us, we'll get back to you by email. You can also write directly to [info@reproducibilitynetwork.de](mailto:info@reproducibilitynetwork.de).

----

<form name="contact" method="POST" netlify-honeypot="bot-field" data-netlify="true" action="/contact/thanks">
  <p class="d-none">
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </p>
  <div class="mb-3">
    <label for="subject">Subject</label>
    <small class="text-muted mb-2">&ensp;·&ensp;How can we help?</small>
    <input type="text" class="form-control form-control-lg mt-2" name="subject" id="subject">
  </div>
  <div class="mb-3">
    <label for="message">Message</label>
    <small class="text-muted"></small>
    <textarea class="form-control mt-2" name="message" id="message" rows="6"></textarea>
  </div>
  <div class="mb-3">
    <label for="email">Your email address</label>
    <small class="text-muted">&ensp;·&ensp;We accept anonymous messages, but please be aware that we can't respond.</small>
    <input type="email" class="form-control mt-2" name="email" id="email">
  </div>
  <div>
    <button type="submit" class="btn btn-outline-primary w-100 mt-4">Send</button>
  </div>
</form>
