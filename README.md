# Ficha de Não Conformidade Digital - Lumicenter

Este é um sistema digital e interativo desenvolvido para o setor de **P&D Eletrônicos** da Lumicenter (Formulário **FOR-E-20**). Ele permite registrar e analisar produtos devolvidos por clientes (luminárias, drivers, placas de LED) e exportar um relatório limpo e padronizado em formato PDF.

## 🚀 Funcionalidades

- **Gerenciador de Abas**: Crie, alterne e gerencie múltiplas Fichas de Não Conformidade (FNC) em paralelo, facilitando o trabalho em lote.
- **Nome de Aba Dinâmico**: O título da aba se atualiza automaticamente em tempo real com o nome do cliente ou número da FNC inseridos.
- **Persistência Local (LocalStorage)**: Todos os dados preenchidos são salvos automaticamente no navegador em tempo real, evitando perdas caso a página seja recarregada ou fechada.
- **Migração de Dados**: Recupera automaticamente os dados de sessões anteriores no primeiro carregamento.
- **Máscara Inteligente**: Restrição e formatação automática para os campos `ATENDIMENTO SAC`, `FNC DE ANÁLISE` e `PL. AÇÃO` no padrão `Nº/ANO` (ex: `123/2026`).
- **Sugestão Automática de Nome de PDF**: Ao salvar como PDF (através do botão "Gerar PDF"), o navegador sugere o nome do arquivo padronizado: `FOR-E-20 FNC [nº]-[ano]`.
- **Impressão Limpa**: Layout otimizado para o formato A4 retrato, ocultando elementos de interface como botões e abas.

## 📂 Como Rodar o Projeto

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` diretamente em qualquer navegador web (Chrome, Firefox, Edge, Safari). Não é necessário servidor web ou dependências externas.

## ☁️ Como Publicar e Acessar Online (GitHub Pages)

Para obter um link público e acessar o formulário de qualquer lugar (inclusive no celular ou tablets de suporte), você pode usar o **GitHub Pages**:

1. Crie um repositório no seu GitHub (ex: `ficha-suporte`).
2. Suba os arquivos deste diretório para o repositório.
3. No painel do seu repositório no GitHub:
   - Vá em **Settings** (Configurações).
   - No menu lateral esquerdo, clique em **Pages**.
   - Na seção **Build and deployment**, sob **Source**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
   - Clique em **Save**.
4. Em poucos instantes, o GitHub gerará um link público para o seu site (geralmente `https://seu-usuario.github.io/nome-do-repositorio/`).
