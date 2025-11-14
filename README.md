# 🟢 Gerador de Senhas de Atendimento

Oi! 👋 Eu sou a **Fabiolazg** e esse é o **Gerador de Senhas de Atendimento**.  
Ele serve para gerar senhas organizadas por turno (manhã e tarde) e exportar tudo em PDF. Perfeito para clínicas, consultórios ou qualquer lugar que precise organizar filas de atendimento.  

> 💡 **Dica:** Esse projeto é totalmente **personalizável**! Você pode mudar cores, horários, número de senhas e até o layout do PDF para se encaixar na sua realidade.

---

## 🖥️ Como usar

1. Abra a página `index.html`.  
2. Escolha a **data que você quer gerar as senhas**.  
3. Clique em **Gerar PDF** ou pressione **Enter**.  
4. O PDF vai ser criado com **10 senhas por turno**: manhã e tarde, cada turno em uma página.

---

## ⚙️ Como personalizar

Você pode mexer em várias partes do projeto para adaptá-lo:

- **Horários**: altere os arrays `horariosManha` e `horariosTarde` no script do PDF.  
- **Número de senhas**: ajuste o loop dentro da função `gerarSenhas()`.  
- **Layout do PDF**: mude `largura`, `altura`, `margem` e fontes (`doc.setFont`, `doc.setFontSize`).  
- **Visual da página**: tudo está em `style.css` — cores, fontes, bordas e responsividade podem ser alteradas.  
- **Logo e título**: coloque a sua logozinha no topo da página e como favicon.  

---

## 🛠️ Estrutura do projeto

/site-senhas
│
├─ index.html <- Página principal do gerador de senhas
├─ style.css <- CSS para o layout
├─ logo.png <- Logozinha e favicon
└─ README.md <- Este arquivo explicativo

---

## 🎨 Tecnologias usadas

- HTML5  
- CSS3  
- JavaScript (com jsPDF para gerar PDF)  
- jsPDF (gera PDFs direto no navegador)  

---

## 💡 Sugestões de melhorias

- Adicionar **tema claro/escuro** para a página.  
- Permitir **quantidade de senhas por turno configurável**.  
- Salvar os PDFs com **nome customizado pelo usuário**.  
- Criar **botões de download separado** para cada turno.  

---

## 🔹 Dicas finais

Este projeto é **leve, simples e fácil de mexer**.  
Você pode alterar cores, horários, textos e logos sem quebrar nada.  
É perfeito tanto para aprendizado quanto para uso prático em pequenos estabelecimentos.

---

## 👩‍💻 Contato

Feito com ❤️ por **Fabiolazg**.  
Se você tiver dúvidas ou sugestões, é só abrir uma issue ou entrar em contato!
