# github_ejemplo
Lo mismo que he hecho en local, ahora desde servidor externo.

## Pasos para sincronizar con Internet
0. **Pull**. No sabemos si alguien ha hecho cambios en los archivos de internet. Deberíamos descargarlos.
0. En cuanto escribimos algo que está sin grabar, en la pestaña de este archivo sale un punto gordo, para avisarnos.
0. Grabar los cambios (Ctrl+S) - Aparece una marca en el icono de *source control* con el número de archivos en los que hemos guardado cambios.
1. **Stage**: Marcar los archivos cambiados para que se preparen para ser "controlados" por el sistema.
1. **Commit**: Añadir los archivos marcados a un nuevo punto de control de versiones.
1. **Push**: sincronizar (subir) lo que tenemos en nuestro ordenador

## Errores posibles:

1. **No hacer stage**. Si no le dais al `+`, no hay nada que confirmar. El programa te sugiere añadir él mismo los cambios.
2. **No poner mensaje de commit**. El programa te abre una pestaña para que lo ponga. Hay que escribirlo, guardar y cerrar esa pestaña.
3. **Olvidar sincronizar**. Esto no puedo saltármelo.