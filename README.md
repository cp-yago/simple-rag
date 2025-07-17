# Simple RAG - Estudo e Portfólio

Um RAG (Retrieval-Augmented Generation) simples desenvolvido para fins de estudo e portfólio, com foco em busca semântica em diferentes tipos de mídia.

## 📋 Sobre o Projeto

Este projeto implementa um sistema de RAG que permite:

- **Upload de arquivos** em diferentes formatos (PDF, imagem e vídeo)
- **Busca semântica** inteligente nos arquivos carregados

### Casos de Uso

- 🔍 **Contratos**: "Qual é a multa de rescisão do contrato do colaborador José da Silva?" → Busca no PDF do contrato específico
- 🍚 **Receitas em Vídeo**: "Quanto tempo o arroz de forno deve ficar no forno e a qual temperatura?" → Analisa o vídeo "Como fazer arroz de forno"
- 💬 **Depoimentos em Imagens**: "Traga uma lista de depoimentos positivos sobre o meu produto" → Busca em screenshots de depoimentos

## 🎯 Objetivos de Aprendizado

- **RAG**: Compreender e aplicar conceitos de Retrieval-Augmented Generation na prática
- **Infraestrutura como Código**: Implementar IaC usando Terraform e AWS
- **CI/CD**: Configurar pipelines de integração e deploy contínuo

## 🛠️ Decisões Técnicas

### Frontend

- **React v19** com **Vite v7** para desenvolvimento rápido e HMR otimizado
- **Tailwind CSS v4** para estilização utility-first com nova sintaxe CSS

### Backend

- **Node.js** com **Fastify** para alta performance e TypeScript nativo
- **APIs RESTful** com validação de esquemas e documentação automática

### Infraestrutura

- **Terraform** para Infrastructure as Code
- **AWS** como cloud provider principal

### Organização

- **Monorepo** com **Turbo Repo** para gerenciamento eficiente de builds e cache

## 📁 Estrutura do Projeto

```
simple-rag/
├── apps/
│   ├── api/          # Backend (Node.js + Fastify)
│   └── web/          # Frontend (React + Vite + Tailwind)
├── docs/             # Documentação do projeto
├── infra/            # Infraestrutura (Terraform)
└── README.md         # Este arquivo
```

## 🚀 Metodologia de Desenvolvimento

O projeto será desenvolvido de forma **incremental**, partindo das features mais simples para as mais complexas, sempre priorizando:

1. **Documentação** de decisões técnicas
2. **Implementação** gradual das funcionalidades
3. **Versionamento** e deploy estruturado

## 📚 Próximos Passos

1. Documentar decisões técnicas detalhadas
2. Configurar ambiente de desenvolvimento
3. Implementar funcionalidades básicas
4. Configurar infraestrutura
5. Implementar CI/CD

## 🔧 Tecnologias - Versões e Referências

### Frontend Stack

| Tecnologia       | Versão Atual | Documentação                             | Notas                                                 |
| ---------------- | ------------ | ---------------------------------------- | ----------------------------------------------------- |
| **React**        | v19.1        | [React Docs](https://react.dev)          | Nova API createRoot, Compiler RC disponível           |
| **Vite**         | v7.0.0       | [Vite Guide](https://vitejs.dev)         | Requer Node.js 20.19+, suporte aprimorado ao Rolldown |
| **Tailwind CSS** | v4.x         | [Tailwind Docs](https://tailwindcss.com) | Nova sintaxe CSS-first, `@tailwindcss/vite` plugin    |

### Backend Stack

| Tecnologia  | Versão Atual | Documentação                            | Notas                                    |
| ----------- | ------------ | --------------------------------------- | ---------------------------------------- |
| **Node.js** | 20.19+ LTS   | [Node.js Docs](https://nodejs.org/docs) | Versão mínima para Vite v7               |
| **Fastify** | Latest       | [Fastify Docs](https://fastify.dev)     | TypeScript nativo, performance otimizada |

### DevOps e Tooling

| Tecnologia    | Versão Atual | Documentação                           | Notas                                 |
| ------------- | ------------ | -------------------------------------- | ------------------------------------- |
| **Turborepo** | Latest       | [Turbo Docs](https://turbo.build)      | Cache remoto, suporte multi-framework |
| **Terraform** | Latest       | [Terraform Docs](https://terraform.io) | IaC para AWS                          |

---

> **Nota**: Este é um projeto de estudo focado em aprendizado prático de tecnologias modernas para desenvolvimento de aplicações com IA.
