---
title: "Confirmación de asistencia"
body: |
  Por favor, confírmanos si podrás asistir.
  <form name="rsvp" method="POST" data-netlify="true">
    <p>
      <label>Nombre: <input type="text" name="name" required></label>
    </p>
    <p>
      <label>Email: <input type="email" name="email" required></label>
    </p>
    <p>
      <label>¿Asistirá? 
        <select name="attending" required>
          <option value="">Selecciona</option>
          <option value="Sí">Sí</option>
          <option value="No">No</option>
        </select>
      </label>
    </p>
    <p>
      <button type="submit">Enviar</button>
    </p>
  </form>
---
