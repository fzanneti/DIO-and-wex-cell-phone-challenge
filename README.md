# WEX - End to End Engineering

## Desafio: Programação Orientada a Objetos com .NET

![GitHub repo size](https://img.shields.io/github/repo-size/fzanneti/dio-and-wex-cell-phone-challenge)
![GitHub forks](https://img.shields.io/github/forks/fzanneti/dio-and-wex-cell-phone-challenge?style=social)
![GitHub Repo stars](https://img.shields.io/github/stars/fzanneti/dio-and-wex-cell-phone-challenge?style=social)
![Linguagem](https://img.shields.io/badge/Linguagem-CSharp-blue)
![Bootcamp](https://img.shields.io/badge/WEX-End--to--End%20Engineering-blueviolet?logo=vercel&logoColor=white)
![Plataforma](https://img.shields.io/badge/Powered%20by-DIO.io-red?logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZmZmIiB2aWV3Qm94PSIwIDAgMzIgMzIiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTYuNzEgMy4yNWMtMi44OCAxLjQxLTUuMDcgNC4yMy01LjA3IDcuNzYgMCAzLjU4IDIuMjggNi43IDUuMzMgOC4xNSAxLjgzLS42MiAyLjQtMi4yNiAyLjQtMy44MSAwLS4yMy0uMDItLjQ1LS4wNS0uNjZBLjQ0LjQ0IDAgMDExMC4xIDExYy4yNC0uNzUuMTEtMS41My0uMy0yLjIyQzguOTIgNy45NiA3LjMzIDcuNSA1Ljc0IDcuNjZhNS41NSA1LjU1IDAgM)
![Autor](https://img.shields.io/badge/Autor-fzanneti-blue?style=flat-square&logo=github)

---

### 📋 Descrição do Desafio

Neste projeto, o objetivo é aplicar os fundamentos da Programação Orientada a Objetos (POO) em .NET, utilizando conceitos como **abstração**, **herança** e **polimorfismo**.

O desafio consiste em desenvolver um sistema de console que simula o funcionamento básico de celulares, modelando diferentes marcas e seus comportamentos específicos.

---

### Requisitos Técnicos

- A classe `Smartphone` deve ser **abstrata** e servir como modelo base para os demais celulares.
- As classes `Nokia` e `Iphone` devem **herdar** da classe `Smartphone`.
- O método `InstalarAplicativo` deve ser **sobrescrito** em cada uma das subclasses (`Nokia` e `Iphone`), simulando diferentes formas de instalação.

---

### Estrutura de Classes

```

Smartphone (abstrata)
│
├──> Nokia : Smartphone
│     └──> Sobrescreve o método InstalarAplicativo
│
└──> Iphone : Smartphone
└──> Sobrescreve o método InstalarAplicativo

```

---

### Funcionalidades Implementadas

* Criação de uma instância do `Nokia` e do `Iphone`
* Chamada dos métodos:

  * `Ligar()`
  * `ReceberLigacao()`
  * `InstalarAplicativo(string nome)`

---

### Conceitos Trabalhados

* Abstração
* Herança
* Polimorfismo
* Classes e Métodos
* Sobrescrita de métodos (`override`)
* Encapsulamento

---

### Observações

O código original fornecido pela DIO estava incompleto, com marcações `// TODO`. A proposta foi completada conforme as regras exigidas no enunciado e está disponível neste repositório.

---

### Desafio Vinculado ao Curso - DIO X WEX - End to End Engineering

[![Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=fzanneti&repo=DIO-wex-e2e-csharp&bg_color=261d31&border_color=7a49c6&show_icons=true&icon_color=7a49c6&title_color=37ccab&text_color=FFF)](https://github.com/fzanneti/DIO-wex-e2e-csharp)

---

### Certificado

<img src="https://github.com/fzanneti/DIO-wex-e2e-csharp/blob/main/Assets/images/certificados/21-criando-um-sistema-e-abstraindo-um-celular-com-poo-em-CSharp.jpg" alt="Certificado" width="600px">

---

##### ✍️ Seção criada por: *Fabio Zanneti* - 🎯 Bootcamp: **WEX - End to End Engineering**
[![GitHub](https://img.shields.io/badge/GitHub-fzanneti-181717?style=flat&logo=github)](https://github.com/fzanneti)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-fzanneti-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/fzanneti)
