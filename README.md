# 🎮 Jogo do Número Secreto

Um jogo interativo desenvolvido em **JavaScript** onde você precisa adivinhar um número secreto recebendo dicas ao longo do jogo.

## 📖 Sobre o Projeto

Projeto educacional da **Alura** que explora conceitos fundamentais de programação em JavaScript através de um jogo divertido e interativo.

## � Gameplay

1. Um número aleatório entre 1 e 5000 é gerado
2. Você recebe um prompt solicitando um palpite
3. A cada tentativa, o jogo fornece dicas:
   - ⬆️ "O número secreto é maior que X"
   - ⬇️ "O número secreto é menor que X"
4. Quando acerta, o jogo mostra o número de tentativas usadas

## 🚀 Como Jogar

1. Abra `index.html` no seu navegador
2. Confirme a mensagem de boas-vindas
3. Digite seus palpites nos prompts que aparecem
4. Descubra o número secreto!

## 📂 Arquivos do Projeto

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Estrutura HTML da página |
| `app.js` | Lógica do jogo em JavaScript |
| `style.css` | Estilos e layout |
| `README.md` | Este arquivo |
| `img/` | Imagens do projeto |

## 💻 Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📚 Conceitos JavaScript Utilizados

- **Variáveis** (`let`, atribuição)
- **Tipos de Dados** (number, string)
- **Operadores** (comparação, lógicos, aritméticos)
- **Estruturas de Controle** (`while`, `if/else`, ternário)
- **Métodos Built-in** (`Math.random()`, `parseInt()`)
- **Template Literals** (backticks com `${}`)
- **Funções de I/O** (`prompt()`, `alert()`)
- **Console** (`console.log()`)

## � Modificações Sugeridas

Experimente aprimorar o projeto:

- Adicionar diferentes níveis de dificuldade
- Implementar um limite de tentativas
- Salvar o histórico de jogos
- Criar uma interface visual com elementos DOM
- Adicionar animações e sons
- Adicionar um sistema de pontuação

## 📝 Exemplos de Código

**Geração do número aleatório:**
```javascript
let numeroSecreto = parseInt(Math.random() * numeroMaximo + 1);
```

**Loop principal:**
```javascript
while (chute != numeroSecreto) {
    chute = prompt(`Escolha um número entre 1 e ${numeroMaximo}`);
    // Lógica de verificação...
}
```

## 🎓 Para Aprender Mais

- [MDN - JavaScript Basics](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Documentação Alura](https://www.alura.com.br)

---

**Desenvolvido durante o curso "Lógica de Programação com JavaScript" - Alura** ✨
