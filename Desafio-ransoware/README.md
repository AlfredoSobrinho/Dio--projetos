# Encrypter/Decrypter Script (Ransomware)

## Descrição

- Estes são simples scripts de Python para criptografar e descriptografar arquivos usando a 
biblioteca `pyaes`. 

- ```decrypter.py```: O script lê um arquivo criptografado, usa uma chave de 
descriptografia para descriptografar os dados, remove o arquivo criptografado e cria um novo arquivo descriptografado.

- ```encrypter.py```: O script lê um arquivo descriptografado, usa uma chave de 
criptografia para criptografar os dados, remove o arquivo descriptografado e cria um novo arquivo criptografado.



## Pré-requisitos

- Certifique-se de ter Python e a biblioteca `pyaes` instalada em seu ambiente.

### Instalação do Python

- Você pode baixar e instalar o Python a partir do [site oficial do Python](https://www.python.org/).

### Instalação do pyaes

- Para instalar a biblioteca `pyaes`, execute o seguinte comando no terminal:
- ```pip install pyaes```

- Se estiver usando Python 3, pode ser necessário usar pip3:
- ```pip3 install pyaes```

### Uso

- Coloque o arquivo criptografado (teste.txt) na mesma pasta que os scripts.

- Edite os scripts para garantir que o nome do arquivo e a chave de criptografia e descriptografia estejam corretos.

- Execute os scripts Python para descriptografar ou criptografar o arquivo.


### Exemplo de Execução usando o arquivo teste.txt :

- ```python encrypter.py teste.txt```

- ```python decrypter.py teste.txt.brt```


### Se estiver usando Python 3, pode ser necessário usar:

- ```python3 encrypter.py teste.txt```

- ```python3 decrypter.py teste.txt.brt```


### Contribuição

- Se quiser contribuir para o projeto, sinta-se à vontade para fazer um fork do repositório e enviar pull requests.

### Licença

- Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.



