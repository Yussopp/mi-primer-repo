# mi-primer-repo
lo descubriremos juntos

















































## Nivel 3: conflicto resuelto en pareja

El dueño del repositorio y Santiago Pareja Quintero modificaron
la misma línea de Main.java desde ramas diferentes.

El cambio del dueño se incorporó primero a main. Después, Santiago
actualizó main e intentó fusionar su rama saludo-santiago.
Git detectó un conflicto porque ambos habían cambiado el mismo saludo.

La resolución conservó los dos mensajes en instrucciones
System.out.println separadas y eliminó las marcas del conflicto.

Se comprobó el resultado con:
- javac Main.java
- java Main

El programa compiló sin errores y mostró ambos mensajes.