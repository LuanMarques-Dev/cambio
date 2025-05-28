<body>

  <h1>💱 Casa de Câmbio - Conversor de Moedas</h1>

  <p>
    Este é um projeto simples de conversor de moedas feito com <strong>HTML</strong>, <strong>CSS</strong> e <strong>JavaScript</strong>,
    com foco na manipulação e interação via JavaScript puro (Vanilla JS).
    Ele simula a conversão de moedas estrangeiras (USD, EUR, GBP) para <strong>Reais (BRL)</strong> com uma interface moderna e funcional.
  </p>

  <h2>🎯 Funcionalidades</h2>
  <ul>
    <li>Escolha entre Dólar Americano (USD), Euro (EUR) e Libra Esterlina (GBP).</li>
    <li>Digite um valor e clique em <strong>"Converter em reais"</strong>.</li>
    <li>Exibe a cotação da moeda selecionada e o valor convertido para BRL.</li>
    <li>Previne a entrada de caracteres inválidos no campo de valor.</li>
    <li>Interface responsiva e moderna.</li>
  </ul>

  <h2>🔧 Tecnologias Utilizadas</h2>
  <ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>JavaScript (ES6)</li>
  </ul>

  <h2>🧠 Lógica do JavaScript</h2>
  <ul>
    <li>Valida o campo de valor para aceitar apenas números.</li>
    <li>Utiliza taxas de câmbio fixas para conversão:</li>
  </ul>
  <pre><code>const USD = 4.87;
const EUR = 5.32;
const GBP = 6.08;
  </code></pre>
  <ul>
    <li>Formata o resultado no padrão monetário brasileiro (<code>pt-BR</code>).</li>
    <li>Apresenta o resultado de forma clara e acessível ao usuário.</li>
  </ul>

</body>
