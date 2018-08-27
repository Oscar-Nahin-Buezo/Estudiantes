# Estudiantes
Este programa esta desarrollado en Prolog, en el cual contiene alrededor de 200 hechos divididos entre aulas, alumnos, cursos y fechas de examen.
Ejemplo de consultas:
?- lista_estudiantes_por_curso(math101,X).
X = [2000100001, 2000100002, 2000100003, 2000100004, 2000100008, 2000100010, 2000100012, 2002100009, 2002100040|...].

?- lista_fechas_de_examenes(2000103009,X).
X = ['06.04.2018', '15.04.2018', '05.04.2018', '20.04.2018'].

?- aulas_adecuadas_para_zurdos(math101,X).
X = [nh101, nh201, nh301, hkd101, zbr101, prg101, prg201].

En la primera consulta se puede notar que el resultado no muestra todos los resultado y esto de debe a que todo esta metido en una sola lista por lo que no los muestra todo, al menos no en mi pc. Pero los puntos suspensivos al final de la lista indica que au hay elementos por mostar.
