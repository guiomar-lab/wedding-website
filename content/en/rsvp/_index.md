---
title: "RSVP"
body: |
  Please let us know if you can attend.
  <form name="rsvp" method="POST" data-netlify="true">
    <p>
      <label>Your Name: <input type="text" name="name" required></label>
    </p>
    <p>
      <label>Email: <input type="email" name="email" required></label>
    </p>
    <p>
      <label>Will you attend? 
        <select name="attending" required>
          <option value="">Select</option>
          <option value="Yes">Yes</option>
          <option value="No">No</option>
        </select>
      </label>
    </p>
    <p>
      <button type="submit">Submit</button>
    </p>
  </form>
---
