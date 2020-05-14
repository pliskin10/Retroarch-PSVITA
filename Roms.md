# Retroarch Playlist y Roms

Una vez nuestro Retroarch instlado y listo para usar en nuestra PS Vita, nos interesa crear nuestras playlist para una mejor gestión del contenido de nuestras ROMS.

Para ello:

- copiamos nuestras roms dentro de la sdcard de nuestra PS Vita, se recomienda tenerlas organizadas por plataforma, 
por ejemplo, quedando una estructura parecido a esto:
                       
                       - PSVITA
                          ux0:
                            roms 
                              Nintendo
                                aquí nuestras roms de nes, formato .zip .7z o .nes
                              Super Nintendo
                                aquí nuestras roms de snes, formato .zip .7z o .smc
                              Mega Drive
                                aquí nuestras roms de snes, formato .zip .7z o .smc

- una vez el directorio roms en nuestra sdcard, ejecutamos Retroarch y en el menú principal:

 - vamos a la opción del menú "Import Content"
 - escogemos "Scan Directory"
 - usamos el navegador de archivos para indicar a Retroarch dónde están ubicadas nuestras roms a importar (por ejemplo, SNES)
 - comenzará el proceso de importación, debemos tener paciencia pues se puede demorar bastantes minutos en el proceso
 - debemos tener en cuenta que Retroarch basa su base de datos en los romsets de no-intro (https://archive.org/search.php?query=no-intro%20romset)
 por lo que si no encuentra el nombre de la rom en su base de datos puede que no nos aparezca en la importación.
 