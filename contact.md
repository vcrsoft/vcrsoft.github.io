---
layout: default
title: Contact
permalink: /contact/
---

# Contact Us

<form action="https://formspree.io/f/xkggkgyo" method="POST" class="contact-form">
    <input type="hidden" name="_next" value="https://vcrsoft.com">
    
    <div class="form-group">
        <label for="firstName">First Name *</label>
        <input type="text" id="firstName" name="firstName" required>
    </div>

    <div class="form-group">
        <label for="lastName">Last Name *</label>
        <input type="text" id="lastName" name="lastName" required>
    </div>

    <div class="form-group">
        <label for="organization">Organization *</label>
        <input type="text" id="organization" name="organization" required>
    </div>

    <div class="form-group">
        <label for="jobTitle">Job Title *</label>
        <input type="text" id="jobTitle" name="jobTitle" required>
    </div>

    <div class="form-group">
        <label for="email">Email Address *</label>
        <input type="email" id="email" name="_replyto" required>
    </div>

    <div class="form-group">
        <label for="message">Message *</label>
        <textarea id="message" name="message" rows="5" required></textarea>
    </div>

    <button type="submit" class="submit-button">Send Message</button>
</form>
