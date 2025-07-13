# malla-universidad
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Malla Curricular de Mariana</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Malla Curricular de Mariana</h1>

  <div class="semestre">
    <h2>Ciclo 1</h2>
    <div class="materia aprobada">Francés Intensivo I</div>
    <div class="materia aprobada">Inglés Básico Intensivo</div>
    <div class="materia aprobada">Psicopedagogía I</div>
    <div class="materia aprobada">Teoría de la Comunicación I</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 2</h2>
    <div class="materia aprobada">Francés Intensivo II</div>
    <div class="materia aprobada">Inglés Intermedio Intensivo I</div>
    <div class="materia aprobada">Teoría de la Comunicación II</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 3</h2>
    <div class="materia aprobada">Francés Intensivo III</div>
    <div class="materia aprobada">Gramática Inglesa I</div>
    <div class="materia aprobada">Inglés Intermedio Intensivo II</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 4</h2>
    <div class="materia aprobada">Francés Avanzado</div>
    <div class="materia aprobada">Gramática Francesa I</div>
    <div class="materia aprobada">Gramática Inglesa II</div>
    <div class="materia aprobada">Inglés Avanzado Intensivo I</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 5</h2>
    <div class="materia aprobada">Expresión Oral en Francés</div>
    <div class="materia aprobada">Gramática Francesa II</div>
    <div class="materia aprobada">Inglés Avanzado Intensivo II</div>
    <div class="materia aprobada">Pronunciación en Inglés</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 6</h2>
    <div class="materia aprobada">Fonética Francesa</div>
    <div class="materia aprobada">Lectura y Conversación en Inglés I</div>
    <div class="materia aprobada">Ortografía y Estilística Francesa</div>
    <div class="materia aprobada">Relaciones Públicas</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 7</h2>
    <div class="materia aprobada">Composición Inglesa I</div>
    <div class="materia aprobada">Francés y el Comercio</div>
    <div class="materia aprobada">Introducción a la Civilización Francesa</div>
    <div class="materia aprobada">Lectura y Conversación en Inglés II</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 8</h2>
    <div class="materia pendiente">Francés y el Turismo</div>
    <div class="materia pendiente">Gramática Avanzada</div>
    <div class="materia pendiente">Literatura Francesa I</div>
    <div class="materia pendiente">Opinión Pública</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 9</h2>
    <div class="materia pendiente">Francés y la Traducción</div>
    <div class="materia pendiente">Introducción a la Lingüística</div>
    <div class="materia pendiente">Literatura Francesa II</div>
    <div class="materia pendiente">Seminario I</div>
  </div>

  <div class="semestre">
    <h2>Ciclo 10</h2>
    <div class="materia pendiente">Fonología y Morfología Inglesa</div>
    <div class="materia pendiente">Historia de El Salvador y C.A.</div>
    <div class="materia pendiente">Literatura en Inglés I</div>
    <div class="materia pendiente">Seminario II</div>
  </div>

</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #eef5fb; /* fondo celeste */
  padding: 20px;
}

h1 {
  text-align: center;
  color: #1e3a8a; /* azul oscuro */
}

.semestre {
  background-color: #ffffff;
  margin: 20px auto;
  padding: 15px;
  border-radius: 12px;
  width: 90%;
  max-width: 800px;
  box-shadow: 0 0 10px rgba(0,0,0,0.07);
  border-left: 5px solid #a8d0e6;
}

.semestre h2 {
  color: #1e3a8a;
  margin-bottom: 10px;
}

.materia {
  display: inline-block;
  padding: 10px 16px;
  margin: 10px 8px;
  border-radius: 10px;
  font-weight: 600;
  font-size: 15px;
  background-color: #dbeafe; /* celeste por defecto (pendiente) */
  color: #1e3a8a;
  transition: transform 0.2s ease;
}

.materia:hover {
  transform: scale(1.05);
}

.aprobada {
  background-color: #a8d0e6; /* azul claro */
}

.pendiente {
  background-color: #dbeafe; /* celeste más suave */
}
