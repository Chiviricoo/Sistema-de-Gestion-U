3. Sistema para el control del ingreso a la educación superior. Se desea realizar un sistema para gestionar el ingreso a la Universidad por la vía libre (que no venga de un preuniversitario). Se conoce que en la universidad hay una lista personas que se presentan a las variantes de ingresar a la educación superior, así como el listado de carreras que se ofertan y la provincia de la universidad en cuestión; en general se registra de todas las personas que optan por carreras el nombre, el sexo, la dirección y el carné de identidad, el nivel de escolaridad (técnicos medios o bachilleres), la fecha de inscripción y las tres opciones. De los que optan por carreras para el curso por encuentros se conoce además el centro de trabajo, las notas de las pruebas de matemática y español; por otro lado, de los que optan por carreras por concurso para el curso regular diurno se registra además las notas de las pruebas de matemática e historia y si opta por una ingeniería se conoce la nota de la prueba de física y los que no optan por ingeniería se conoce la nota de español. De las direcciones de los estudiantes se registra la calle, el número, el municipio y la provincia. De las carreras que se ofertan se conoce su nombre, la facultad donde se estudian y el número de plazas en concurso para el curso regular diurno y para el curso por encuentros.
El sistema debe permitir las siguientes funcionalidades:
a) Implemente la funcionalidad necesaria para gestionar (insertar, actualizar, eliminar y listar) los datos de los estudiantes de forma independiente (por cada tipo de variante), teniendo en cuenta que a la modalidad del diurno solo se pueden presentar estudiantes de la provincia y tienen que tener menos de 35 años; además debe gestionar los datos de las carreras que se ofertan.
b) Implemente la funcionalidad necesaria para determinar la dirección de un estudiante dado el carné de identidad de este.
c) Implemente la funcionalidad necesaria para determinar el porciento de desaprobados de los estudiantes que optan por una carrera dada en el curso regular diurno.
d) Implemente la funcionalidad necesaria para determinar los datos del estudiante que mejores notas sacó en la modalidad de curso por encuentros y que pide una carrera dada en una de sus opciones.
e) Implemente la funcionalidad necesaria para determinar que porciento de estudiantes que se presentaron en el curso por encuentros son de otra provincia.
f) Implemente la funcionalidad necesaria para determinar el escalafón de los estudiantes con el otorgamiento por carrera y por modalidad, ordenado por el promedio de las notas de mayor a menor y que estudiantes cogieron la carrera; puede quedar de la siguiente forma:
Nombre
Sexo
Matemática
Historia
Física
Español
Promedio
Aceptado

Pedro    
M
97
95.5
99
-
97.16
Sí

Juana
F
82
91.5
79
-
84.16
No


g) Pruebe que las operaciones implementadas en el modelo funcionan correctamente según los datos de prueba que usted le entró al programa.
