<!DOCTYPE html>
<html lang="pt-br">
    <meta charset="UTF-8">
        <title>Contato - Barbearia Alura</title>

        <link rel="stylesheet" href="C:\Users\User\Desktop\Curso Alura Premiere\reset\reset.css">
        <link rel="stylesheet" href="contato.css">
        <link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
        <link rel="icon" href="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png">
    </head>
    <body>
        <header>
            <div class="caixa">
                <h1><img src="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png" alt="Logo da Barbearia Alura"></h1>

                <nav>
                    <ul>
                        <li><a href="C:\Users\User\Desktop\Curso Alura Premiere\Barbearia Alura\index.html">Home</a></li>
                        <li><a href="C:/Users/User/Desktop/Curso%20Alura%20Premiere/Produtos/produto.html">Produtos</a></li>
                       <li><a href="C:\Users\User\Desktop\Curso Alura Premiere\Contato\contato.html">Contatos</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        
        <main>
            <form>
                <!--Campos de texto-->
                    <label for="nome">Nome</label>
                    <input type="text" id="nome" class="input-padrao" required>

                    <label for="email">Email</label>
                    <input type="email" id="email" class="input-padrao" placeholder="email@dominio.com.br" required>

                    <label for="telefone">Telefone</label>
                    <input type="tel" id="telefone" class="input-padrao" placeholder="(XX) XXXXX-XXXX" required>

                    <label for="mensagem">Mensagem</label>
                    <textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

                <fieldset>
                    <!--Checkbox de contato-->
                    <legend>Como prefere o nosso contato?</legend>
                    <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                    <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                    <label for="radio-whatsapp"><input type="radio" name="contato" value="telefone" id="radio-whatsapp" checked>Whatsapp</label>
                    
                </fieldset>

                <fieldset>
                    <!--Preferencia de horario-->
                    <legend>Qual o hor??rio para o atendimento?</legend>
                    <select>
                        <option>Manh??</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </fieldset>
                <!--Email de novidades-->
                <label class="checkbox"><input type="checkbox" checked>Gostaria de receber nossas novidades por email?</label>

                <input type="submit" value="Enviar Formul??rio" class="enviar">

            </form>
            <!--Tabela-->
            <table>
                <thead>
                    <tr>
                        <th>Dia</th>
                        <th>Hor??rio</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Segunda </td>
                        <td>8h - 20h</td>
                    </tr>
                    <tr>
                        <td>Quarta </td>
                        <td>8h - 20h</td>
                    </tr>
                    <tr>
                        <td>Sexta </td>
                        <td>8h - 20h</td>
                    </tr>
                </tbody>
            </table>
        </main>

        <footer>
            <img src="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png" alt="Logo da Barbearia Alura">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
        </footer>
    </body>

</html>