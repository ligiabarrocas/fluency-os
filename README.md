# FluencyOS — Inglês para PM em Tecnologia

Versão: v0  
Status: protótipo funcional em HTML/CSS/JavaScript para uso pessoal e validação.

## Objetivo

O FluencyOS é uma plataforma de estudo de inglês prático para uma pessoa PM em tecnologia.

O foco principal é ajudar no desenvolvimento de:

- fala;
- escuta;
- pronúncia;
- leitura;
- escrita;
- vocabulário profissional;
- estrutura de frases;
- confiança para reuniões reais.

A proposta não é ser um curso genérico de inglês, mas sim um ambiente de treino aplicado ao dia a dia de trabalho em tecnologia, com exemplos de reuniões, status report, planejamento, refinamento, riscos, bloqueios, conversas individuais e comunicação com times técnicos.

## Para quem é

Esta versão foi pensada principalmente para uma pessoa que atua como PM, gerente de projetos, delivery lead, project lead ou papel semelhante em times de tecnologia.

Também pode ajudar pessoas que trabalham com Produto, QA, Desenvolvimento, Dados, Arquitetura, Governança, Operações e Liderança técnica.

## Estrutura da plataforma

A plataforma é composta por páginas HTML estáticas. Cada página tem um objetivo específico.

### Início

Apresenta o objetivo da plataforma e direciona para os principais caminhos de estudo.

### Dashboard

Mostra o progresso salvo localmente no navegador e a última frase praticada.

### Plano 120 dias

Plano principal de estudo.

A estrutura segue um ciclo de 4 dias por semana:

1. Base: frases, verbos e palavras.
2. Gramática: regra aplicada e exemplos.
3. Diálogo: prática de conversa e escrita.
4. Revisão: exercícios, escuta, escrita e simulação oral.

O objetivo é evoluir de inglês básico/aplicável até comunicação mais confiante e influente em contexto profissional.

### Rituais PM

Área com situações reais de trabalho, como Daily, Planning, Refinamento, Status Report, Retrospectiva, Review/Demo, One-on-one, Kickoff, Ways of Working, Technical Sync e Riscos/Bloqueios.

Cada ritual traz frases, diálogo, tradução, pronúncia aproximada e áudio.

### Casos reais

Página com situações comuns do dia a dia de projetos em tecnologia, como proposta com risco, escopo não viável, ambiente bloqueado, acesso pendente, pressão de prazo, governança, documentação, observabilidade, dependências técnicas e próximos passos.

### Frases úteis

Biblioteca de frases para reuniões, status, pedidos de ajuda, follow-up, alinhamento, feedback e comunicação profissional.

### Datas e horários

Treino de dias da semana, meses, números, horários e frases para marcar, remarcar ou confirmar reuniões.

### Dicionário 2000+

Área de consulta com palavras, verbos, substantivos, adjetivos, preposições, advérbios e chunks.

Cada item pode conter palavra em inglês, tradução, categoria, pronúncia aproximada, exemplo e áudio.

### Montar frases

Guia de regras para construir frases em inglês.

O foco é entender diferenças entre português e inglês, como ordem das palavras, posição dos adjetivos, uso de auxiliares, perguntas, negativas, preposições, modais, tempos verbais, conectores, condicionais e frases complexas.

### Verbos

Página para praticar verbos com exemplos no presente, passado, futuro e present perfect.

### Gramática

Gramática aplicada ao contexto profissional, com foco em uso prático e exemplos.

### Pronúncia

Guia de pronúncia para apoiar clareza, ritmo e confiança na fala.

A pronúncia aproximada é um apoio visual para brasileiros. O áudio do navegador deve ser usado como referência principal.

### Speaking

Frases por nível para treino de fala, repetição e confiança.

### Flashcards

Revisão rápida de palavras, expressões e frases.

### Text Lab

Área para colar textos, e-mails ou frases e usar como apoio para estudo, revisão e criação de prompts.

### Tech & Data

Vocabulário de tecnologia, dados, IA, governança, integração, observabilidade e temas técnicos.

### Exercícios do dia a dia

Página opcional com ideias para praticar inglês usando músicas, filmes, séries, podcasts, audiobooks, academia, deslocamento, cenas curtas e diário de palavras.

Esta área não é o foco principal da plataforma. Ela serve como complemento para manter contato com o inglês na rotina.

### Voz & áudio

Página para configurar a voz do navegador e testar áudio lento/normal.

### Ajuda

Guia para entender como estudar pela plataforma e como aproveitar melhor cada área.

## Como estudar

Sugestão de uso diário:

1. Abrir o Plano 120 dias.
2. Fazer a lição do dia.
3. Escutar cada frase no modo lento.
4. Escutar novamente no modo normal.
5. Repetir em voz alta.
6. Ler a tradução.
7. Observar a pronúncia aproximada.
8. Gravar a própria voz quando possível.
9. Fazer os exercícios.
10. Marcar o dia como concluído.

Em dias com menos tempo, priorize áudio, repetição, 3 a 5 frases úteis e uma pequena revisão.

Em dias com mais tempo, faça plano diário, ritual PM relacionado, dicionário, montar frases, speaking e revisão oral.

## Progresso

O progresso é salvo no navegador usando armazenamento local.

Isso significa que não há login, conta de usuário, banco de dados ou sincronização entre dispositivos. O progresso fica no dispositivo/navegador usado.

## Compartilhamento

A plataforma pode ser publicada no GitHub Pages.

O link pode ser compartilhado com outras pessoas para teste e feedback.

Como é um site estático, várias pessoas podem usar ao mesmo tempo sem conflito. Cada pessoa terá seu progresso salvo no próprio navegador.

## Como publicar no GitHub Pages

Suba todos os arquivos da plataforma para o repositório, incluindo todos os arquivos `.html`, a pasta `assets` e este `README.md`.

A pasta `assets` é obrigatória, pois contém os arquivos de estilo e funções:

```text
assets/css/app.css
assets/js/app.js
