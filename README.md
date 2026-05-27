## Nícolas Galdino

**Engenheiro de Dados Sênior | IA & Search** — Ministério Público do Estado do Rio de Janeiro (MPRJ)

Atuo no Núcleo de Inteligência Artificial (NIA) do MPRJ, sendo responsável pela arquitetura de dados, pipelines de indexação e infraestrutura de busca que sustentam as soluções de IA do órgão. O acervo indexado sob minha responsabilidade ultrapassa 90 milhões de documentos judiciais de múltiplas fontes, com pipelines de carga incremental e completa rodando diariamente.

---

### O que eu faço hoje

- **Indexação em larga escala** — projetei o pipeline que processa ~120M de páginas via OCR (Azure IntelliDoc), gera embeddings (Azure OpenAI) e indexa no Elasticsearch com busca híbrida BM25 + semântica (Reciprocal Rank Fusion)
- **Agentes e chatbots** — construí o NIA Chat Visão MPRJ com LangGraph: classificação de intenção, expansão de siglas, geração de queries DSL via LLM, busca híbrida e geração de respostas — reduzindo latência de 54s para ~5s e consumo de tokens em 93%
- **Governança de dados** — responsável pelo Elasticsearch, PostgreSQL e Oracle da equipe: modelagem de índices, API keys, políticas de acesso e pipelines de alimentação
- **Orquestração** — diversas DAGs no Apache Airflow/Kubernetes com escalonamento coordenado entre fontes, paralelismo de tasks, controle de ociosidade e monitoramento proativo
- **Infraestrutura** — CI/CD com GitLab, deploy em OpenShift, consolidação de secrets, versionamento automático com bump2version, resiliência de pool PostgreSQL com TCP keepalives
- **Bibliotecas internas** — mantenho o nia-etl-utils (PyPI), pacote compartilhado entre todos os ETLs do time, com módulos de OCR, embedding, conexão Elasticsearch, configuração de ambiente e tratamento de exceções

---

### Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,elasticsearch,kubernetes,docker,postgres,linux,git,azure" />
  </a>
</p>

`Airflow` · `LangGraph` · `RabbitMQ` · `OpenShift` · `Oracle` · `GitLab CI/CD` · `Azure OpenAI` · `Azure OCR` · `FastAPI` · `PGVector` · `Docker`

---

### Experiência

**Engenheiro de Dados Sênior | IA & Search** · MPRJ/NIA · mar 2025 – presente
Arquitetura de pipelines ETL para ML e agentes LLM. Pipeline de indexação de 90M+ documentos judiciais com OCR e embeddings. Chatbot com busca híbrida e agentes LangGraph. Orquestração com Airflow, deploy em OpenShift.

**Engenheiro de Dados & Desenvolvedor Backend** · MPRJ/DTI · jan 2023 – mar 2025
Migração de ETL do Pentaho para Airflow. Manutenção de dados legados em Oracle. Backend em Django (Parquet Digital, ROPC). Testes automatizados, documentação com Swagger/MkDocs. Colaboração com equipe multidisciplinar de 40+ profissionais.

**Desenvolvedor Frontend** · MPRJ/DTI · abr 2022 – dez 2022
Interfaces em React para o Parquet Digital. Deploy em OpenShift. Primeiros passos com Scrum e entrega iterativa.

---

### Contato

<p align="left">
  <a href="https://www.linkedin.com/in/nicolas-galdino-esmael/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=flat" height="28" alt="linkedin" />
  </a>
  &nbsp;
  <a href="mailto:nicolasesmael1998@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=flat" height="28" alt="gmail" />
  </a>
</p>
