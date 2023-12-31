# GardenOroVerde-MNE_Tutorial
Podés visitar la página web del Garden Oro Verde acá: [https://cuttinggardens2023.org/gardens/oro-verde/](https://cuttinggardens2023.org/gardens/oro-verde/)

Tutores del Garden Oro Verde:

	- Brigitte Aguilar, Universidad Nacional de Entre Ríos - CONICET
	- Sofía Poux,  Universidad Nacional de Entre Ríos - CONICET
	- Elizabeth Young, Universidad Nacional de Entre Ríos - CONICET

 ## Qué necesitas para el tutorial
Por favor, seguí los siguientes pasos antes del comienzo de los tutoriales:

Paso 1: Descargá las notebooks del tutorial que se encuentran en este repositorio. Guardalas en una carpeta de tu computadora.

Paso 2: Descargá la [carpeta](https://drive.google.com/drive/folders/1O7c_1LH-i5KSSZhoew4meIr4l44zcVF6?usp=drive_link) con los datos [1]. Guardala en la carpeta donde se encuentran las notebooks del tutorial.

Paso 3: Instalá [Anaconda](https://www.anaconda.com/download) en tu computadora.

Paso 4: Instalá la versión actualizada de MNE-Python (necesitas una instalación completa *con todas las dependencias*, **no** "MNE-Python con funcionalidades básicas únicamente"). Consulta las instrucciones en:https://mne.tools/stable/install/installers.html

Paso 5: Utilizaremos el IDE Visual Studio Code (VS Code) para correr nuestras notebooks. Si no lo tenés instalado podés descargarlo acá: https://code.visualstudio.com/

Paso 6: Para verificar que MNE-Python se instaló correctamente, por favor prueba correr esta breve notebook [0-Chequeo_instalacion](0-Chequeo_instalacion.ipynb). Si utilizás VS Code deberás seleccionar el *kernel* de MNE-python (1.5.1_1) antes de correr la notebook. 

### Jupyter Notebook en VS Code

Para correr las Jupyter Notebook de este tutorial en VS Code debes ir a menú File/Open Folder y en la ventana del explorador seleccionar la carpeta donde guardaste las notebooks del tutorial. Una vez abierta la carpeta, podrás ver las notebooks del tutorial en el lado izquierdo (Explorer). Deberás tener instaladas las extensiones de Python y Jupyter en VS Code. 

## Programa
#### MNE Python introduction I and II (Wednesday 18/10/2023)
 - 15:00 – 15:20 Presentación e introducción a los tutoriales
 - 15:20 – 16:20 [1-Preprocesamiento](1-Preprocesamiento.ipynb)
 - 16:20 - 16:30 Descanso
 - 16:30 - 17:15 [2-Analisis_temporal](2-Analisis_temporal.ipynb)
 - 17:15 - 18:00 [3-Analisis frecuencial](3-Analisis frecuencial.ipynb)
#### MNE Python advanced III and IV (Thursday 19/10/2023)
 - 15:00 – 15:45 [4-Modelado_forward](4-Modelado_forward.ipynb)
 - 15:45 – 16:30 [5-Localizacion_fuentes](5-Localizacion_fuentes.ipynb)
 - 16:30 - 16:45 Descanso
 - 16:45 - 17:30 [6-Analisis_de_grupos](6-Analisis_de_grupos.ipynb)
 - 17:30 - 18:00 Conclusiones y discusión

### Referencias y Créditos
*[1]* El dataset utilizado en este tutorial es un fragmento del dataset de acceso libre: [Multimodal faces dataset for PracticalMEEG handson tutorials](https://zenodo.org/record/7405048)

El código de estos tutoriales está basado en [PracticalMEEG2022: MNE-python hands-on tutorial](https://zenodo.org/record/7602381). Autora: Britta Westner. 

Parte del código de estos tutoriales ha sido fuertemente inspirado por este artículo:

Mainak Jas, Eric Larson, Denis Engemann, Jaakko Leppakangas, Samu Taulu, Matti Hamalainen,and Alexandre Gramfort. 2018. A Reproducible MEG/EEG Group Study With the MNE Software: Recommendations, Quality Assessments, and Good Practices. Frontiers in Neuroscience. 12, doi: 10.3389/fnins.2018.00530
