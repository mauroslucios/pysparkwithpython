# pysparkwithpython
- docker
- python
- spark
- pyspark

### comandos docker
- Criando container docker com volume atachado
    - docker run -d -P --name sparkWithPythonNotebbok -v /home/mauro-lucio/Documentos/projetos/python_projects/pythonSpark/sparkdata:/home/jovyan/work jupyter/all-spark-notebook:spark-3.5.0
- Copiando arquivos entre host e container
    - docker cp ~/Downloads/sparkSQLBasic.ipynb sparkWithPythonNotebbok:/home/jovyan/work/arquivos