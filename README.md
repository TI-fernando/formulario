# Formulário com Validação

Este é um projeto de um **formulário com validação em JavaScript puro**, proposto pelo pessoal do curso DevEmDobro. Ele valida se todos os campos obrigatórios foram preenchidos antes de enviar os dados.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## Funcionalidades

✅ Validação de campos obrigatórios ✅ Altera a borda dos campos para vermelho se não estiverem preenchidos ✅ Exibe uma mensagem de "Campo obrigatório" abaixo do input vazio ✅ Muda a borda do campo para verde quando preenchido corretamente ✅ Estilização responsiva

## Estrutura do Projeto

```
/
|-- src/
|   |-- css/
|   |   |-- reset.css
|   |   |-- style.css
|   |-- img/
|   |-- js/
|   |   |-- index.js
|-- index.html
|-- README.md
```

## Como Rodar o Projeto

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Abra o arquivo `index.html` no navegador

## Como Funciona a Validação

O JavaScript adiciona classes CSS aos campos conforme a validação:

- Se o campo estiver **preenchido**, ele recebe a classe `.valido` (borda verde)
- Se o campo estiver **vazio**, ele recebe a classe `.invalido` (borda vermelha) e a mensagem de erro é exibida

## Contribuição

1. Faça um fork do repositório
2. Crie um branch para sua feature (`git checkout -b minha-feature`)
3. Commit suas modificações (`git commit -m 'Adicionando nova feature'`)
4. Envie para o branch principal (`git push origin minha-feature`)
5. Abra um Pull Request

---

Desenvolvido com ❤️ por [Fernando Henrique](https://github.com/TI-fernando)

