# 🖥️ WebOS File Manager Pro

> Um gerenciador de arquivos virtual completo executado no navegador, com editor de código integrado e navegador HTML embutido.

[![HTML](https://img.shields.io/badge/HTML-100%25-E34C26?logo=html5&logoColor=white)](https://github.com/daniellorenzo2050-png/webfs-project)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Deno](https://img.shields.io/badge/Deno-Ready-black?logo=deno&logoColor=white)](https://deno.land)

---

## ✨ Características

### 📁 Gerenciador de Arquivos Virtual
- Criar, renomear e deletar arquivos e pastas
- Navegação intuitiva com breadcrumb interativo
- Sistema de arquivos persistente com localStorage
- Suporte a múltiplas extensões de arquivo

### 💻 Editor de Código Integrado
- Editor de código com syntax highlighting via **CodeMirror**
- Suporte para:
  - 🔴 **HTML** - Com preview em tempo real
  - 🟡 **JavaScript** - Com validação
  - 🔵 **CSS** - Com formatação
  - 🟢 **JSON** - Com validação de estrutura
- Atalho **Ctrl+S** para salvar rápido
- Interface elegante com tema Monokai

### 🌐 Navegador HTML Integrado
- Execute e visualize arquivos HTML diretamente
- localStorage virtual para aplicações web
- Sandbox seguro com isolamento de contexto
- Preview em tempo real

### 🎨 Interface Moderna
- Design responsivo com **Bootstrap 5**
- Ícones bonitos com **Font Awesome 6**
- Animações fluidas e suaves
- Tema claro e intuitivo
- Totalmente acessível

---

## 🚀 Como Usar

### No Navegador
Abra o arquivo `index.html` em qualquer navegador moderno:

```bash
# Usando um servidor local
python -m http.server 8000
# ou
npx http-server
```

Acesse: `http://localhost:8000`

### No Deno
Se estiver rodando no **Deno**, use:

```bash
deno run --allow-net --allow-read https://deno.land/std/http/server.ts
```

---

## 📦 Funcionalidades em Detalhes

### 🗂️ Sistema de Arquivos
```
/
├── Sistema/
│   └── data/
│       └── localStorage.json
└── index.html
```

### ⌨️ Atalhos de Teclado
| Atalho | Ação |
|--------|------|
| **Ctrl + S** | Salvar arquivo |
| **Clique** | Abrir pasta ou arquivo |
| **Duplo clique** | Editar item |

### 🎛️ Botões Principais
- **📁 Nova Pasta** - Crie diretórios
- **📄 Novo Arquivo** - Crie arquivos vazios
- **🔌 Reset** - Limpe tudo (cuidado!)
- **▲ Subir** - Volte para pasta anterior

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| **Bootstrap** | 5.3.0 | Framework CSS |
| **CodeMirror** | 5.65.13 | Editor de código |
| **Font Awesome** | 6.4.0 | Ícones |
| **LocalForage** | 1.10.0 | Armazenamento persistente |
| **SweetAlert2** | 11 | Diálogos elegantes |

---

## 📋 Requisitos

- ✅ Navegador moderno (Chrome, Firefox, Safari, Edge)
- ✅ JavaScript habilitado
- ✅ LocalStorage disponível

---

## 🎯 Casos de Uso

- 📚 **Educação** - Aprender HTML, CSS, JavaScript
- 🧪 **Prototipagem** - Testar código rápido
- 📝 **Anotações** - Armazenar snippets de código
- 🎨 **Design** - Criar componentes web
- 🔧 **Desenvolvimento** - Debug de aplicações web

---

## 🚀 Próximas Features

- [ ] Exportar arquivos como ZIP
- [ ] Importar arquivos do computador
- [ ] Tema escuro
- [ ] Suporte a mais linguagens
- [ ] Git integration
- [ ] Colaboração em tempo real

---

## 📝 Exemplo de Uso

1. **Clique em "Novo Arquivo"**
2. **Digite o nome:** `hello.html`
3. **Escreva seu código:**
   ```html
   <!DOCTYPE html>
   <html>
   <head>
     <title>Olá Mundo</title>
     <style>
       body { text-align: center; font-size: 24px; }
     </style>
   </head>
   <body>
     <h1>🎉 Olá WebOS!</h1>
   </body>
   </html>
   ```
4. **Clique em "Salvar"** (Ctrl+S)
5. **Clique no ícone ▶️ para visualizar**

---

## 🤝 Contribuindo

Sugestões e melhorias são bem-vindas! Sinta-se livre para:
- Abrir issues
- Fazer pull requests
- Compartilhar ideias

---

## 📄 Licença

Este projeto está sob licença **MIT**. Veja `LICENSE` para mais detalhes.

---

## 👨‍💻 Autor

**Daniel Lorenzo**
- GitHub: [@daniellorenzo2050-png](https://github.com/daniellorenzo2050-png)
- 💼 Desenvolvedor Full Stack

---

## 🌟 Se curtiu, deixe uma ⭐!

Desenvolvido com ❤️ e ☕

```
███████████████████████████████████
█ WebOS File Manager Pro           █
█ Gerenciador de Arquivos Virtual  █
█ Feito com HTML, CSS e JavaScript █
███████████████████████████████████
```

**Versão:** 1.0.0  
**Última atualização:** 2026  
**Status:** ✅ Em produção