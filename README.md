# Tutorial: Criando um Repositório Remoto e Realizando o Primeiro Commit

[![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este repositório tem como objetivo mostrar passo a passo como criar um repositório remoto no GitHub e realizar o primeiro commit utilizando a branch `main`.

---

## Pré-requisitos

- [Git instalado](https://git-scm.com/downloads)
- Conta no [GitHub](https://github.com/)

---

## Tecnologias Utilizadas

- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
- ![Markdown](https://img.shields.io/badge/markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

---

## Passo a Passo

### 1. Criar o Repositório no GitHub

1. Acesse [https://github.com/](https://github.com/)
2. Clique em **"New repository"**
3. Preencha:
   - **Repository name**
   - Opcionalmente, uma **descrição**
   - Marque a opção **"Add a README file"** se quiser começar com um README
4. Clique em **"Create repository"**

---

### 2. Clonar o Repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 3. Adicionar Arquivos Locais

Se o repositório ainda não tiver arquivos:

```bash
echo "# Meu Projeto" >> README.md
touch .gitignore
```

### 4. Inicializar o Git (caso ainda não tenha sido feito)

```bash
git init
```
### 5. Inicializar o Git (caso ainda não tenha sido feito)

```bash
git add .
git commit -m "Primeiro commit"
```

### 6. Definir a Branch Principal como main

```bash
git branch -M main
```

### 7. Adicionar o Repositório Remoto

```bash
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
```

### 8. Enviar o Commit para o GitHub

```bash
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
```

## Autor

[![Fabio Lucas](https://img.shields.io/badge/Fabio%20Lucas-GitHub-black.svg)](https://github.com/fabiolucasz/)

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.