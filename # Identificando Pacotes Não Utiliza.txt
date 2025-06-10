# Identificando Pacotes Não Utilizados em um Projeto

Este guia explica como verificar e remover dependências não utilizadas em projetos Node.js e React Native.

## 1️⃣ Instalar o `depcheck`
`depcheck` é uma ferramenta que analisa o código-fonte e identifica pacotes que estão instalados, mas não são referenciados.

### Instalação dentro do projeto:
```sh
npm install --save-dev depcheck

### Verificar a instalação caso precise:
```sh
npm list --depth=0 | grep depcheck

### Listar dependências não utilizadas:
```sh
 npx depcheck

