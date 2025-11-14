---
title: "Відповідь на запрошення"
body: |
  Будь ласка, повідомте, чи зможете ви бути присутні.
  <form name="rsvp" method="POST" data-netlify="true">
    <p>
      <label>Ім’я: <input type="text" name="name" required></label>
    </p>
    <p>
      <label>Email: <input type="email" name="email" required></label>
    </p>
    <p>
      <label>Чи будете присутні? 
        <select name="attending" required>
          <option value="">Оберіть</option>
          <option value="Так">Так</option>
          <option value="Ні">Ні</option>
        </select>
      </label>
    </p>
    <p>
      <button type="submit">Відправити</button>
    </p>
  </form>
---
