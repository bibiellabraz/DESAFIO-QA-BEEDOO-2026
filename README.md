# DESAFIO-QA-BEEDOO-2026

README.md
1. Sobre o desafio

Este repositório contém a análise, os cenários de teste, os bugs encontrados e as evidências de execução referentes ao desafio técnico de QA para o módulo de cadastro e listagem de cursos.

2. Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e a listagem de cursos, possibilitando ao usuário informar dados como nome do curso, descrição, instrutor, datas, tipo do curso, número de vagas e informações complementares conforme o tipo selecionado.

3. Principais fluxos disponíveis

Os principais fluxos identificados na aplicação foram:
Cadastro de curso
Listagem de cursos
Exibição dos dados cadastrados
Variação de campos conforme o tipo de curso (online ou presencial)

4. Pontos mais críticos para teste

Os pontos que considerei mais críticos foram:
Cadastro principal de curso
Validação dos campos do formulário
Persistência e exibição dos dados na listagem
Comportamento da aplicação com entradas inválidas
Tratamento de textos longos, caracteres especiais e URLs
Comportamento visual da listagem e organização dos cards

5. Análise inicial da aplicação

Durante a exploração inicial, observei que a aplicação possui uma interface simples, com foco no cadastro e listagem de cursos. A partir dessa análise, priorizei testes voltados ao fluxo principal, validações de formulário, cenários negativos e comportamentos inesperados.

Também foram observados indícios de ausência de validação em diversos campos, erros 404 após determinadas ações e problemas de layout na listagem dos cursos.

6. Decisões tomadas para criação dos testes

A estratégia de testes foi baseada em risco e cobertura funcional. Por isso, priorizei:
Fluxo feliz de cadastro
Exibição correta na listagem
Validação de campos obrigatórios
Testes com dados inválidos
Testes com textos longos e caracteres especiais
Verificação de comportamento visual após cadastro
Essas decisões foram tomadas porque o cadastro e a listagem são o núcleo da funcionalidade, e qualquer falha nesses pontos impacta diretamente a experiência do usuário.

7. Raciocínio utilizado durante a análise

Meu raciocínio foi dividido em três frentes:
Funcional: validar se o fluxo principal realmente funciona
Validação: verificar se os campos aceitam apenas dados esperados
Exploratória: testar comportamentos inesperados, como entradas fora do padrão, textos extensos e efeitos na navegação e no layout

A investigação dos defeitos também incluiu uso do console do navegador para observar erros de rota e comportamento da aplicação após as ações executadas.

8. Cenários e casos de teste

Planilha com os cenários e casos de teste:
[[inserir link do Google Sheets aqui](https://docs.google.com/spreadsheets/d/1xmRfmdpIRIoArKnq_LH5gK7ohLFMOwJY_XxUQOFLZBE/edit?usp=sharing)]

9. Relatório de bugs

Relatório com bugs encontrados:
[inserir link do arquivo ou referência da pasta bugs]

10. Evidências de execução

Evidências dos testes executados:
[inserir link do Google Drive ou pasta compartilhada aqui]

11. Considerações finais

O desafio permitiu explorar tanto o comportamento funcional quanto aspectos de validação, investigação de defeitos e experiência do usuário. Foram encontrados problemas relevantes relacionados à validação de entrada, tratamento de rotas e organização visual da listagem.
