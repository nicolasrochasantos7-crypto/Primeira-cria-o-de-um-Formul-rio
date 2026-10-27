# 📍 Formulário de Endereço com Busca Automática de CEP

Projeto desenvolvido para praticar conceitos de desenvolvimento Front-end, com foco na criação de um formulário de endereço e na integração com uma API externa para consulta automática de CEP.

## 🚀 Funcionalidades

- **Formulário de endereço:** campos para preenchimento dos dados de entrega.
- **Consulta automática de CEP:** integração com a API [ViaCEP](https://viacep.com.br/) para buscar informações do endereço.
- **Validação de CEP:** verificação do preenchimento dos 8 dígitos antes de realizar a consulta.
- **Preenchimento automático:** utilização dos dados retornados pela API para facilitar o preenchimento do endereço.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- API ViaCEP

## ⚙️ Como funciona

O usuário informa um CEP de 8 dígitos no formulário. Após a validação do campo, o JavaScript realiza uma requisição à API ViaCEP para consultar o endereço correspondente.

Os dados retornados são utilizados para preencher automaticamente os campos de endereço, tornando o processo mais prático.

Atualmente, o JavaScript está incorporado ao arquivo HTML para facilitar a edição durante a fase inicial de desenvolvimento.

## 📌 Status do projeto

**Em desenvolvimento.**

Nesta primeira versão, o projeto contempla a interface Front-end e a consulta de CEP por meio de uma API externa.

A integração com banco de dados ainda não foi implementada. O formulário está sendo utilizado para testar e aprimorar a validação de dados e a consulta automática de endereços.

## 🔮 Próximas melhorias

- [ ] Separar o JavaScript em um arquivo independente.
- [ ] Aprimorar o tratamento de erros e as validações do formulário.
- [ ] Melhorar a responsividade e a experiência do usuário.
- [ ] Implementar a integração com banco de dados SQL.
- [ ] Desenvolver novas funcionalidades para o gerenciamento de endereços.

---

Desenvolvido como parte da minha jornada de aprendizado em desenvolvimento de software.
