# 🎯 Jogo do Número Secreto

Um jogo simples e interativo onde o usuário deve adivinhar um número secreto entre 1 e 100. O jogo dá dicas se o número é maior ou menor que o chute do jogador, e utiliza síntese de voz para tornar a experiência mais divertida.

---

## 🕹️ Como jogar

1. Ao iniciar o jogo, uma mensagem pedirá que você escolha um número entre 1 e 100.
2. Digite seu palpite no campo de entrada.
3. O jogo responderá com:
   - “Acertou!” se você descobrir o número secreto.
   - “O número secreto é menor” ou “O número secreto é maior” para ajudar com a próxima tentativa.
4. Após acertar, clique em **"Reiniciar Jogo"** para jogar novamente.

---

## 🧠 Tecnologias usadas

- **HTML, CSS e JavaScript**
- **[ResponsiveVoice](https://responsivevoice.org/)** (síntese de voz em português)

---

## 🔁 Funcionalidades

- Geração de número aleatório sem repetição até o limite de 100.
- Feedback interativo com texto e voz.
- Contador de tentativas.
- Botão de reinício para uma nova rodada.

---

## 💻 Como executar localmente

1. Clone este repositório ou copie os arquivos para uma pasta local.
2. Crie um arquivo HTML que inclua os elementos:
   - Um campo de entrada para o palpite.
   - Um botão para verificar o chute.
   - Um botão para reiniciar.
3. Importe o script da **ResponsiveVoice** no seu HTML:
   ```html
   <script src="https://code.responsivevoice.org/responsivevoice.js?key=YOUR_KEY"></script>
   ```
4. Abra o arquivo HTML no navegador.

---

## 📂 Exemplo de estrutura HTML mínima

```html
<h1></h1>
<p></p>
<input type="number" />
<button onclick="verificarChute()">Chutar</button>
<button id="reiniciar" onclick="reiniciarJogo()" disabled>Reiniciar Jogo</button>

<script src="seu-script.js"></script>
<script src="https://code.responsivevoice.org/responsivevoice.js?key=YOUR_KEY"></script>
```

---

## 👤 Autor

Carlos Calvo

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usá-lo e modificá-lo.
