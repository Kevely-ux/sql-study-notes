# 📚 SQL Study Notes

Guia de referência em SQL (MySQL) construído a partir das aulas e exercícios da disciplina **Banco de Dados e Aplicações** — comandos, padrões de uso e, principalmente, os **erros reais** encontrados durante a prática e como resolvê-los.

**🔗 [Ver o guia publicado](https://Kevely-ux.github.io/sql-study-notes/)**

---

## Sobre o projeto

A maioria dos materiais de estudo de SQL mostra só o comando "certo". Este guia é diferente: cada seção nasceu de uma dúvida ou de um erro real rodado no MySQL Workbench, documentado com o código de erro, a causa e a correção — não só a teoria.

Construído como uma única página estática (HTML/CSS puro, sem dependências de build), com suporte a tema claro/escuro automático e leitura confortável no celular.

## Conteúdo

Além do guia por tópico, a página [Guia por aula](https://Kevely-ux.github.io/sql-study-notes/aulas.html) organiza os slides de cada aula e traz, para cada exercício, um "Como resolver" com dicas (sem gabarito pronto).

| # | Tópico |
|---|---|
| 1 | Criar tabelas (`CREATE TABLE`, `PRIMARY KEY`, `FOREIGN KEY`) |
| 2 | Inserir dados (`INSERT`, tipos de coluna) |
| 3 | Consultar dados (`SELECT`, `AS`, `CASE WHEN` aninhado) |
| 4 | Combinar consultas (`UNION`, `INTERSECT`, `EXCEPT`) |
| 5 | Juntar tabelas (`JOIN`, `LEFT JOIN`, `NOT EXISTS`) |
| 6 | Agrupar e somar (`GROUP BY`, `HAVING`) |
| 7 | `WITH` (Common Table Expressions) |
| 8 | Subqueries (taxonomia completa: SELECT, INSERT, UPDATE, DELETE) |
| 9 | Atualizar dados (`UPDATE`, Safe Update Mode) |
| 10 | Índices (`CREATE INDEX`, `EXPLAIN ANALYZE`) |
| 11 | Views (`CREATE VIEW`, regras de atualização) |
| 12 | Trigger (`BEFORE`/`AFTER`, `NEW`/`OLD`, `SIGNAL`) |
| 13 | Function (`RETURNS`, `DETERMINISTIC`, chamada dentro do `SELECT`) |
| 14 | Stored Procedure (`IN`/`OUT`/`INOUT`, `WHILE`/`REPEAT`, `SIGNAL`) |
| 15 | Referência rápida de erros (códigos reais do MySQL) |

## Tecnologias

- HTML5 + CSS3 (sem frameworks)
- Tipografia: [Archivo](https://fonts.google.com/specimen/Archivo), [Source Serif 4](https://fonts.google.com/specimen/Source+Serif+4) e [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), via Google Fonts
- Publicado com [GitHub Pages](https://pages.github.com/)

## Rodando localmente

Não precisa de nenhuma instalação — é um arquivo HTML estático:

```bash
git clone https://github.com/Kevely-ux/sql-study-notes.git
cd sql-study-notes
# abra o index.html diretamente no navegador
```

## Licença

Distribuído sob a licença MIT — veja [LICENSE](LICENSE) para mais detalhes.

---

<sub>Feito durante a disciplina de Banco de Dados e Aplicações.</sub>
