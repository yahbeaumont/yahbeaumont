# Hay Beaumont

Arquiteto de software e engenheiro. Construo produtos de IA de ponta a ponta: arquitetura, implementação full-stack, billing, infraestrutura e os detalhes operacionais que decidem se um produto sobrevive ao contato com os usuários.

**[English](README.md)**

---

A maior parte do que eu coloco em produção é privada. O que posso mostrar é a engenharia: como um sistema é montado, quais decisões pesaram e onde estão os limites. Os repositórios abaixo são estudos de caso de produtos reais, escritos para engenheiros, não para páginas de vendas. Não são open source e não contêm código de produto nem dados de clientes.

## Trabalhos selecionados

| Projeto | O que é | Construído com |
|---|---|---|
| **[zoka](https://github.com/yahbeaumont/zoka-case-study)** | Uma plataforma de estudos com IA para estudantes brasileiros: comunidades, tutor conversacional e planos pagos, em produção | Next.js, Firebase, Stripe, Cloud Run |
| **[vai-de-qual](https://github.com/yahbeaumont/vai-de-qual-case-study)** | Uma plataforma de apostas regulamentada e a transição que a produziu: de um arquivo HTML por superfície para uma API modular e um ledger de partidas dobradas | NestJS, PostgreSQL, Redis, Stripe, Pix |
| **[orbital](https://github.com/yahbeaumont/orbital-case-study)** | Um site bilíngue de marketing e produto para hardware de IA local, gerado por um pipeline em Python em vez de um framework | Python, HTML, CSS e JavaScript escritos à mão |
| **[orbital-os](https://github.com/yahbeaumont/orbital-os-case-study)** | A arquitetura de uma plataforma de IA local e agnóstica de hardware: pesquisa, registros de decisão e diagramas da fase anterior ao código | Arquitetura, ADRs, escrita técnica |
| **[jer-crm](https://github.com/yahbeaumont/jer-crm-case-study)** | Um CRM de prospecção que transforma listas filtradas de empresas em uma fila de trabalho diária, com regras de acesso impostas pelo banco | Next.js, PostgreSQL, row-level security |

## Como eu trabalho

Parto da restrição, não do framework. Um produto regulado, um time pequeno e um prazo dizem mais sobre um sistema do que qualquer preferência por biblioteca.

Dinheiro e identidade ganham fronteira. O browser nunca recebe confiança para decidir algo que custa dinheiro, expõe dados de outro usuário ou altera um direito de acesso. Onde o banco pode impor uma regra, ele impõe.

Eu escrevo a decisão. Um registro de por que um sistema é como é custa menos do que reconstruí-lo depois, principalmente quando quem reconstrói sou eu, dois anos adiante.

Prefiro infraestrutura sem surpresas e ciclos curtos de feedback. Menos peças móveis, estado visível e um rollback que funciona.

## Stack

TypeScript, Python, Node.js, NestJS, Next.js, React. PostgreSQL, Redis, Firebase, Cloud Run, Firebase Hosting. Stripe, Pix. Inferência local com modelos de pesos abertos, em hardware que eu consigo testar de verdade.

---

Os estudos de caso são publicados em **inglês** e **português brasileiro**. Cada repositório declara o que não contém.
