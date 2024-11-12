<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootcamp DIO - Cibersegurança Santander - Phishing para captura de senhas do Facebook</title>
    <style>
        /* Estilo para os títulos */
        h1, h2 {
            transition: all 0.3s ease;
        }

        /* Efeito de hover para os títulos */
        h1:hover, h2:hover {
            color: #3498db;
            text-shadow: 2px 2px 5px rgba(52, 152, 219, 0.6);
            cursor: pointer;
        }

        /* Estilo de link para os links internos */
        a {
            text-decoration: none;
            color: #2c3e50;
            transition: color 0.3s;
        }

        a:hover {
            color: #e74c3c;
        }
    </style>
</head>
<body>
    <h1>Phishing para Captura de Senhas do Facebook</h1>

    <h2>Ferramentas Utilizadas</h2>
    <ul>
        <li><b>Kali Linux</b>: Uma distribuição de segurança e testes de penetração.</li>
        <li><b>SEToolkit</b>: Ferramenta de engenharia social que facilita a criação de ataques de phishing e outros ataques.</li>
    </ul>

    <h2>Configurando o Phishing no Kali Linux</h2>

    <h3>Passo 1: Acesso como root</h3>
    <p>Primeiro, abra o terminal no Kali Linux e obtenha acesso root:</p>
    <pre><code>sudo su</code></pre>

    <h3>Passo 2: Iniciando o SEToolkit</h3>
    <p>Em seguida, inicie o <b>SEToolkit</b> no Kali Linux:</p>
    <pre><code>setoolkit</code></pre>

    <h3>Passo 3: Escolhendo o Tipo de Ataque</h3>
    <p>Dentro do SEToolkit, selecione as opções conforme descrito:</p>
    <ul>
        <li><b>Tipo de ataque</b>: Social-Engineering Attacks</li>
        <li><b>Vetor de ataque</b>: Web Site Attack Vectors</li>
        <li><b>Método de ataque</b>: Credential Harvester Attack Method</li>
        <li><b>Método de ataque adicional</b>: Site Cloner</li>
    </ul>

    <h3>Passo 4: Obter o Endereço da Máquina</h3>
    <p>Utilize o comando a seguir para descobrir o endereço IP da sua máquina:</p>
    <pre><code>ifconfig</code></pre>

    <h3>Passo 5: URL para o Clone</h3>
    <p>Agora, forneça a URL que você deseja clonar. Neste caso, vamos usar o <b>Facebook</b>:</p>
    <p><a href="http://www.facebook.com" target="_blank">http://www.facebook.com</a></p>

    <h3>Passo 6: Resultados</h3>
    <p>Após seguir os passos acima, o SEToolkit irá clonar o site do Facebook e você poderá capturar credenciais (como nome de usuário e senha) inseridas pelos usuários no site clonado.</p>

    <hr>
    <footer>
        <p><strong>Disclaimer:</strong> Use esta ferramenta apenas em ambientes de teste e com permissão explícita. O phishing é ilegal sem o consentimento da vítima e é contra as regras de ética de segurança cibernética.</p>
    </footer>
</body>
</html>
