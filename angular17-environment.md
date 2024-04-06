# Instalação Angular 17 com Linux:
## Preparar ambiente:
1. Baixe a versão LTS do node mais recente 18+ , utilizei: v20.12.1
2. Abra o terminal de comando no diretório onde se encontra o arquivo baixado o Node.js ou navegue até ele pelo terminal de comando
3. Use o comando tar para extrair o conteúdo do arquivo .tar.gz. Por exemplo:
   ```
    tar -xvf nome_do_arquivo.tar.gz
   ```
4. Isso criará um diretório com o nome do  arquivo, que contém os arquivos do Node.js.
5. Navegue para o diretório Node.js
  ```
  cd nome-do-arquivo ```
  ```
6. Instale o Node.js globalmente, copiando os arquivos para o diretório de instalação padrão, como /usr/local/.
   ```
     sudo cp -R * /usr/local/
    ```
8. Verifique a instalação
  ```
    node -v
    npm -v
  ```
## Instale o Angular globalmente
```
  npm install -g @angular/cli
```

![image](https://github.com/ElaineCristinaG/utils/assets/76761529/2bfc2a68-d5b4-4a91-9d6c-643d476b0a6e)
