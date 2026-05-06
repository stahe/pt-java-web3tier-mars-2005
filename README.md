# Arquiteturas web de três camadas e MVC com Struts, Spring e Java

🔗 **Documento relacionado:**
[Arquiteturas de três camadas e MVC com Struts, Spring e Java](https://stahe.github.io/pt-java-web3tier-mars-2005/)

---

## 📘 Introdução

Este repositório reúne o conteúdo de dois artigos publicados entre março e julho de 2005 no Developpez.com.
Neles, exploram-se as arquiteturas web Java através de uma abordagem didática e passo a passo:

1. **Spring IoC**
   Uma introdução à **inversão de controlo (IoC)**, também conhecida como **injeção de dependências (DI)**, utilizando o framework Spring.

2. **Três exemplos de arquiteturas web de três camadas**
   Apresentação de uma aplicação web simplificada para gerir compras online, implementada utilizando uma arquitetura **MVC (Modelo-Vista-Controlador)** e apresentada em três variantes técnicas.

---

## 🏗️ Arquiteturas abordadas

A aplicação de exemplo está estruturada de acordo com uma arquitetura **de três camadas**:

* **Camada de apresentação**
* **Camada de lógica de negócio**
* **Camada de acesso aos dados**

O modelo **MVC** é implementado de três formas diferentes:

### 1️⃣ Servlet + JSP

* Um **servlet controlador**
* **Páginas JSP** para as vistas
* Arquitetura MVC manual

### 2️⃣ Struts

* Implementação MVC baseada no framework **Struts**
* Controlo centralizado através do `ActionServlet`
* Mapeamento declarativo de ações

### 3️⃣ Spring MVC

* Utilização do framework **Spring MVC**
* Integração com o contentor IoC do Spring
* Configuração orientada para a injeção de dependências

---

## 🎯 Objetivos de aprendizagem

* Compreender o princípio da **arquitetura de três camadas**
* Dominar o **modelo MVC num ambiente web Java**
* Descobrir a **inversão de controlo (IoC)** e a injeção de dependências
* Comparar diferentes abordagens para a implementação de MVC
* Compreender as vantagens das estruturas em relação a uma implementação manual

---

## 🧩 Tecnologias utilizadas

* Java
* Servlets
* JSP
* Struts
* Spring Framework
* Spring MVC

---

## 📚 Público-alvo

Este material destina-se a:

* Desenvolvedores Java que desejam compreender as arquiteturas web tradicionais
* Qualquer pessoa que pretenda comparar o MVC «manual» e o MVC baseado em frameworks

---

## 🏷️ Contexto histórico

Estes artigos datam de 2005 e refletem o estado das práticas web em Java naquela altura.

Serge Tahé, março de 2005