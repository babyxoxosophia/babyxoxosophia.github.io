---
layout: page
title: Hire Me
permalink: /contact/
---

<!-- # Hire Me for Your New Creative Project! -->

I'm available for commissions worldwide and will be happy to act in your movie, market your brand, or collaborate on creative projects. Please write to my agent at [babyxoxosophia@gmail.com](mailto:babyxoxosophia@gmail.com) or use the contact form below.

<div class="contact-form">
  <form action="mailto:babyxoxosophia@gmail.com" method="POST" enctype="text/plain">
    <div class="form-group">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required>
    </div>
    
    <div class="contact-details">
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
      </div>

      <div class="form-group">
        <label for="phone">Phone Number</label>
        <input type="tel" id="phone" name="phone" pattern="[0-9\-\+\s\(\)]*" placeholder="+1 (123) 456-7890" required>
      </div>
    </div>
    
    <div class="form-group">
      <label for="subject">Subject</label>
      <select id="subject" name="subject" required>
        <option value="">Select a subject</option>
        <option value="Acting Opportunity">Acting Opportunity</option>
        <option value="Brand Collaboration">Brand Collaboration</option>
        <option value="Creative Project">Creative Project</option>
        <option value="Commission Request">Commission Request</option>
        <option value="Press Inquiry">Press Inquiry</option>
        <option value="Other">Other</option>
      </select>
    </div>
    
    <div class="form-group">
      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" required></textarea>
    </div>
    
    <button type="submit" class="submit-button">Send Message</button>
  </form>
</div>

<style>
.contact-form {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
}

.form-group {
  margin-bottom: 20px;
}

.contact-details {
  display: flex;
  gap: 20px;
  margin-bottom: 20px;
}

.contact-details .form-group {
  flex: 1;
  margin-bottom: 0;
}

label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

input, textarea, select {
  width: 100%;
  padding: 8px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}

textarea {
  resize: vertical;
}

select {
  background-color: white;
  cursor: pointer;
}

.submit-button {
  background-color: #333;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
  transition: background-color 0.3s;
}

.submit-button:hover {
  background-color: #555;
}

a[href^="mailto:"] {
  color: #0066cc;
  text-decoration: none;
  transition: color 0.3s ease;
}

a[href^="mailto:"]:hover {
  color: #004499;
  text-decoration: underline;
}
</style> 