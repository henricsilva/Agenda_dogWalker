# 🐾 DogWalker Agenda

Sistema simples de agendamento de passeios para cães, feito com **HTML, CSS e JavaScript puro**, usando `localStorage` para salvar os dados no navegador.

---

## 📌 Funcionalidades

* 👤 **Área do Cliente**

  * Agendar passeio informando:

    * Nome do cliente
    * Nome do pet
    * Data e hora

* 🔐 **Painel do Gestor**

  * Login com senha
  * Visualizar todos os agendamentos
  * Confirmar passeios
  * Excluir registros

* 💾 **Persistência de dados**

  * Os agendamentos ficam salvos no navegador usando `localStorage`

* 📱 **Layout responsivo**

  * Adaptado para celular e desktop

---

## 🔑 Acesso ao Painel do Gestor

Senha padrão:

```
dog123
```

---

## 🛠 Tecnologias utilizadas

* HTML5
* CSS3 (com variáveis e responsividade)
* JavaScript (DOM + LocalStorage)

---

## 🚀 Como executar o projeto

1. Baixe ou copie o arquivo `index.html`
2. Abra o arquivo diretamente no navegador
3. Pronto! O sistema já estará funcionando

---

## 📂 Estrutura do projeto

```
/dogwalker-agenda
 └── index.html
```

---

## 🧠 Lógica principal

* Os dados são armazenados em:

```js
localStorage.getItem('dogwalker_dados')
```

* Cada agendamento possui:

```js
{
  id,
  cliente,
  pet,
  data,
  hora,
  status
}
```

---

## ✨ Melhorias futuras (opcional)

* Autenticação com múltiplos gestores
* Filtro por data ou status
* Exportar agenda em PDF
* Integração com backend (Firebase / API)

---

## 📄 Licença

Projeto livre para fins educacionais e acadêmicos.

---

Se quiser, posso:
✔ Adaptar esse README para **GitHub**
✔ Criar uma versão em inglês
✔ Gerar um logo ou banner do projeto
✔ Ou transformar isso num projeto com backend 😎
