

## Criando ambiente virtual e gerenciando versões com Poetry e Pyenv

- Criando projeto com Poetry

```bash
poetry new poetry-demo

```

- instalando versão python com pyenv 

  ```bash
  pyenv install 3.10.0
  ```

- Definindo versão local do projeto

  ```
  pyenv local 3.10.0
  ```

- criando ambiente virtual 

  ```bash
  poetry shell
  ```

- Setar no poetry versão da env 

  ```bash 
  poetry env use 3.10
  ```

- instalar uma biblioteca

  ``` bash
  poetry add pyspark 
  ```

  