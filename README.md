Aprendizaje Supervisado - Mentorias Diplomatura en Ciencia de Datos 2019
========================================================================

Pagina
------

http://diplodatos.famaf.unc.edu.ar/


Repositorio
-----------

https://github.com/diplodatos2019mentoria/Aprendizaje_Supervisado

-------------------------------------------------------------------------------

Descarga de los Datasets
------------------------

Los Datasets que se sera usado, se pude descargar del siguiente link de Google Drive: 
[Football Dataset](https://drive.google.com/drive/folders/1kpqLVQ4FKzzlEFiku45U42tQameso8Dt?usp=sharing).

**Importante:** Se recomienda descargar los 3 CSVs y ubicarlos en el diretorio `Datasets`.

> [Ver Descripcion del Dataset](./Dataset_Description.md)


Instalación
-----------

1.  Se necesita el siguiente software:

    -   Git
    -   Pip
    -   Python 3.6
    -   TkInter
    -   Virtualenv

    En un sistema basado en Debian (como Ubuntu), se puede hacer:

        sudo apt-get install git python-pip python3 virtualenv

2.  Crear y activar un nuevo [virtualenv]. Recomiendo usar [virtualenvwrapper]. Se puede instalar así:

        sudo pip install virtualenvwrapper

    Y luego agregando la siguiente línea al final del archivo `.bashrc`:

        export WORKON_HOME=$HOME/.virtualenvs
        export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python
        export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv
        [[ -s "/usr/local/bin/virtualenvwrapper.sh" ]] && source "/usr/local/bin/virtualenvwrapper.sh"

3.  Bajar el código:

        git clone https://github.com/diplodatos2019mentoria/Aprendizaje_Supervisado.git


Entorno Virtual
---------------

1.  Para crear y activar nuestro virtualenv:

        mkvirtualenv --python=/usr/bin/python3.6 dd19-as

4.  Instalar dependencias:

        cd Aprendizaje_Supervisado
        pip install -r requirements.txt


Ejecución
---------

1.  Activar el entorno virtual con:

        workon dd19-as



<!---------------------- Links ---------------------->
[virtualenv]: http://virtualenv.readthedocs.org/en/latest/virtualenv.html
[virtualenvwrapper]: http://virtualenvwrapper.readthedocs.org/en/latest/install.html#basic-installation
