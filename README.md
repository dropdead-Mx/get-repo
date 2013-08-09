

version: Moises
Author:  Germán Martínez Solís (dropdead-Mx)
youtube: https://www.youtube.com/user/TheDarkSideOfLinux
Mail:    gms.linux@gmail.com
                                                                         
                                     
                                                                          

Es una utileria para agregar nativamente desde debian 6 y 7 repositorios 
desde launchpad sin necesidad de modificar el source.list del sistema    
y sin hacer uso alguno de scripts como launchpad-getkeys                 


    _|    _|    _|_|_|    _|_|    
    _|    _|  _|_|      _|    _|  
    _|    _|      _|_|  _|    _|  
      _|_|_|  _|_|_|      _|_| 


          get-repo --ppa[nombre de ppa] --v [version]  
  
          get-repo --ppa webupd8team/java --v oneiric  

--help    para mostrar ayuda 
 
--ppa     Para introducir nombre del ppa ejemplo : 
 
	      get-repo --ppa awn-testing/ppa
 
--v       Para indicar la version compatible de ubuntu con debian
   
          las versiones varian de acuerdo al ppa :  
          lucid (10.04) , natty (11.04) , oneiric (11.10), precise (12.04) quantal (12.10)
          raring (13.04), saucy (13.10) 
 
--r       Para eliminar un repositorio :  
 
          get-repo --r [nombre de ppa] --v [version]  
  
          get-repo --r webupd8team/java --v oneiric  


