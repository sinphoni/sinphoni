<DOCencuestas html>
<html>
<head>
  <title>Preguntas de Salud</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Preguntas de Salud</h1>
    <form>
      <p>1. ¿Has hecho ejercicio hoy?</p>
      <label>
        <a href="#" onclick="selectOption('q1', 'si')">Sí</a>
        <input type="radio" name="q1" value="si" style="display: none;">
      </label>
      <label>
        <a href="#" onclick="selectOption('q1', 'no')">No</a>
        <input type="radio" name="q1" value="no" style="display: none;">
      </label>

      <p>2. ¿Has consumido frutas y verduras hoy?</p>
      <label>
        <a href="#" onclick="selectOption('q2', 'si')">Sí</a>
        <input type="radio" name="q2" value="si" style="display: none;">
      </label>
      <label>
        <a href="#" onclick="selectOption('q2', 'no')">No</a>
        <input type="radio" name="q2" value="no" style="display: none;">
      </label>

      <!-- Repite lo mismo para las otras preguntas (3 a 6) -->

    </form>
  </div>

  <script>
    function selectOption(question, option) {
      document.querySelector(`input[name="${question}"][value="${option}"]`).checked = true;
    }
  </script>
</body>
</html>
