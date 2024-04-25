# Ambiente PySpark e JupyterLab, implementando Delta Lake e Apache Iceberg

### Integrantes
- [Pedro Henrique Hahn](https://github.com/pedrohahn)
- [Pedro Henrique Guedes](https://github.com/Pedroguedez)
- [Charles Clezar](https://github.com/CharlesClezar)

### Dataset
https://www.tablab.app/view/parquet?datatable-source=demo-house-price

### Instalando as dependências

```bash
pip install jupyterlab
pip install pyspark
pip install delta-spark
pip install iceberg
```

### Virtualização com Docker
```bash
docker pull jupyter/pyspark-notebook
```
```bash
docker run -p 8888:8888 jupyter/pyspark-notebook
```

### Rodando o projeto
No Prompt de Comando, dar o seguinte comando
```bash
python -m notebook
```
