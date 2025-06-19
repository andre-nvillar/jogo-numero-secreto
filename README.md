# 🎯 Jogo do Número Secreto

Bem-vindo(a) ao **Jogo do Número Secreto**!  
Este projeto é um jogo interativo simples desenvolvido em **JavaScript**, onde o jogador tenta adivinhar um número secreto gerado aleatoriamente entre 1 e 10.  

Faz parte do meu processo de aprendizado e prática em lógica de programação, manipulação de DOM e interatividade com o usuário via navegador.  

---

## 🧠 Sobre o Projeto

A cada rodada, o sistema sorteia um número secreto aleatório (sem repetir até que todos sejam utilizados). O usuário deve tentar acertar esse número com base em dicas fornecidas na tela.

A aplicação fornece:

- Feedback em tempo real sobre o chute do usuário (maior ou menor que o número);
- Contador de tentativas;
- Mensagem de sucesso ao acertar o número;
- Botão para reiniciar o jogo;
- Mensagens faladas com a biblioteca `responsiveVoice` para acessibilidade e diversão.

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (puro)
- [responsiveVoice.js](https://responsivevoice.org/) (texto falado no navegador)

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/andre-nvillar/jogo-numero-secreto.git
   ```

2. Abra o arquivo `index.html` diretamente no seu navegador.

> Nenhuma instalação adicional é necessária. O jogo roda 100% no navegador!

---

## 📷 Exemplo de Funcionamento

```bash
Jogo do número secreto
Escolha um número entre 1 e 10
> Usuário digita 5

"O número secreto é menor"

> Usuário digita 2

"O número secreto é maior"

> Usuário digita 3

"Acertou!"
"Você descobriu o número secreto com 3 tentativas!"
```

---

## 📚 Aprendizados

- Uso de funções e escopo em JavaScript
- Manipulação de DOM com `querySelector` e `innerHTML`
- Uso de `Math.random()` e lógica para evitar repetição de números
- Condicionais, laços e contadores
- Criação de interface amigável com feedback de voz usando `responsiveVoice`

---

## 🎯 Próximos Passos

- Melhorar a interface com HTML/CSS responsivo
- Adicionar opção de mudar o intervalo (ex: 1 a 100)
- Armazenar histórico de tentativas ou recordes
- Melhorar acessibilidade para usuários com deficiência visual

---

## ✍️ Autor

Feito com entusiasmo por **André Novo Villar** 🚀  
[LinkedIn](https://www.linkedin.com/in/andr%C3%A9-luiz-novo-villar-silva-dos-santos-506458b1/) | [GitHub](https://github.com/andre-nvillar)

---

## 🏁 Considerações Finais

Este jogo foi uma maneira divertida de aplicar os fundamentos de JavaScript, trabalhando lógica, interação com o usuário e até acessibilidade.

Se quiser jogar, testar ou contribuir, fique à vontade!  
Sugestões e feedbacks são sempre bem-vindos. 😉
