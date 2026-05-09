# Gerador de Currículos Profissionais ✨

Um aplicativo web moderno, rápido e autocontido para criação de currículos profissionais com exportação direta para PDF. Desenvolvido em estrutura **Single-file** (HTML/CSS/JS), permitindo o uso fácil e imediato.

![Preview do Projeto](https://img.shields.io/badge/Status-Operacional-brightgreen)
![Tech](https://img.shields.io/badge/Tech-Vanilla_JS-yellow)
![Design](https://img.shields.io/badge/Design-Modern_2--Column-blue)

## 🚀 Funcionalidades

- **Layout Moderno:** Design de duas colunas (Sidebar escura + Conteúdo principal) inspirado em modelos profissionais contemporâneos.
- **Upload de Foto:** Suporte para imagem de perfil com renderização circular no PDF.
- **Seções Dinâmicas:** Adicione quantas experiências profissionais e formações acadêmicas desejar.
- **Gestão de Habilidades:** Sistema de tags inteligente com sugestões e visualização de barras de competência no PDF final.
- **Persistência Local:** Seus dados são salvos automaticamente no navegador (`LocalStorage`), para que você não perca o progresso ao fechar a aba.
- **Exportação Premium:** PDF gerado via `html2canvas` e `jsPDF` com layout otimizado para impressão A4.
- **Tema Automático:** Suporte para modo escuro (Dark Mode) baseado na preferência do seu sistema.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Estrutura semântica e estilização moderna com Variáveis CSS e Flexbox/Grid.
- **JavaScript (ES6+):** Lógica de estado, manipulação de DOM e validações em tempo real.
- **[jsPDF](https://github.com/parallax/jsPDF):** Biblioteca para geração do arquivo PDF.
- **[html2canvas](https://html2canvas.hertzen.com/):** Captura do layout HTML para renderização fiel no documento.

## 📖 Como Usar

1. Abra o arquivo `index.html` no seu navegador de preferência.
   - *Dica:* Para melhor funcionamento (evitando restrições de segurança de arquivos locais), recomenda-se abrir através de um servidor local (ex: `Live Server` do VS Code ou `python -m http.server`).
2. Preencha as seções do formulário. O progresso será indicado pela barra no topo.
3. Utilize o botão **"Preencher com Dados de Teste"** se quiser ver o layout do PDF antes de digitar seus dados.
4. Clique em **"Gerar e Baixar PDF"** quando todos os campos obrigatórios estiverem validados.

## 📂 Estrutura do Arquivo

- `index.html`: Contém toda a estrutura, estilos (CSS) e lógica (JS) do aplicativo. É o único arquivo necessário para rodar a aplicação.

---
Desenvolvido por Leticia Ribeiro de Souza - Linkedin 
