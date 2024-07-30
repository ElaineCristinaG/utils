# Mostrar branch atual no terminal bash:
## Configuração
1. Abra o arquivo bash: nano ~/.bashrc 
3. Cole o bloco de codigo ao final do documento:
   ```
   parse_git_branch() {
        git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
      }
      export PS1="\u@\h \[\033[32m\]\w\[\033[33m\]\$(parse_git_branch)\[\033[00m\] $ "

