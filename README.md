# PRIMEIRO DESAFIO (MESA PHP)

Para realizar o desafio basta forkar esse repositório e colocar a mão na massa :)

Nosso primeiro desafio é algo bastante simples...
Dentro do diretório **data**, existe um arquivo com uma lista de itens que servirão como nosso dataset. 
Esse desafio consiste em:

  - Realizar a leitura do dataset disponibilizado.
  - Permitir que o dataset seja filtrado por categorias.
  - Permitir que o formato da exibição possa ser alterado de acordo com o solicitado.

# Filtro por categoria

Deverá ser possível filtrar o dataset através das categorias, por exemplo...
Partindo do pressuposto que estamos filtrando pela QueryString **category**:
    
    - ?category=doces
    - ?category=doces,sucos

Observe que o nome da categoria deve casar exatamente com o que está no dataset, caso se deseje filtrar com duas categorias o seguindo exemplo deve ser utilizado.

# Formato de exibição

Devemos permitir permitir a exibição do dataset em dois formatos (**json** e **xml**).
Fica a critério do desenvolvedor definir como será informado o tipo de exibição desejado.

# Critérios de Aceitação

## Funcionamento

**Deve** conter cobertura de teste unitário, ao menos do funcionamento principal.

## Qualidade

**Deve** passar no Code Sniffer (Standard PSR-2)
