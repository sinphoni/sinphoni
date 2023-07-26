<!DOCencuestas html>
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
        <input type="radio" name="q2" value="si"> Sí
      </label>
      <label>
        <input type="radio" name="q2" value="no"> No
      </label>

      <p>3. ¿Has dormido al menos 7 horas anoche?</p>
      <label>
        <input type="radio" name="q3" value="si"> Sí
      </label>
      <label>
        <input type="radio" name="q3" value="no"> No
      </label>

      <p>4. ¿Has bebido suficiente agua hoy?</p>
      <label>
        <input type="radio" name="q4" value="si"> Sí
      </label>
      <label>
        <input type="radio" name="q4" value="no"> No
      </label>

      <p>5. ¿Te has sentido estresado/a hoy?</p>
      <label>
        <input type="radio" name="q5" value="si"> Sí
      </label>
      <label>
        <input type="radio" name="q5" value="no"> No
      </label>

      <p>6. ¿Has fumado o consumido alcohol hoy?</p>
      <label>
        <input type="radio" name="q6" value="si"> Sí
      </label>
      <label>
        <input type="radio" name="q6" value="no"> No
      </label>

      <button type="submit">Enviar respuestas</button>
    </form>
  </div>
</body>
</html>
