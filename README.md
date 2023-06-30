# 01
Landing page
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Landing Page Pañalera</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
  <div class="container">
    <h1>Pañalera XYZ</h1>

    <div class="row">
      <div class="col-md-6">
        <h2>Presentación de la Organización</h2>
        <p>Aquí puedes escribir información sobre tu organización y los productos que ofrecen.</p>

        <h2>Presentación Personal</h2>
        <p>Aquí puedes agregar información sobre las personas detrás de la empresa y su experiencia en el rubro.</p>
      </div>
      <div class="col-md-6">
        <h2>Formulario de Contacto</h2>
        <form id="contact-form">
          <div class="form-group">
            <label for="name">Nombre:</label>
            <input type="text" class="form-control" id="name" name="name" required>
          </div>
          <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" class="form-control" id="email" name="email" required>
          </div>
          <div class="form-group">
            <label for="message">Mensaje:</label>
            <textarea class="form-control" id="message" name="message" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
      </div>
    </div>

    <div class="row">
      <div class="col-md-6">
        <h2>Formulario de Cotización</h2>
        <form id="quote-form">
          <!-- Agrega los campos necesarios para el formulario de cotización -->
        </form>
      </div>
      <div class="col-md-6">
        <h2>Formulario de Reclamo</h2>
        <form id="complaint-form">
          <!-- Agrega los campos necesarios para el formulario de reclamo -->
        </form>
      </div>
    </div>

    <div id="api-results" class="mt-4"></div>
  </div>

  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-validate/1.19.3/jquery.validate.min.js"></script>
</body>
</html>
