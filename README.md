# 🛡️ Phishing — Laboratório Educacional

## 📌 Sobre o projeto

Este projeto apresenta um laboratório prático desenvolvido para estudar o funcionamento de ataques de **Phishing** e compreender como páginas fraudulentas podem ser utilizadas para induzir usuários ao fornecimento de informações.

O laboratório foi desenvolvido em um ambiente controlado utilizando **Kali Linux**, com o objetivo de compreender o fluxo de um ataque de engenharia social e, principalmente, estudar formas de identificação e prevenção.

> ⚠️ **Aviso:** este projeto possui finalidade exclusivamente educacional. Não são utilizadas credenciais reais e nenhum dado de terceiros é coletado.

---

## 🎯 Objetivos

* Compreender o conceito de Phishing;
* Estudar Engenharia Social;
* Conhecer o funcionamento de páginas falsas;
* Entender requisições HTTP e POST;
* Trabalhar com ambiente de laboratório no Kali Linux;
* Observar como um servidor web recebe requisições;
* Identificar possíveis indicadores de uma página fraudulenta;
* Desenvolver conhecimentos de prevenção e conscientização em segurança.

---

## 🧠 O que é Phishing?

**Phishing** é uma técnica de engenharia social utilizada para enganar uma pessoa fazendo com que ela acredite estar interagindo com uma entidade legítima.

O atacante pode utilizar elementos como:

* páginas visualmente semelhantes às originais;
* mensagens fraudulentas;
* links maliciosos;
* domínios semelhantes aos legítimos;
* formulários falsos;
* técnicas de manipulação psicológica.

O objetivo pode ser induzir a vítima a realizar uma ação que beneficie o atacante.

---

## 🔬 Ambiente do Laboratório

O laboratório foi desenvolvido em ambiente isolado utilizando:

* 🐧 Kali Linux
* 🌐 Servidor web local
* 📝 HTML/CSS
* 🧪 Página fictícia para simulação
* 🔎 Ferramentas de segurança para análise

A aplicação é executada localmente para evitar interação com usuários ou sistemas externos.

---

## 📡 Conceito de HTTP POST

Durante o estudo foi analisada a utilização do método HTTP `POST`.

Diferentemente de uma requisição `GET`, utilizada normalmente para solicitar recursos, uma requisição `POST` pode transportar dados enviados por um formulário para o servidor.

Fluxo simplificado:

```text
Usuário
   ↓
Página web
   ↓
Preenchimento do formulário
   ↓
HTTP POST
   ↓
Servidor
   ↓
Processamento dos dados
```

No laboratório, esse conceito é utilizado apenas com **dados fictícios**.

---

## 🧪 Estrutura do Projeto

```text
phishing-lab/
│
├── index.html
├── README.md
└── ...
```

O arquivo `index.html` representa a interface da página utilizada durante a simulação.

---

## 🔐 Segurança e Ética

O projeto foi desenvolvido seguindo uma abordagem de **Ethical Hacking**.

Não devem ser utilizados:

* credenciais reais;
* contas de terceiros;
* informações pessoais;
* páginas destinadas a enganar usuários reais;
* infraestrutura pública sem autorização.

Todos os testes devem permanecer dentro de um ambiente controlado e autorizado.

---

## 🛡️ Como identificar Phishing

Alguns sinais comuns incluem:

* URL diferente do domínio oficial;
* erros ortográficos ou linguagem incomum;
* solicitação inesperada de credenciais;
* mensagens com urgência ou ameaça;
* links suspeitos;
* certificados ou conexões inesperadas;
* páginas que imitam serviços conhecidos.

A melhor defesa contra Phishing combina **conscientização do usuário, autenticação multifator, filtros de segurança e análise cuidadosa de links e domínios**.

---
## 🧩 **Teste**

<img width="2560" height="1300" alt="03" src="https://github.com/user-attachments/assets/9820a810-f912-4ecd-8fa5-154e86eee2f2" />

<img width="1256" height="1010" alt="01" src="https://github.com/user-attachments/assets/58f6d264-a248-4c0b-9048-c3124a78a526" />

<img width="1831" height="560" alt="05" src="https://github.com/user-attachments/assets/e23fe5a3-62a3-41cf-9541-10eef0258b7d" />

---

## 📚 Aprendizados

Este laboratório permitiu estudar conceitos relacionados a:

* Cybersecurity;
* Ethical Hacking;
* Engenharia Social;
* Phishing;
* HTTP;
* HTTP POST;
* servidores web;
* Kali Linux;
* análise de requisições;
* segurança de aplicações web.

---

## ⚠️ Disclaimer

Este projeto foi criado exclusivamente para **estudo, treinamento e conscientização em segurança da informação**.

O uso das técnicas apresentadas contra sistemas, contas ou pessoas sem autorização pode ser ilegal e causar danos.

**Utilize somente em ambientes próprios ou explicitamente autorizados.**
