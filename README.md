# DESAFIO-QA-BEEDOO-2026
# Desafio QA – Beedoo

Este repositório contém a análise, cenários de teste, bugs encontrados e evidências de execução referentes ao desafio técnico de QA para o módulo de **cadastro e listagem de cursos**.

---

# 1. Objetivo da aplicação

A aplicação tem como objetivo permitir o **cadastro e a visualização de cursos**, possibilitando que usuários registrem informações como:

- Nome do curso
- Descrição
- Instrutor
- URL de imagem
- Datas de início e fim
- Número de vagas
- Tipo de curso (online ou presencial)
- Informações complementares como link de inscrição ou endereço.

---

# 2. Fluxos principais identificados

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

1. Cadastro de curso
2. Listagem de cursos
3. Exibição dos dados cadastrados
4. Exibição de campos condicionais conforme o tipo de curso
   - Link de inscrição (curso online)
   - Endereço (curso presencial)

Esses fluxos foram considerados os mais críticos para validação da funcionalidade.

---

# 3. Estratégia de testes

A estratégia utilizada foi baseada em **testes exploratórios e análise de risco**, priorizando:

- Fluxos principais da funcionalidade
- Validação de campos
- Cenários negativos
- Testes com entradas inesperadas
- Comportamento da interface com dados extremos
- Verificação de erros no console do navegador

Os testes também consideraram aspectos de:

- Usabilidade
- Validação de dados
- Segurança básica
- Comportamento visual da interface.

---

# 4. Pontos críticos identificados para teste

Os principais pontos considerados críticos foram:

- Cadastro correto de cursos
- Persistência dos dados cadastrados
- Exibição correta na listagem
- Validação de campos obrigatórios
- Comportamento com entradas inválidas
- Limites de caracteres
- Integridade da interface ao exibir dados extensos
- Tratamento de URLs e dados inseridos pelo usuário

---

# 5. Ferramentas utilizadas

Durante os testes foram utilizadas as seguintes ferramentas:

- Navegador Google Chrome
- Console do navegador (DevTools)
- Testes exploratórios manuais
- Captura de evidências por prints
- Documentação de cenários em planilha

---

# 6. Cenários e casos de teste

Os cenários e casos de teste executados estão documentados na planilha:

📄 **Casos de Teste**  
(casos_de_teste_beedoo.xlsx)
([[Google Sheets](https://docs.google.com/spreadsheets/d/1xmRfmdpIRIoArKnq_LH5gK7ohLFMOwJY_XxUQOFLZBE/edit?usp=sharing)])

A planilha contém:

- Cenários positivos
- Cenários negativos
- Testes de validação
- Testes exploratórios

---

# 7. Bugs encontrados

Durante os testes foram identificados diversos problemas relacionados a:

- Validação de dados
- Navegação da aplicação
- Layout da interface
- Tratamento de URLs

📄 **Relatório de bugs:**  
(relatorio_bugs_beedoo.docx)
[[Arquivo bugs](https://1drv.ms/w/c/981934816ed2ea07/IQCgod_E_yqASLGO3B4XWEwFAflBdTEJPjhwD8WnUceIkk0?e=I7xC71)]

---

# 8. Evidências dos testes

As evidências dos testes executados estão disponíveis no docmento (relatorio_bugs_beedoo.docx) ou entrando diretamente no link:
[[Arquivo bugs](https://1drv.ms/w/c/981934816ed2ea07/IQCgod_E_yqASLGO3B4XWEwFAflBdTEJPjhwD8WnUceIkk0?e=I7xC71)]

📂 **evidencias**

Incluindo:

- prints dos bugs
- prints do console
- evidências da quebra de layout
- erros de requisição

---

# 9. Considerações finais

O desafio permitiu avaliar diferentes aspectos da qualidade da aplicação, incluindo:

- comportamento funcional
- validação de dados
- tratamento de entradas inesperadas
- experiência do usuário
- investigação de defeitos

Durante a análise foram identificadas falhas relevantes que podem impactar diretamente a experiência do usuário e a confiabilidade da aplicação, especialmente relacionadas à validação de dados e organização da interface.
