# Hay Beaumont

Arquiteto de Software e Engenheiro. Projeto e desenvolvo produtos baseados em inteligência artificial de ponta a ponta, da arquitetura e implementação full-stack à infraestrutura, sistemas de pagamento e decisões operacionais que determinam se uma solução realmente funciona no mundo real.

**[English](README.md)**

---

A maior parte dos produtos que desenvolvo e coloco em produção é privada. O que compartilho aqui é a engenharia por trás deles: como os sistemas são arquitetados, quais decisões técnicas foram determinantes, os trade-offs envolvidos e os desafios encontrados ao transformar ideias em produtos reais.

Os repositórios abaixo apresentam estudos de caso de projetos efetivamente desenvolvidos, com uma abordagem técnica voltada a engenheiros e profissionais de tecnologia, não a apresentações comerciais. Não são projetos open source e não disponibilizam código-fonte proprietário nem dados de clientes.

## Trabalhos selecionados

| Projeto | O que é | Construído com |
|---|---|---|
| **[zoka](https://github.com/yahbeaumont/zoka-case-study)** | Uma plataforma de estudos com IA para estudantes brasileiros: comunidades, tutor conversacional e planos pagos, em produção | Next.js, Firebase, Stripe, Cloud Run |
| **[vai-de-qual](https://github.com/yahbeaumont/vai-de-qual-case-study)** | Rede social para apaixonados por futebol, com uma evolução arquitetural que transformou uma estrutura baseada em arquivos HTML independentes por funcionalidade em uma API modular, acompanhada de um ledger financeiro de partidas dobradas. | NestJS, PostgreSQL, Redis, Stripe, Pix |
| **[orbital](https://github.com/yahbeaumont/orbital-case-study)** | Experiência digital bilíngue para um ecossistema de hardware de IA local, desenvolvida por meio de um pipeline de geração próprio em Python, priorizando controle arquitetural, desempenho e independência de frameworks.| Python, HTML, CSS e JavaScript |
| **[orbital-os](https://github.com/yahbeaumont/orbital-os-case-study)** | Plataforma de IA local, desenvolvida integralmente do zero e projetada para ser agnóstica de hardware. Reúne arquitetura própria, pesquisa técnica, registros de decisões arquiteturais (ADRs), diagramas e documentação de engenharia que fundamentam a concepção e a implementação do sistema. | Arquitetura de Software | Engenharia de Sistemas | ADRs | Pesquisa Técnica e Documentação de Engenharia |
| **[jer-crm](https://github.com/yahbeaumont/jer-crm-case-study)** | CRM de prospecção desenvolvido integralmente do zero, que transforma listas segmentadas de empresas em filas diárias de trabalho comercial. Possui controle de acesso aplicado diretamente na camada de banco de dados, garantindo isolamento de dados e aplicação consistente das permissões. | Next.js | PostgreSQL | Row-Level Security (RLS) | Arquitetura de Software e Engenharia de Dados |

## Como eu trabalho

Começo pelas restrições, não pelo framework. Requisitos regulatórios, tamanho da equipe, prioridades do negócio e prazos de entrega influenciam muito mais a arquitetura de um sistema do que preferências pessoais por uma biblioteca ou tecnologia específica.

Estabeleço fronteiras claras para dinheiro e identidade. O navegador nunca deve ser considerado confiável para autorizar operações financeiras, acessar dados de outros usuários ou modificar permissões. Sempre que uma regra puder ser imposta diretamente pelo banco de dados, ela deve ser.

Documento as decisões e suas razões. Registrar por que um sistema foi concebido de determinada maneira custa muito menos do que reconstruir esse raciocínio no futuro — especialmente quando quem precisa fazer isso sou eu, dois anos depois.

Prefiro infraestrutura previsível e ciclos curtos de feedback. Menos componentes desnecessários, estado observável, processos claros e mecanismos de rollback que realmente funcionam. Confiabilidade é resultado de decisões de engenharia deliberadas, não de complexidade desnecessária.

## Stack

**Linguagens e Runtime:** TypeScript, Python, Node.js.  
**Frameworks:** NestJS, Next.js, React.  
**Banco de Dados e Infraestrutura:** PostgreSQL, Redis, Firebase, Google Cloud Run, Firebase Hosting.  
**Pagamentos e Integrações:** Stripe, Pix e integração com serviços de terceiros.  
**Inteligência Artificial:** Integração de LLMs, modelos de pesos abertos (*open-weight models*) e inferência local em hardware real, com testes práticos de desempenho, capacidade e comportamento dos modelos.

---

Os estudos de caso estão disponíveis em **inglês** e **português brasileiro**. Cada repositório especifica seu escopo, seus limites e quais informações e materiais foram intencionalmente excluídos da publicação.
