<!DOCTYPE html>
<html lang="pt-br">
    <meta charset="UTF-8">
        <title>Contato - Barbearia Alura</title>

        <link rel="stylesheet" href="C:\Users\User\Desktop\Curso Alura Premiere\reset\reset.css">
        <link rel="stylesheet" href="contato.css">
        <link rel="icon" href="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png">
    </head>
    <body>
        <header>
            <div class="caixa">
                <h1><img src="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png"></h1>

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
                    <label for="nome">Nome</label>
                    <input type="text" id="nome" class="input-padrao">

                    <label for="email">Email</label>
                    <input type="text" id="email" class="input-padrao" placeholder="email@dominio.com.br">

                    <label for="telefone">Telefone</label>
                    <input type="text" id="telefone" class="input-padrao" placeholder="(XX) XXXXX-XXXX">

                    <label for="mensagem">Mensagem</label>
                    <textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>

                <div>
                    <p>Como prefere o nosso contato?</p>
                    <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                    <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                    <label for="radio-whatsapp"><input type="radio" name="contato" value="telefone" id="radio-whatsapp">Whatsapp</label>
                    
                </div>

                <div>
                    <p>Qual o horário para o atendimento?</p>
                    <select>
                        <option>Manhã</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </div>

                <label class="checkbox"><input type="checkbox">Gostaria de receber nossas novidades por email?</label>

                <input type="submit" value="Enviar Formulário">

            </form>
        </main>

        <footer>
            <img src="C:\Users\User\Desktop\Curso Alura Premiere\img\logo-branco.png">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
        </footer>
    </body>

</html>
