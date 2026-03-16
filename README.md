# ☁️ Appnet Pro

O **Appnet Pro** é um gerenciador de arquivos APK moderno e leve, que funciona diretamente no seu navegador. Ele permite armazenar, organizar e baixar seus instaladores Android com segurança e privacidade.

> **Status do Projeto:** 🟢 Operacional (v2.0)  
> **Link para Acesso:** `https://seu-usuario.github.io/appnet/`

---

## 🚀 Funcionalidades

* **Armazenamento Persistente:** Utiliza a tecnologia *IndexedDB* para manter seus APKs salvos mesmo após fechar o navegador.
* **Compressão Inteligente:** Usa a biblioteca `JSZip` para comprimir os arquivos e economizar espaço local.
* **Interface Premium:** Design escuro (dark mode) otimizado para facilitar a visualização e gestão dos apps.
* **Segurança HTTPS:** Pronto para ser hospedado no GitHub Pages com criptografia total.
* **Integração Firebase:** Estrutura preparada para conexão com a nuvem do Google (Firebase Storage).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5/CSS3:** Estrutura e estilização moderna.
* **JavaScript (ES6+):** Lógica do sistema e manipulação de arquivos.
* **JSZip:** Compressão e descompressão de dados.
* **Firebase API:** Preparado para backup em nuvem real.
* **IndexedDB:** Banco de dados interno do navegador.

---

## 📦 Como usar?

1.  **Adicionar:** Clique no botão **+ ADICIONAR APK** no topo da página.
2.  **Aguardar:** O sistema irá processar e comprimir o instalador automaticamente.
3.  **Gerenciar:** Seus apps aparecerão em cartões com nome, tamanho e data.
4.  **Baixar:** Clique em **Baixar** para extrair o APK original e instalá-lo no seu dispositivo.

---

## 🔧 Configuração para Desenvolvedores

Se você deseja clonar este projeto e usar seu próprio banco de dados Firebase:

1. Edite o arquivo `index.html`.
2. Localize a constante `firebaseConfig`.
3. Substitua as credenciais pelas do seu [Firebase Console](https://console.firebase.google.com/).
4. Certifique-se de que as regras do Storage permitam leitura e escrita.

---

## 🔒 Privacidade e Tranca de Dados

Este aplicativo foi desenvolvido com foco na persistência. De acordo com as diretrizes do projeto, todos os dados aprendidos e armazenados possuem um "lock" de segurança no banco de dados local do navegador, evitando perdas acidentais ao sair da página.

---
*Desenvolvido para ser simples, rápido e profissional.*
