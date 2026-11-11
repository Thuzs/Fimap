# FIMAP

### Plataforma de gestão financeira pessoal que usa Open Finance e Inteligência Artificial para transformar dados em ações reais.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/vers%C3%A3o-1.0.0-blue)

> ℹ️ **Aviso:** FIMAP é um projeto de Trabalho de Conclusão de Curso (TCC) desenvolvido no SENAI Jandira.

**FIMAP** é uma plataforma de gestão financeira pessoal que usa a tecnologia de Open Finance aliada à IA para monitorar continuamente a vida financeira do usuário, identificar problemas, simular cenários de investimento e transformar essas descobertas em ações reais para melhorar a situação financeira do cliente.

| Problema | Solução | Resultado esperado | 
| ----- | ----- | ----- | 
| Controle financeiro ineficiente (apenas anotar os gastos não faz sobrar dinheiro). | Detector automático de oportunidades via Inteligência Artificial. | O usuário recebe alternativas reais de economia (ex: planos mais baratos) de forma proativa. | 

## O Problema

* **Estresse financeiro:** Segundo pesquisa da Onze/Icatu, o dinheiro é a maior fonte de preocupação para 49% dos brasileiros (acima de saúde e violência).

* **Controle passivo não funciona:** 91% das pessoas fazem algum controle financeiro, mas a grande maioria ainda não consegue arcar com os custos mensais. Apenas registrar dados não gera eficiência.

* **Falta de direcionamento prático:** Plataformas comuns apenas mostram onde o usuário gastou, mas não ajudam a pesquisar ativamente no mercado opções mais baratas para reduzir as contas fixas.

## A Solução

| Antes | Depois com FIMAP | 
| ----- | ----- | 
| Informações espalhadas em vários bancos e aplicativos. | Centralização automática e segura de cartões, contas e empréstimos via Open Finance. | 
| O usuário descobre que gastou R\$149 de internet e se frustra. | A IA alerta: "Encontramos um provedor na sua região por R\$100" e sugere a troca. | 
| Tentar guardar dinheiro para um carro às cegas. | A IA calcula quanto falta e encontra os R\$420/mês necessários "cortando" gastos específicos. | 

## Funcionalidades

* **Centralização Financeira:** Dashboard intuitivo e personalizável (por tipo de transação, data, etc.) que conecta todos os bancos de forma segura usando provedor Open Finance.

* **Assistente Financeiro de IA:** Um chatbot com quem o usuário pode conversar para fazer perguntas específicas, como *"Quanto eu gastei com restaurantes mês passado?"*.

* **Detector Automático de Oportunidades:** Monitoramento contínuo do fluxo financeiro. A IA identifica gastos altos, pesquisa soluções reais e envia alertas com sugestões diretas de redução de custos.

* **Metas Financeiras Guiadas:** O usuário define um objetivo. O sistema calcula a parcela mensal e a IA varre as despesas atuais para indicar exatamente onde economizar para atingir a meta.

* **Simulador Financeiro Pessoal:** Avalia os custos e investimentos atuais do cliente, mostrando o impacto de diferentes abordagens, permitindo que o usuário altere os valores manualmente para encontrar o melhor cenário.

## Público-Alvo

| Segmento | Perfil | Dor principal | 
| ----- | ----- | ----- | 
| Pessoas Físicas (CLT, MEI, etc.) | Pessoas que tentam controlar o dinheiro, mas não fecham o mês no verde. | Alto nível de preocupação com dinheiro e falta de alternativas eficientes para reduzir despesas. | 

## Diferenciais

Após uma análise mercadológica dos principais aplicativos financeiros, identificamos que a maioria utiliza IA de forma **passiva** (apenas respondendo perguntas sobre os próprios gastos) ou para reter o usuário no seu próprio ecossistema de investimentos. 

O diferencial do FIMAP é a **ação e a imparcialidade**: não apenas mostramos o problema, mas a IA busca soluções reais fora do app (no mercado aberto) para cortar gastos, além de simular investimentos de forma imparcial.

| Funcionalidade / Diferencial | **FIMAP** | Organizze | Pierre | Dinzo / Buddy B | 
| :--- | :---: | :---: | :---: | :---: | 
| **Detector de Oportunidades** (Busca ativa de planos mais baratos no mercado) | ✅ | ❌ | ❌ | ❌ | 
| **Simulador de Investimentos Imparcial** (Foco educacional, sem vender produto próprio) | ✅ | ❌ | ❌ | ❌ | 
| **Assistente IA Conversacional** | ✅ | ✅ | ✅ | ⚠️ | 
| **Centralização bancária via Open Finance** | ✅ | ✅ | ✅ | ⚠️ | 
| **Foco principal da IA** | **Buscar soluções externas** | **Analisar dados passados** | **Vender produtos da empresa** | **Projetar fluxo de caixa** | 


## Tecnologias

| Camada | Tecnologia | 
| ----- | ----- | 
| Front-end (Web) | Tailwind, Vue.js, TypeScript | 
| Mobile | Kotlin, Jetpack Compose | 
| Back-end | Node.js, JavaScript | 
| Inteligência Artificial | Cloudflare Workers, gemma-4-26b-a4b-it | 
| Banco de dados | MySQL | 
| Infraestrutura/Deploy | Azure App Service, Render, Github | 
| Conectividade | Provedor Open Finance | 

## Artefatos e Documentação

| Etapa do Projeto | Links de Acesso |
|------------------|-----------------|
| **Requisitos** | [RN](https://docs.google.com/document/d/1Rcx7Q1sOhEdZ10WHrPW59SdkeK7YQWoIa-DzfcK6B-o/edit?usp=sharing) • [RF](https://docs.google.com/document/d/14yVumIdsQ9BdmwzZstf8ka7flUwIH5oX/edit?usp=sharing&ouid=106577692142462691391&rtpof=true&sd=true) • [RNF](https://docs.google.com/document/d/1N2HAioVkY6YqSe5BItpo7UpseXKgebejmkF3y4f2tL8/edit?usp=sharing) |
| **Planejamento** | [TAP - Termo de Abertura (Miro)](https://miro.com/app/board/uXjVHpa3Jh4=/?share_link_id=523195214914) |
| **Modelagem de Dados** | [Modelo Conceitual](https://drive.google.com/drive/folders/1YK91x_gYVm27MBjn0p-XSy6qQ9UA_YxE?usp=sharing) • [Modelo Lógico](https://drive.google.com/drive/folders/1WQaGQ_0MAAIlf1oeLUtf_6N3eM9PGQWn?usp=sharing) |
| **Back-end e API** | [Repositório Github](https://github.com/Guhhxz/Back-end-FIMAP) • [Swaggerhub](https://app.swaggerhub.com/apis/asd-1e6/fimap-api/3.0.0) |
| **Design / UI UX** | [Protótipo no Figma](https://www.figma.com/design/n9xy7RJBfoPaCrBypary09/FIMAP?node-id=0-1&t=TCJwFEc0mMgeu5Zw-1) |
| **Qualidade e Testes** | [Plano e Documento de Testes](https://drive.google.com/drive/folders/13d5K0VUlFKNwP62hLj8w9BEgiCKD2Qti?usp=sharing) |

## Autoria e Equipe

* **Desenvolvedores:** [Arthur](https://github.com/Thuzs), [Murilo](https://github.com/Murilo-Antunes), [Hugo](https://github.com/Guhhxz), [Pedro](https://github.com/pedrorodriguesdev), e [Anderson](https://github.com/Nephyro)
* **Orientadores:** [Prof. Leonid](https://github.com/fernandoleonid), [Prof. Marcel](https://github.com/MarcelNT) e [Prof. João](https://github.com/Joao-Meyer)
* **Instituição:** [SENAI Jandira](https://www.sp.senai.br/unidade/jandira/) - Curso de Desenvolvimento de Sistemas

---
⭐ Gostou do projeto? Deixe uma estrela no repositório!
