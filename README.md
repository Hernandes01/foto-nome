# foto-nome
Verificador de idade

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/index.css">
  <script src="js/index.js"></script>
  <title>Verificador de Idade</title>
</head>
  <header>
    <h1>Verificador de idade</h1>
  </header>
  <section>
    <div>
      <p>Ano de Nascimento: 
        <input type="number" name="txtano" id="txtano" min="0">
      </p>
      <p>Sexo:
        <input type="radio" name="radsex" id="mas" checked>
        <label for="mas">Masculino</label>
        <input type="radio" name="radsex" id="fem">
        <label for="fem">Feminino</label>
        <input type="radio" name="radsex" id="trans">
        <label for="trans">Trans</label>
        <input type="radio" name="radsex" id="homo">
        <label for="homo">Homossexual</label>
      </p>
      <p>
      <input type="button" value="Verificar" onclick="verificar()">
        </p>
    </div>
    <div id="res">
      Preencha os dados acima para ver o resultado!
    </div>
  </section>
  <footer>
    <p>
      &copy; Ramon Moraes
    </p>
  </footer>
</body>
</html>
