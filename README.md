# Setup

Clonar repositorio e instalar compilador g++, [Cmake Windows x64 Installer](https://cmake.org/download/), y las extensiones de vs-code: cmake y cmake tools 

Verificar ruta en CmkaeLists.txt (esta debe ser cambiada si hay distintos .cpp dentro de src/)

![image](https://github.com/user-attachments/assets/b80c017b-eeba-41ad-8e49-3133988820c9)


Ejecutar codigo de prueba con boton de play de Cmake, pero da ERROR (ya que se ejecuto desde un directorio erroneo porque cmake ejecuta desde forma por defecto en {workspaceFolder}/build/Debug, pero se busca hacerlo desde la raiz)

![image](https://github.com/user-attachments/assets/ca42850c-e00f-4db0-8402-12c167dcb187)



Visualizacion correcta ejecutando desde raiz

![image](https://github.com/user-attachments/assets/a0a8feaf-9e28-45ee-97ad-59e671510a63)
