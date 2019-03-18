#Implementación de MODO KIOSK <h5>
  
  
  * Crear un usuario que va a ser el encargado de kiosk
  
  **useradd kiosk**
  
  **passwd kiosk**
  
  * Modificar el archivo */etc/gdm/custom.conf* las siguientes variables.
  
  **[daemon]**
  
  **AutomaticLoginEnable=true**
  
  **AutomaticLogin=kiosk  = el nombre del usuario con el que se va acceder**
  
