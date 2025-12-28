<section class="contact">
  <h2>Let’s Connect</h2>
  <p>
    Reach out to me directly via <a href="mailto:Doyal.Kumar.Sarker@ucf.edu"> Doyal.Kumar.Sarker@ucf.edu </a> or using my <a href="https://www.linkedin.com/in/doyal-kumar-sarker-5a22a418b/" LinkedIn </a> profile. You cmay      also use the contact form below to send me a message.
  </p>

  <form
    action="https://formspree.io/f/xeoylvkv"
    method="POST"
  >
    <label for="name">
      Your Name
    </label>
    <input
      type="text"
      id="name"
      name="name"
      placeholder="Your full name"
      required
    >

    <label for="email">
      Your Email
    </label>
    <input
      type="email"
      id="email"
      name="email"
      placeholder="your.email@example.com"
      required
    >

    <label for="message">
      Your Message
    </label>
    <textarea
      id="message"
      name="message"
      rows="5"
      placeholder="Write your message here..."
      required
    ></textarea>

    <!-- Email subject -->
    <input type="hidden" name="_subject" value="New message from website">

    <!-- Honeypot (spam protection) -->
    <input type="text" name="_gotcha" style="display:none">

    <button type="submit">Send Message</button>
  </form>
</section>
