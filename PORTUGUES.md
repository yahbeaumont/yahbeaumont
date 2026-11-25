<img src="assets/hero.pt.svg" alt="Hay Beaumont, Arquiteto de Software e Engenheiro" width="100%">

**[English](README.md)**

A maior parte dos produtos que desenvolvo e coloco em produção é privada. O que compartilho aqui é a engenharia por trás deles: como os sistemas são arquitetados, quais decisões técnicas foram determinantes, os trade-offs envolvidos e os desafios encontrados ao transformar ideias em produtos reais.

Os repositórios abaixo apresentam estudos de caso de projetos efetivamente desenvolvidos, com uma abordagem técnica voltada a engenheiros e profissionais de tecnologia, não a apresentações comerciais. A maioria não é open source e nenhum deles expõe código proprietário ou dados de clientes; os que são abertos estão identificados como tal.

<img src="assets/sec-01.pt.svg" alt="Trabalhos selecionados" width="100%">

<a href="https://github.com/yahbeaumont/pix-on-ai"><img src="assets/pix-on-ai.pt.svg" alt="pix-on-ai, motor de crédito em código aberto sobre o fluxo Pix: 28 features de fluxo, PD calibrada com LightGBM, política de crédito versionada e reason codes por decisão. Python, FastAPI, PostgreSQL." width="100%"></a>
<a href="https://github.com/yahbeaumont/zoka-platform"><img src="assets/zoka-platform.pt.svg" alt="zoka-platform, plataforma de estudos com IA para estudantes brasileiros: comunidades, tutor e planos pagos, em produção. Next.js, Firebase, Stripe, Cloud Run." width="100%"></a>

<a href="https://github.com/yahbeaumont/vai-de-qual"><img src="assets/vai-de-qual.pt.svg" alt="vai-de-qual, rede social de futebol: grafo social, planos pagos, créditos e repasse a criadores. NestJS, PostgreSQL, Redis, Stripe." width="100%"></a>

<a href="https://github.com/yahbeaumont/orbital-website"><img src="assets/orbital-website.pt.svg" alt="orbital-website, site bilíngue para um ecossistema de hardware de IA local, gerado por pipeline em Python. Python, HTML, CSS, JavaScript." width="100%"></a>

<a href="https://github.com/yahbeaumont/orbital-os-platform"><img src="assets/orbital-os-platform.pt.svg" alt="orbital-os-platform, plataforma de IA local independente de hardware: arquitetura, orquestração de modelos e inferência local. Arquitetura, ADRs, pesquisa." width="100%"></a>

<a href="https://github.com/yahbeaumont/jer-crm"><img src="assets/jer-crm.pt.svg" alt="jer-crm, CRM de prospecção com controle de acesso imposto por row-level security no PostgreSQL. Next.js, PostgreSQL, row-level security." width="100%"></a>

<a href="https://github.com/yahbeaumont/pulso-plus"><img src="assets/pulso-plus.pt.svg" alt="pulso-plus, apoio à decisão clínica em hipertensão em código aberto: agente com LLM sobre ferramentas determinísticas, portão de sinais de alarme e revisão humana. Python, Streamlit, Pydantic." width="100%"></a>

<a href="https://github.com/yahbeaumont/rewind"><img src="assets/rewind.pt.svg" alt="rewind, ferramenta de código aberto para gravação e replay determinístico de execuções de agentes autônomos, com fitas encadeadas por SHA-256. TypeScript, Node." width="100%"></a>

<a href="https://github.com/yahbeaumont/nanorouter"><img src="assets/nanorouter.pt.svg" alt="nanorouter, harness de código aberto para fine-tuning de um SLM de 0,5B que roteia intenções e emite JSON válido contra schema. Medido: 0,81 de validade contra 0,69 de um 7B. Python, LoRA, Qwen." width="100%"></a>

<a href="https://github.com/yahbeaumont/docsage"><img src="assets/docsage.pt.svg" alt="docsage, RAG de código aberto sobre a documentação do FastAPI com suíte de avaliação de 60 perguntas, abstenção calibrada e A/B pareado com bootstrap. Medido: o A/B pareado não encontra ganho de recuperação (delta de nDCG -3,6%, inconclusivo), abstenção 0,30 contra 0,00, custo por consulta 40% menor e p95 de 63 s porque o cross-encoder é serializado em CPU. Python, Qdrant, BM25, rerank." width="100%"></a>

<a href="https://github.com/yahbeaumont/argus"><img src="assets/argus.pt.svg" alt="argus, agente de pesquisa de código aberto sobre MCP com orçamento por tarefa, detecção de loop, circuit breaker e verificação de citações. Medido em 40 tarefas: 75,0% de sucesso contra 62,5% sem guardas, 24% mais barato por tarefa e p95 de 194 s para 66 s, sem significância a 5% (McNemar p=0,125). Python, MCP." width="100%"></a>

<img src="assets/sec-02.pt.svg" alt="Como eu trabalho" width="100%">

Começo pelas restrições, não pelo framework. Requisitos regulatórios, tamanho da equipe, prioridades do negócio e prazos de entrega influenciam muito mais a arquitetura de um sistema do que preferências pessoais por uma biblioteca ou tecnologia específica.

Estabeleço fronteiras claras para dinheiro e identidade. O navegador nunca deve ser considerado confiável para autorizar operações financeiras, acessar dados de outros usuários ou modificar permissões. Sempre que uma regra puder ser imposta diretamente pelo banco de dados, ela deve ser.

Documento as decisões e suas razões. Registrar por que um sistema foi concebido de determinada maneira custa muito menos do que reconstruir esse raciocínio no futuro, especialmente quando quem precisa fazer isso sou eu, dois anos depois.

Prefiro infraestrutura previsível e ciclos curtos de feedback. Menos componentes desnecessários, estado observável, processos claros e mecanismos de rollback que realmente funcionam. Confiabilidade é resultado de decisões de engenharia deliberadas, não de complexidade desnecessária.

<img src="assets/sec-03.pt.svg" alt="Stack de tecnologia" width="100%">

```text
linguagens   typescript · python · node.js
frameworks   nestjs · next.js · react
dados        postgresql · redis · firebase · cloud run
pagamentos   stripe · pix
ia           integração de llm · modelos de peso aberto
             inferência local em hardware real
```

<img src="assets/sec-04.pt.svg" alt="Notas" width="100%">

Os estudos de caso estão disponíveis em **inglês** e **português brasileiro**. Cada repositório especifica seu escopo, seus limites e quais informações e materiais foram intencionalmente excluídos da publicação. Os repositórios pix-on-ai, rewind, nanorouter, docsage e argus são a exceção: os cinco são código aberto, sob licença MIT, e trazem o código em vez de um estudo de caso.
