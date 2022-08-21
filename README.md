# formularios-novos
<!DOCTYPE html>
<html lang="en">
</head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Cadastro</title>
</head>
<body>

    <div>
        <h1 id="titulo">Cadastro de DEVs</h1>
        <p id="subtitulo">Complete suas informações</p>
        <br>
    </div>

    <form>
        <fieldset class="Grupo">
            <div class="campo">
                <strong></strong><label for="Nome">Nome</label><strong></strong>
                <input type="text" name="Nome" id="Nome" required>
            </div class="campo">
            <br><br>
            <div class="Campo">
                <strong></strong><label for="Sobrenome">Sobrenome</label><strong></strong>
                <input type="text" name="Sobrenome" id="Sobrenome" required>
            </div class="Campo">
        </fieldset class="Grupo">
        <br><br>
        <div>
          <label for="email">Email</label>
          <input type="email" name="email" id="email" required>
        </div>
        <br><br>
        <div class="campo">
            <strong></strong><label>De qual Lado da aplicação você Desenvolve</label><strong></strong>
            <label>
               <input type="radio" name="devweb" value="Frontend" checked>Front-End
            </label>
            <br>
            <label>
                <input type="radio" name="devweb" value="Backend">Back-end
            </label>
            <input type="radio" name="devweb" value="Full-stack">Full-stack
        </div class="Campo">
<br><br>

<div class="Campo">
    <label>Senioridade</label>
    <select id="Senioridade">
    <option selected disabled value="">Escolha</option>
    <option>Junior</option>
    <option>Pleno</option>
    <option>sênior</option>
    </select>
</div class="Campo">
<br><br>
<fieldset>
    <div class="campo">
        <label>Selecione as tecnologias que utiliza:</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
        <input type="checkbox" id="tecnologia8" name="tecnologia8" value="C++">
        <label for="tecnologia8">C++</label>
    </div class="Campo">
</fieldset>

<div class="Campo">
    <br>
    <label for="experiência">Conte um pouco da sua experiência</label>
    <textarea row="6" style="margin: ;13em" id="experiência" name="experiência"><</textarea>
</div class="Campo">

<button type="submit">Concluido!</button>

</form>
   

</body>
</html>
