# 🛒 Dicionário de Dados — Sistema Comercial Mercado Sara

## 📝 Descrição do Projeto
Este projeto consiste na modelagem de um banco de dados relacional para o **Mercado Sara**, um supermercado de médio porte com 6 frentes de caixa simultâneas, e na publicação do seu **dicionário de dados** como uma página web no **GitHub Pages**. O objetivo principal é percorrer o ciclo completo de um projeto de banco de dados: levantar requisitos e regras de negócio, modelar as entidades, documentar cada atributo e disponibilizar tudo em um endereço público.

Desenvolvido como parte da disciplina de **Modelagem de Banco de Dados (2026.2)**, do curso de Análise e Desenvolvimento de Sistemas da UNICID, sob orientação do **Prof. Dr. Diego Carvalho**, o projeto reúne:

* **Documento de Requisitos (v2.0):** 15 requisitos funcionais, 8 não funcionais, 7 regras de negócio e 5 políticas legais (LGPD, SEFAZ, CTN e Marco Civil), com matriz de rastreabilidade. Disponível para download na própria página.
* **DER:** diagrama entidade-relacionamento com zoom e arraste, aberto em um visualizador na página.
* **Script DDL:** criação das 19 tabelas em MySQL 8.0+, com chaves, restrições `CHECK` e integridade referencial `ON DELETE RESTRICT ON UPDATE CASCADE`.
* **Dicionário de Dados:** página com as 19 tabelas, mostrando para cada atributo a descrição, o tipo, as constraints, a classificação de privacidade (LGPD), a linhagem do dado e o controle de acesso (RBAC).

## 🚀 Tecnologias Utilizadas
* **Banco de Dados:** MySQL 8.0+ (InnoDB, `utf8mb4`), modelo na 3ª Forma Normal (3FN)
* **Linguagens:** HTML5, CSS3 e JavaScript
* **Bibliotecas:** Bootstrap 5.3.3 e Panzoom 4.6.0
* **Modelagem:** Mermaid (DER)
* **Ferramentas:** Git, GitHub e GitHub Pages
* **Modelos de IA:** Gemini e Claude

## 📊 Resultados e Aprendizados
O projeto resultou em um dicionário de dados navegável, publicado e acessível por um link público.

* **Requisitos e Regras de Negócio:** Aprendi a transformar necessidades do negócio em requisitos funcionais, não funcionais, regras e políticas rastreáveis, ligando cada requisito às entidades e restrições do banco.
* **Modelagem Relacional:** Normalizei o modelo até a 3FN e defini chaves primárias, chaves estrangeiras, `UNIQUE` e `CHECK`, usando exclusão lógica (`ativo`) em vez de `DELETE` físico nos registros com histórico fiscal.
* **Dicionário de Dados:** Estruturei a documentação de cada atributo com tipo, constraints, privacidade (`DP` e `DPS`), linhagem e RBAC, e conferi o conteúdo com a seção 6 do documento de requisitos.
* **Página Interativa:** Criei uma página com busca por tabela ou coluna, tema claro e escuro, navegação lateral entre as entidades e visualizador do DER com zoom.
* **Publicação:** Pratiquei o fluxo de versionar com Git, enviar ao GitHub e ativar o GitHub Pages, além de tratar o cache do navegador para exibir a versão atualizada.

## 🧠 Declaração de Uso Ético da IA
Este projeto utilizou inteligência artificial como ferramenta de suporte tecnológico nas seguintes etapas:

* **Gemini:** refinamento do documento de requisitos para a versão 2.0, criação do código Mermaid usado para gerar o DER e criação do script DDL.
* **Claude:** criação do dicionário de dados e da página web que o apresenta.

Todo o conteúdo gerado foi revisado, testado e compreendido por mim, garantindo a minha responsabilidade integral sobre a autoria final, integridade e funcionamento da aplicação.

## 💻 Deploy do projeto
[Clique para acessar](https://guilherme-leme-machado.github.io/dicionario-dados-projeto-mercado)

---
[Voltar ao início](https://github.com/Guilherme-Leme-Machado/portfolio-guilherme-leme-machado)
