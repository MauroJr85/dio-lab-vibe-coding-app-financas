# 💸 Finanças em Dia

Projeto desenvolvido para o desafio **"Criando um APP de Organização de Finanças Pessoais com Vibe Coding"**, da **DIO**.

### [🌐 Acesse o aplicativo](https://saldo-com-prop.lovable.app/)


## 📌 Sobre o projeto

O **Finanças em Dia** é um aplicativo de organização financeira voltado para iniciantes.

A proposta é facilitar o controle das finanças pessoais por meio de funcionalidades simples e intuitivas, como:

- Registro de receitas e despesas por conversa;
- Visualização de um resumo financeiro;
- Acompanhamento de metas de economia;
- Sugestões educativas de organização financeira;
- Importação e classificação de despesas a partir de faturas de cartão de crédito em PDF.

O projeto foi concebido como um **MVP (Produto Mínimo Viável)**, utilizando a abordagem de *Vibe Coding* e ferramentas de inteligência artificial.

## 📝 Prompt final — PRD

O prompt abaixo foi elaborado com auxílio do **ChatGPT** e utilizado no **Lovable** para orientar a criação do aplicativo.

```markdown
Crie um aplicativo web responsivo chamado **Finanças em Dia**, em português brasileiro, para iniciantes em organização financeira.

**Objetivo:** facilitar o controle de receitas e despesas por conversa ou importação de faturas de cartão de crédito em PDF.

### Funcionalidades

**1. Painel financeiro**
- Exibir receitas, despesas, saldo mensal e últimas transações.
- Mostrar distribuição das despesas por categoria.
- Atualizar os indicadores automaticamente.
- Permitir selecionar o mês de referência.

**2. Registro por conversa**
- Campo semelhante a um chat.
- Interpretar frases como "Recebi R$ 3.000 de salário" e "Gastei R$ 80 no mercado".
- Identificar valor, descrição, tipo e categoria.
- Permitir confirmar ou corrigir antes de salvar.
- Utilizar regras simples, sem APIs externas de IA.

**3. Importação de fatura PDF**
- Criar área para upload de faturas de cartão de crédito em PDF.
- Utilizar pdfjs-dist para extrair texto localmente no navegador.
- Identificar transações contendo data, estabelecimento e valor.
- Sugerir categorias automaticamente por palavras-chave.
- Exibir os lançamentos extraídos em tabela editável.
- Permitir corrigir, excluir ou confirmar individualmente os itens.
- Importar os itens selecionados somente após confirmação.
- Evitar duplicidades de lançamentos.
- Não contabilizar total da fatura, pagamentos, estornos ou créditos como novas compras.
- Registrar as despesas no mês de referência da fatura, permitindo correção pelo usuário.
- Informar claramente quando não for possível interpretar o arquivo, sem inventar transações.
- Nesta versão, aceitar apenas PDFs com texto selecionável. Não implementar OCR.

**4. Histórico**
- Listar lançamentos com data, descrição, categoria, valor e origem (manual ou PDF).
- Permitir filtrar e excluir lançamentos.

**5. Meta de economia**
- Permitir definir meta mensal.
- Exibir progresso visual considerando o saldo mensal, sem ultrapassar 100% na barra.

### Interface
- Design moderno, limpo, intuitivo e profissional.
- Cores predominantes: verde, branco e cinza-claro.
- Navegação: Painel, Registrar, Importar Fatura, Histórico e Metas.
- Ícones discretos, cartões financeiros e gráficos simples.
- Interface responsiva para desktop e celular.
- Dados fictícios iniciais identificados como demonstração.

### Requisitos técnicos
- React, TypeScript e Tailwind CSS.
- Persistência no localStorage.
- Processamento do PDF exclusivamente no navegador.
- Não enviar nem armazenar o arquivo PDF em servidores.
- Sem autenticação, backend, banco de dados, integrações bancárias ou APIs pagas.
- Não criar funcionalidades extras.
- Todos os botões principais devem funcionar.

**Prioridade:** entregar um MVP funcional, visualmente atraente e adequado para apresentação no desafio da DIO, com foco especial no fluxo de importação e conferência de faturas PDF. Implemente diretamente, sem etapas adicionais de planejamento.
```

## ⚙️ Funcionalidades propostas

| Recurso | Descrição |
|---|---|
| 💬 Conversa financeira | O usuário informa receitas ou despesas em linguagem natural e confirma os dados identificados. |
| 🏷️ Classificação | O sistema sugere uma categoria e permite sua correção. |
| 📊 Resumo financeiro | Visualização de receitas, despesas, saldo e lançamentos. |
| 🎯 Meta de economia | Definição de objetivos e acompanhamento do progresso. |
| 💡 Dicas educativas | Sugestões simples de organização financeira. |
| 📄 Fatura em PDF | Identificação e classificação de compras, sujeitas à revisão e confirmação do usuário. |

## 🤖 Interações com a IA

Durante o desenvolvimento, foram utilizados o ChatGPT, para a elaboração do prompt, e o Lovable, para a criação do aplicativo.

### Registros das interações

![Interação com a IA — Captura 1](https://github.com/user-attachments/assets/36e9ac8b-a8ef-476e-a065-59bff1c6bd96)

![Interação com a IA — Captura 2](https://github.com/user-attachments/assets/3e916889-9fce-4f63-b6ec-e00f9d007a38)

**Observação:** devido à limitação de créditos do Lovable, foi utilizado apenas o prompt apresentado acima.

## 📚 Reflexão sobre o processo

### ✅ O que funcionou bem?

A facilidade de uso do Lovable na criação de um aplicativo simples e funcional a partir de um prompt bem estruturado.

### ⚠️ O que não funcionou como esperado?

A limitação de créditos do Lovable impediu a inclusão de novas funcionalidades que eu pretendia acrescentar ao aplicativo.

### 💡 O que aprendi sobre conversar com IAs?

Aprendi que toda interação com inteligência artificial deve partir de objetivos claros e bem definidos, para que os resultados estejam alinhados ao que se pretende alcançar.
