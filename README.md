# Challenge
Desarrollo de challenge para participar de pasantía.

Este proyecto es realizado en Jupyter Notebook.
Antes de comenzar instalo lo siguiente en el prompt de anaconda:
- pip install google-cloud-bigquery
- pip install apache-airflow

Tambien, para poder utilizar Git a través de Anaconda Navigator, entrar en este último, ir a 
Enviroments, clickear "Not Installed", buscar Git y luego pinchar "Apply". Para asegurarse que 
Git está activado se entra al prompt de Anacoda y se corre
- git --version

Para comenzar, busco una base de datos (.csv) en Kaggle ya que me costó comenzar esta simulación sin tener 
alguna disponible.

En el repositorio se encuentran dos archivos disponibles, el primero contiene la simulación del proceso ETL 
utilizando Python, y el segundo corresponde al proceso de ingestación de datos a través de Apache Airflow, el cual 
no sé si está en lo correcto ya que es mi primera vez utilizando este programa.

Una vez finalizado el codigo en Python, utilizo nuevamente el prompt de Anaconda, esto para trabajar (también por primera vez) con Git:
1. Configuro el nombre de usuario y correo de Git:
   - git config --global user.name "Valeria_LH"
   - git config --global user.email "valeria.scarlett01@gmail.com"
2. Inicializo un repositorio Git
   - git init
3. Agrego el archivo al repositorio
   - git add C:\Users\valer\PYTHON\Simulacion\Code_Challenge.ipynb
