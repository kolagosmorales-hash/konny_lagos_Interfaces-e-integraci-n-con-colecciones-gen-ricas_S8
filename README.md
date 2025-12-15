Semana 8: Interfas e integracion con colecciones genericas
Descripcion del Sistema:
SalmonApp es una aplicación desarrollada en java utilizando programación orientada a objetos, el sistema permite registrar distintas entidades del dominio salmonero, como empleados, proveedores, mediante una interfaz grafica básica construida con JOptionPane. 
El proyecto aplica conceptos como interfaces, herencia, polimorfismo, colecciones y validación de tipos utilizando el operador instanceof

Estructura del proyecto: 
El proyecto esta organizado en los siguientes paquetes:
-app --> contiene la clase principal Main, desde donde se inicia la ejecución del sistema 
-model --> contiene la clase del dominio y la interfaz del sistema:
  *Registrable (interfaz)
  *Empleado
  *Proveedor 
-data --> contiene la clase GestorEntidades, encargada de administrar una colección genérica de objetos que implementan la interfaz registrable y aplicar validaciones mediante instanceof 
-ui --> Contiene la clase MenuGUI responsable de la interfaz grafica del sistema usando JOptioPane

Clase e interfaces utilizadas:
-interfaz: 
*Registrable 
-clases: 
*Empleado
*Proveedor 
*GestorEntidades
*MenuGUI 
*Main

Ejecucion del programa:
1. Clonar el reprositorio: https://github.com/kolagosmorales-hash/konny_lagos_Interfaces-e-integraci-n-con-colecciones-gen-ricas_S8/blob/main/SalmonApp.zip
2. ubica la clase principal
3. ejecuta la clase Main
4. el sistea mostrara una interfaz grafica con un menu que permite:
   - Registrar empleados
   - Registrar proveedores
   - Mostrar los resumenes de las entidades registradas 
