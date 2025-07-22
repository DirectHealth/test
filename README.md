# 🚀 Desafio Full Stack DirectRad – Módulo de Laudos Médicos (RIS)

Olá! Obrigado pelo seu interesse em fazer parte do nosso time. Abaixo você encontrará todas as instruções para realizar seu desafio técnico.

---

## 📌 Avisos Importantes

- Leia este documento com atenção e siga as instruções;
- Crie um repositório **no seu GitHub**, **sem citar nada relacionado ao DirectRad**;
- Faça commits frequentes e significativos;
- Envie o link do repositório ao final;
- É permitido consultar Google, StackOverflow ou projetos próprios;
- Fique à vontade para tirar dúvidas;
- Respire, organize seu tempo e boa sorte! 💪

---

## 🧠 Contexto

O **RIS** (Radiology Information System) é um sistema de emissão de laudos médicos radiológicos. O objetivo deste desafio é avaliar sua capacidade de desenvolver uma aplicação **full stack** utilizando **PHP** (preferencialmente com CodeIgniter), integrando funcionalidades comuns nesse tipo de sistema.

---

## ✅ Requisitos Funcionais

Desenvolva um módulo simples para **criação, edição e gestão de laudos médicos**:

### 📝 Formulário de Laudo

- Editor de texto (ex: TinyMCE) com suporte a:
  - Modelos de frases e laudos reutilizáveis;
  - Inserção de imagens no corpo do laudo;
  - Reconhecimento de voz (transcrevendo áudio via microfone do navegador Chrome);
- Campos obrigatórios:
  - Nome do paciente
  - Data de nascimento
  - Nome do exame
  - Médico
  - Data e hora do laudo
- Botões:
  - **Salvar Rascunho**
  - **Visualizar Preview (PDF)**
  - **Liberar Laudo (PDF)**

### 📄 Liberação do Laudo em PDF

- Após a liberação, o laudo não poderá mais ser editado;
- O cabeçalho deve conter as informações do paciente, do exame e da data. O rodapé deve conter as informações do médico e a assinatura;
- Exibir o PDF na tela com opção de download.

### 📋 Tela de Listagem/Gestão de Laudos

- Listar todos os laudos com filtros;
- Ações de CRUD;
- Status dos laudos;

---

## 🛠️ Requisitos Técnicos

- **Backend:** PHP (preferencialmente CodeIgniter)
- **Frontend:** HTML, CSS (Bootstrap), JavaScript (Ajax), Editor WYSIWYG (ex: TinyMCE) e outros
- **Banco de Dados:** MySQL
- **Ambiente:** Docker com `docker-compose.yml` (PHP + Nginx/Apache + MySQL)
- **Versionamento:** Git + GitHub (repositório público ou privado)

---

## ⚠️ Diferenciais
- Usar alguma integração com IA
- Uso assíncrono das funcionalidades
- Uso de Docker
- Testes
- Uso de Design Patterns
- Documentação
- Proposta de melhoria na arquitetura
- Ser consistente e saber argumentar suas escolhas
- Apresentar soluções que domina
- Modelagem de Dados
- Manutenibilidade do Código
- Tratamento de erros
- Cuidado com itens de segurança
- Arquitetura (estruturar o pensamento antes de escrever)
- Carinho em desacoplar componentes (outras camadas, service, repository)
- PSRs
- Aplicação e conhecimentos de SOLID
- Apresentação de código limpo e organizado

---

Boa sorte e bons commits! 🚀
