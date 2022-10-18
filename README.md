[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8959785&assignment_repo_type=AssignmentRepo)
# Plantilla para tarea (Python)

Esta es una plantilla para crear una tarea auto-corregida (autograded) en [github classroom](https://classroom.github.com/classrooms)

## Instrucciones para los estudiantes

- Lean cuidadosamente `enunciado.ipynb` y completen donde corresponda
- Implemente las funciones y clases que se piden en `tarea.py`
- Los *tests* en `test_tarea.py` pueden inspeccionarse pero no modificarse
- Los resultados se evaluarán en base al último *commit* antes de la fecha y hora de entrega
- Haga *commits* con sus avances regularmente. Se evaluará su progreso en base al histórico de *commits*. 
- Se espera que sigan el [código de ética de la ACM](https://www.acm.org/code-of-ethics)


## Instrucciones para profesores

(Borre esta sección del README cuando termine de redactar la tarea)

### Configurando su *classroom*

- [Cree una organización de github](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch) para alojar las tareas
- [Cree un *classroom* usando la organización recién creada](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/manage-classrooms)
- (Opcional) Suba la lista (*roster*) de estudiantes


### Configurando el código inicial para su tarea

- Cree un repositorio **privado** para su tarea [usando este repositorio como plantilla (*template*)](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) dentro de la organización
- Modifique `tarea.py` y `test_tarea.py` según sus necesidades
- Agregue en `requirements.txt` las librerías que se importan en `test_tarea.py`
- Modifique `.github/classroom/autograding.json` para configurar sus *tests*
- (Opcional) Si añadió nuevos archivos que deben ser *testeados* entonces modifique `.github/workflow/classroom.yaml` (ver comentario en la linea 6)


### Crear una tarea en *github classroom*

- Seleccione su *classroom* en la [interfaz de github classroom](https://classroom.github.com/classrooms)
- Haga click en el boton verde "New assignment". Escoja el título y la fecha límite (*deadline*). Selecciona si la tarea es individual o en grupo
- Deje el repositorio como privado: de esa manera sólo usted y los miembros del grupo pueden ver los repositorios
- Agregue el repositorio de código inicial (sección anterior) 
- No incorpore pruebas autocorregidas en la interfaz (ya están incorporadas en su repositorio)
- Un enlace para distribuir la tarea se creará. Cuando los estudiantes acepten la tarea haciendo click en el link se creara un repositorio privado en la organización
