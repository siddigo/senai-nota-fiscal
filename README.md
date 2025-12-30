# 🧾 SENAI – Sistema de Nota Fiscal (POO)

Este projeto foi desenvolvido com fins **educacionais**, como parte do aprendizado de **Programação Orientada a Objetos (OOP/POO)**.

O objetivo é simular o funcionamento básico de uma **nota fiscal**, utilizando classes que representam entidades distintas e que se comunicam entre si.

---

## 🎯 Objetivo do Projeto

- Praticar conceitos fundamentais de **POO**
- Trabalhar com **composição entre classes**
- Simular um problema do mundo real de forma estruturada
- Desenvolver lógica de cálculo e formatação de saída

---

## 🧠 Conceitos Aplicados

- Classes e Objetos  
- Encapsulamento  
- Métodos e atributos  
- Comunicação entre objetos  
- Organização e responsabilidade de classes  

---

## 🏗️ Estrutura Conceitual

O sistema é composto, principalmente, por duas classes:

### 📄 NotaFiscal
Responsável por:
- Armazenar os itens da nota
- Calcular o valor total
- Gerar a impressão da nota fiscal

### 📦 Item
Responsável por:
- Representar um produto/serviço
- Armazenar nome, quantidade e valor unitário
- Calcular seu valor total

A **NotaFiscal contém vários Itens**, caracterizando uma relação de **composição**.

---

## ⚙️ Funcionamento Geral

1. Criação de uma nota fiscal
2. Criação de itens
3. Adição dos itens à nota
4. Cálculo automático do total
5. Impressão da nota com todos os itens e valor final

---

## 🧪 Finalidade Educacional

Este projeto **não tem objetivo comercial ou fiscal real**.  
Ele foi desenvolvido exclusivamente para:

- Aprendizado
- Exercícios de lógica
- Consolidação de conceitos de POO

---

## 📚 Contexto

Projeto desenvolvido no contexto de estudos no **SENAI**, como parte da formação em lógica de programação e orientação a objetos.

---

## 🧩 Próximos Passos (opcional)

Possíveis evoluções didáticas:
- Aplicar herança para tipos diferentes de itens
- Persistência em arquivo
- Interface gráfica ou console mais elaborada
- Cálculo de impostos

---

📌 Projeto simples, mas fundamental para a compreensão de **modelagem orientada a objetos**.

---

## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
