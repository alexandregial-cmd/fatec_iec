name: Pipeline Experimental
on: push

jobs:
  ci-continuous-integration:
    name: Teste de CI
    runs-on: ubuntu-22.04
    steps:
      - name: Mensagem de saudação
        run: echo "Olá, Fatec!"

      - name: Fazendo clone e checkout no meu repositório nesta VM Ubuntu
        uses: actions/checkout@v5

      - name: Zipar os arquivos do meu repositório
        run: zip -r arquivos.zip .

      - name: Listar os arquivos do meu repositório
        run: ls -la
