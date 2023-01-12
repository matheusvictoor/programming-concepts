# Gerenciamento de arquivos e diretórios em sistemas operacionais

## Como renomear vários arquivos do mesmo tipo, em um diretório que possuem vários outros diretórios

Para renomear todos os arquivos .py desse diretório principal e seus subdiretórios para main.py usando um script de comando do prompt de comando do Windows. Um exemplo de comando seria:

```
FOR /R "python-exercises" %f IN (*.py) DO REN "%f" main.py
```

Esse comando usa o comando FOR para percorrer recursivamente o diretório "python-exercises" e seus subdiretórios, procurando por arquivos com a extensão .py. Quando encontra um arquivo com essa extensão, ele usa o comando REN para renomear o arquivo para main.py.

OBS: é importante ter cuidado ao usar esse comando, pois ele irá renomear todos os arquivos .py que encontrar e todos irão ter o mesmo nome, tenha certeza que é essa a intenção.