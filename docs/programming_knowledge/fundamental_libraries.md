# Bibliotecas e Ferramentas Fundamentais para a Aurora

Este documento serve como um guia de referência para a Aurora, detalhando as bibliotecas e frameworks essenciais em cada linguagem de programação que ela domina. O objetivo é garantir que a Aurora utilize as ferramentas mais eficazes e padronizadas para o desenvolvimento de software, alinhando-se com as melhores práticas da indústria e as preferências de Arthur Emanuel Forster.

## ☕ Java

Para desenvolvimento Java, a Aurora deve priorizar as seguintes bibliotecas e frameworks, focando em robustez, escalabilidade e performance:

| Categoria | Biblioteca/Framework | Descrição | Uso Principal |
|---|---|---|---|
| **Core** | **Java Standard Library (JCL)** | Conjunto de bibliotecas que acompanham o JDK, fornecendo funcionalidades básicas. | Operações de I/O, coleções, networking, utilitários. |
| **Framework Web** | **Spring Boot** | Framework para construção rápida de aplicações Java, com foco em microsserviços e REST APIs. | Desenvolvimento de backend, APIs RESTful, aplicações empresariais. |
| **Persistência** | **Hibernate** | Framework ORM (Object-Relational Mapping) para mapeamento de objetos Java para bancos de dados relacionais. | Gerenciamento de dados, interação com bancos de dados. |
| **Testes** | **JUnit** | Framework de testes unitários para Java. | Testes de unidade e integração. |
| **Testes** | **Mockito** | Framework de mocking para testes unitários, permitindo simular dependências. | Criação de mocks para testes isolados. |
| **Utilitários** | **Apache Commons** | Coleção de bibliotecas reutilizáveis para tarefas comuns. | Manipulação de strings, I/O, coleções, etc. |
| **Utilitários** | **Guava (Google)** | Biblioteca de utilitários do Google para Java, com foco em coleções, caching, concorrência. | Melhorias em coleções, caching, programação funcional. |
| **Logging** | **SLF4J + Logback/Log4j2** | Abstração de logging (SLF4J) com implementações eficientes. | Registro de eventos e depuração. |

## 🟦 TypeScript

Para TypeScript, a Aurora deve focar em ferramentas que garantam segurança de tipo, produtividade e integração com o ecossistema JavaScript:

| Categoria | Biblioteca/Framework | Descrição | Uso Principal |
|---|---|---|---|
| **Core** | **TypeScript Standard Library** | Tipos embutidos e definições para APIs JavaScript padrão. | Tipagem estática, segurança de código. |
| **Utilitários de Tipo** | **`ts-toolbelt`** | Maior biblioteca de utilitários de tipo para TypeScript. | Manipulação avançada de tipos, metaprogramação de tipos. |
| **Framework Backend** | **NestJS** | Framework progressivo para Node.js, construído com TypeScript, para aplicações backend escaláveis. | Desenvolvimento de APIs RESTful, microsserviços, GraphQL. |
| **Framework Backend** | **Express.js (com tipos)** | Framework web minimalista e flexível para Node.js, com definições de tipo para TypeScript. | Criação de servidores web e APIs. |
| **Validação** | **Zod / Yup** | Bibliotecas de validação de schema para garantir a integridade dos dados. | Validação de entrada de dados (formulários, APIs). |

## ⚛️ React

No ecossistema React, a Aurora deve dominar as bibliotecas que otimizam a construção de UI, gerenciamento de estado e performance:

| Categoria | Biblioteca/Framework | Descrição | Uso Principal |
|---|---|---|---|
| **Core** | **React** | Biblioteca JavaScript para construção de interfaces de usuário. | Desenvolvimento de componentes UI. |
| **Gerenciamento de Estado** | **Zustand / Jotai** | Bibliotecas leves e flexíveis para gerenciamento de estado global. | Gerenciamento de estado de aplicações complexas. |
| **Gerenciamento de Estado** | **React Query / SWR** | Bibliotecas para gerenciamento de estado de servidor (data fetching, caching, sincronização). | Otimização de requisições de dados, caching. |
| **Roteamento** | **React Router** | Biblioteca padrão para roteamento declarativo em aplicações React. | Navegação entre páginas/componentes. |
| **UI Components** | **MUI (Material UI)** | Biblioteca de componentes React que implementa o Material Design do Google. | Construção rápida de interfaces com design consistente. |
| **UI Components** | **Radix UI** | Primitivos de UI sem estilo para construir sistemas de design acessíveis. | Criação de componentes UI customizados e acessíveis. |
| **Estilização** | **Tailwind CSS** | Framework CSS utility-first para construção rápida de designs customizados. | Estilização de componentes, design responsivo. |
| **Estilização** | **Styled Components** | Biblioteca para escrever CSS dentro do JavaScript, com componentes estilizados. | Estilização baseada em componentes, encapsulamento de estilos. |
| **Testes** | **React Testing Library** | Ferramenta para testar componentes React de forma que simule o uso real do usuário. | Testes de unidade e integração de componentes. |

## 🐍 Python

Para Python, a Aurora deve ter proficiência em bibliotecas para automação, análise de dados, IA e desenvolvimento web:

| Categoria | Biblioteca/Framework | Descrição | Uso Principal |
|---|---|---|---|
| **Core** | **Python Standard Library** | Módulos embutidos para diversas tarefas. | Operações de sistema, I/O, estruturas de dados. |
| **Numérico/Científico** | **NumPy** | Biblioteca fundamental para computação numérica, com suporte a arrays e matrizes. | Operações matemáticas, processamento de dados. |
| **Análise de Dados** | **Pandas** | Biblioteca para manipulação e análise de dados, com DataFrames. | Limpeza, transformação e análise de dados. |
| **Visualização** | **Matplotlib / Seaborn** | Bibliotecas para criação de gráficos e visualizações de dados. | Geração de gráficos estatísticos e informativos. |
| **Machine Learning** | **Scikit-learn** | Biblioteca abrangente para algoritmos de Machine Learning. | Classificação, regressão, clustering, pré-processamento. |
| **Deep Learning** | **TensorFlow / PyTorch** | Frameworks líderes para construção e treinamento de redes neurais. | Desenvolvimento de modelos de Deep Learning. |
| **Web Framework** | **FastAPI** | Framework web moderno e rápido para construir APIs com Python 3.7+. | Desenvolvimento de APIs RESTful de alta performance. |
| **Web Framework** | **Django** | Framework web de alto nível para desenvolvimento rápido e seguro. | Aplicações web complexas, com ORM e admin panel. |
| **Automação** | **Requests** | Biblioteca HTTP para fazer requisições web de forma simples. | Interação com APIs, web scraping. |
| **Automação** | **BeautifulSoup4** | Biblioteca para parsing de HTML/XML. | Web scraping, extração de dados de páginas web. |

## 🎮 Luau (Roblox)

Para Luau, a Aurora deve focar nas APIs e frameworks que otimizam o desenvolvimento de experiências no Roblox:

| Categoria | Biblioteca/Framework | Descrição | Uso Principal |
|---|---|---|---|
| **Core** | **Luau Standard Library** | Funções e tipos embutidos da linguagem Luau. | Manipulação de dados, operações básicas. |
| **Roblox API** | **`game` object** | Objeto global que dá acesso a todos os serviços e objetos do Roblox Studio. | Interação com o ambiente Roblox (players, world, UI). |
| **Framework de Jogo** | **Knit** | Framework leve para desenvolvimento de jogos no Roblox, focado em modularidade e comunicação cliente-servidor. | Estruturação de projetos de jogos, comunicação remota. |
| **Utilitários** | **Roact** | Implementação do React para Roblox, permitindo UI declarativa. | Construção de interfaces de usuário no Roblox. |
| **Utilitários** | **Rodux** | Implementação do Redux para Roblox, para gerenciamento de estado. | Gerenciamento de estado de aplicações complexas no Roblox. |

## 📚 Manutenção e Atualização

A Aurora deve monitorar ativamente os repositórios oficiais, documentações e comunidades de cada uma dessas bibliotecas e frameworks para se manter atualizada sobre novas versões, melhores práticas e tendências. O aprendizado contínuo é essencial para garantir que ela sempre utilize as ferramentas mais eficazes e seguras.

---
*Documento elaborado por Manus AI, sob a supervisão de Arthur Emanuel Forster (Notty0001).*
