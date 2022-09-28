## Taller de Bioinformática

<br><br>

### `Recomendaciones importantes:`
#### I) `Lee cuidadosamente el ` [programa completo del taller](https://raw.githubusercontent.com/bioinfo01123/taller2022/main/PROGRAMA%20TALLER%20DE%20BIOINFORM%C3%81TICA.pdf) `, revisa los requerimientos de trabajo y requisitos computacionales, debes cumplir con estos criterios (la velocidad de internet es crucial para darle fluidez al contenido, puedes revisar tu velocidad de internet` [aquí](https://www.speedtest.net/es) `o` [aquí](https://fast.com/es/)`).`<br>
#### II) `Lee y sigue cuidadosamente las instrucciones de instalación para evitar errores.`<br>
#### III) `Si ya tienes una versión de Python instalada no es recomendable que continues con la instalación.`<br>
#### IV) `Puedes revisar la presencia de Python en Panel de Control > Programas y características.`<br>
#### V) `Si tienes dudas o problemas con la instalación escríbenos al siguiente correo:` [bioinfo01123@gmail.com](mailto:bioinfo01123@gmail.com)`.`<br><br><br><br>


### `INSTALACIONES`


## **Instalación de Python: Windows** <img src="https://upload.wikimedia.org/wikipedia/sr/thumb/1/14/Windows_logo_-_2006.svg/644px-Windows_logo_-_2006.svg.png" width = 15%>

#### **1**. Descarga la versión 3.6.7 de Python ([Descargar](https://www.python.org/ftp/python/3.6.7/python-3.6.7-amd64.exe))

#### **2**. Una vez realizada la descarga dirígete a la carpeta de la descarga y encuentra el ejecutable `python-3.6.7-amd64.exe`.<br>

[Antes de continuar puedes ver el siguiente video para guiarte en la instalación de Python](https://youtu.be/WjLLEEaQ_RQ).<br>

#### **3**. Da click derecho sobre `python-3.6.7-amd64.exe` y posteriormente ejecutar como administrador.<br>

#### **4**. Te aparecerá una ventana como la que se muestra a continuación.<br>
<img src="https://raw.githubusercontent.com/bioinfproject/bioinfo/master/Folder/Python_2.PNG" width = 65%><br>

- a) **Activar la casilla** **`Add Python 3.6 to PATH`**<br>
- b) **Desactivar la casilla** **`Install launcher for all users (recommended)`**<br>
- c) **Dar click en el botón** **`Install Now`**<br>
- d) **Dar click en el botón** **`Close`**<br><br>


#### `Validar la instalación de Python 3.6.7`.

#### **5**. Para abrir una terminar nueva de windows presiona las teclas Windows + R al mismo tiempo.

#### **6**. Escribir `cmd` o `CMD` en la ventana de ejecución y dar click en `OK`.

#### **7**. Una vez abierta la terminal escribe el siguiente comando y da enter (mostrará la versión de Python instalada).

```bash
python --version
```

<img src="https://raw.githubusercontent.com/bioinfo01123/taller2022/main/terminal.jpg" width = 95%><br>

<br>

## **Instalación de Python: Macintosh** <img src="https://raw.githubusercontent.com/bioinfo01123/taller2022/main/Macintosh.png" width = 12%>

#### `Las computadoras Mac ya tienen instalado Python 3 por defecto, para comprobar su existencia realiza el siguiente paso.` 

#### **1**. Abrir la terminal y escribir el siguiente comando (mostrará la versión de Python instalada).

```bash
python3 --version
```

<br>

## **Instalación de Jupyter Notebook** <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1200px-Jupyter_logo.svg.png" width = 15%>

[Jupyter Notebook](https://jupyter.org/): es una aplicación web de código abierto que te permite crear y compartir documentos que contienen código, visualizaciones y texto enriquecido.

[Antes de continuar puedes ver el siguiente video para guiarte en la instalación de Jupyter Notebook](https://youtu.be/5Xloczl-K_w).<br>

#### **1**. Una vez validada la instalación de Python abre una terminal de windows nueva (Windows + R, luego escribe cmd).

#### **2**. Copia y pega el siguiente comando en la terminal y da enter para instalar Jupyter Notebook.<br>

```bash
pip install notebook
```

#### `Validar la instalación de Jupyter Notebook`.

#### **3**. En la misma terminal escribir el siguiente comando y dar enter (tras ejecutar el comando se abrirá el navegador predeterminado con el ambiente interactivo de Jupyter Notebook).<br>

```bash
jupyter notebook
```

<br><br>

## **Instalación de módulos usados en el taller** <img src="https://pypi.org/static/images/logo-small.95de8436.svg" width = 15%>

[Antes de continuar puedes ver el siguiente video para guiarte en la instalación de módulos de Python](https://www.youtube.com/watch?v=bij66_Jtoqs&ab_channel=codebasics).<br>

Instalación de `numpy` (los demás módulos se instalan de la misma forma).

```bash
pip install numpy
```

### **Instalar los siguientes módulos**
`pandas`  
`matplotlib`  
`scipy`  
`openpyxl`  
`colormap`  
`easydev`  
`xlsxwriter`  
`requests`  
`abifpy`  
