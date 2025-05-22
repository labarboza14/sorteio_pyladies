

# 🎁 Sorteio de Brindes Interativo no Google Colab

Seja bem-vinda! 👩‍💻✨

Este projeto foi criado para realizar **sorteios de brindes de forma interativa e visual** diretamente no **Google Colab**. Ele pode ser usado em eventos, workshops, encontros da comunidade ou em qualquer situação onde você queira sortear nomes a partir de uma planilha de participantes.

---

## 📌 O que esse código faz?

* Permite **fazer upload de uma planilha** com os dados dos participantes.
* Mostra todos os **participantes da lista (nome, telefone, e-mail)**.
* Com um clique em um botão, realiza o **sorteio de um nome aleatoriamente**.
* Mostra uma **mensagem estilizada** com o nome da pessoa sorteada.
* Pergunta se você deseja fazer um novo sorteio (via dropdown com "Sim" ou "Não").
* Vai **guardando os nomes sorteados** (sem duplicar ou repetir).
* Exibe os nomes já sorteados de forma visual e organizada.
* Quando você clicar em "Não", o sorteio será encerrado e todos os nomes sorteados serão exibidos como um histórico.

---

## ✅ Pré-requisitos

Você precisa apenas de:

* Conta no Google
* Navegador com acesso à internet
* Planilha com os participantes no formato `.csv` ou `.xlsx`

---

## 🧾 Como deve ser a planilha?

Ela deve ter **três colunas obrigatórias** (com os seguintes nomes exatos):

```
Nome, Telefone, Email
```

Exemplo:

| Nome           | Telefone        | Email                                     |
| -------------- | --------------- | ----------------------------------------- |
| Maria Oliveira | (11) 99999-0000 | [maria@gmail.com](mailto:maria@gmail.com) |
| Joana Souza    | (21) 98888-1111 | [joana@email.com](mailto:joana@email.com) |

---

## 🚀 Como usar o sorteio no Google Colab?

1. Acesse o [Google Colab](https://colab.research.google.com).
2. Cole o código do projeto em uma célula.
3. Rode a célula com `Shift + Enter`.
4. Quando solicitado, **faça o upload da sua planilha de participantes**.
5. Clique no botão **"Sortear Brinde"**.
6. Após cada sorteio, use o menu dropdown para decidir se deseja sortear outro nome.
7. Quando terminar, escolha "Não" e veja o resultado final com todos os nomes sorteados! 🎉

---

## 💡 Explicação técnica (resumo simples)

### Estrutura geral do código:

* Usa **Python com pandas** para ler e tratar os dados.
* Usa **IPython widgets** para criar botões e menus interativos no Colab.
* Usa **HTML embutido** para deixar a interface mais bonita e amigável.
* As funções estão organizadas para manter o sorteio controlado e repetir enquanto houver participantes disponíveis.

### Principais blocos:

* `carregar_planilha()` – lê o arquivo enviado.
* `sortear()` – escolhe um nome aleatório da lista restante.
* `mostrar_participantes()` – exibe todos os nomes no início.
* `mostrar_sorteados()` – exibe só os nomes sorteados até agora.
* `on_botao_click()` – controla o que acontece quando o botão é clicado.
* `on_dropdown_change()` – decide o que fazer quando a pessoa escolhe "Sim" ou "Não" no menu.

---

## 💬 Dicas para quem está começando

🌟 Se você é uma mulher em início de carreira em dados ou programação, parabéns por estar aqui!

* **Não tenha medo de experimentar.** Altere o código, teste com novas ideias e veja o que acontece!
* **Comente o código para estudar.** Leia cada função e escreva ao lado o que você entendeu.
* **Participe de comunidades como PyLadies.** Aprender com outras mulheres pode ser muito inspirador.
* Se tiver dúvidas, pesquise por termos como `pandas`, `widgets`, `Google Colab interatividade`.


