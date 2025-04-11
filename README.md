# 🚴‍♂️ Bikcraft - Site Responsivo com Formulário PHP + PHPMailer

Este é um projeto completo de site institucional fictício da **Bikcraft**, desenvolvido com foco em front-end responsivo e integração de formulário com envio de e-mail via **PHPMailer**.

---

## 🌐 Visão Geral

O projeto apresenta um site totalmente responsivo com as seguintes seções:

- Página inicial (`index.html`)
- Página sobre a empresa (`sobre.html`)
- Página de produtos (`produtos.html`)
- Página de portfólio (`portfolio.html`)
- Página de contato com formulário funcional (`contato.html` + `enviar.php`)

---

## 🧰 Tecnologias Utilizadas

| Camada     | Tecnologias                     |
|------------|---------------------------------|
| Front-end  | HTML5, CSS3, JavaScript         |
| Back-end   | PHP (formulário de contato)     |
| E-mails    | PHPMailer + SMTP (Gmail)        |
| Layout     | Responsivo e acessível          |

---

## 📬 Funcionalidade: Formulário de Contato

O formulário envia os dados para o e-mail configurado via **SMTP (Gmail)** utilizando a biblioteca PHPMailer.

### ✉️ Parâmetros do `enviar.php`:

- `nome`, `email`, `telefone`, `mensagem`
- Anti-spam com `leaveblank` e `dontchange`
- Mensagem de retorno ao usuário em caso de sucesso ou falha

> ⚠️ **IMPORTANTE:** Não compartilhe sua senha do Gmail em repositórios públicos. Recomendado o uso de senhas de app específicas ou variáveis de ambiente.

---

## 🖥️ Como Executar Localmente

1. Clone o repositório
2. Configure o `enviar.php` com seu e-mail e senha de app do Gmail:
   ```php
   $email_envio = 'seuemail@gmail.com';
   $email_pass = 'suasenha';
   ```
3. Acesse `index.html` da pasta `4-HTML+CSS+RESPONSIVO+JS+PHPMAILER` para testar.

---

## 👨🏾‍💻 Autor
 
- **Linkedin:** [Eric Bueno](https://www.linkedin.com/in/ericfsbueno/)

---

## 📜 Licença
Este projeto está licenciado sob a licença MIT - sinta-se à vontade para reutilizar com os devidos créditos.

---

## Agradecimento
- [André Rafael](https://www.origamid.com/)