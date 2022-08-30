# Statistical System Design for School

An elementary school wants to implement a statistical system for classifying students' test scores.
The school uses a grading system based on numbers that go from 0 to 5, with different ranges with labels that emphasize student performance.

The system must generate statistical data that can help teachers identify groups or students with difficulties. Currently there is information on the test scores for each of the students in class F, the system must generate statistical data from the following information:

Nombre	    Género	    Materia	      Nota
maria	        f	      matemáticas	    4.4
armando	      m	      matemáticas	    4.6
maria	        f	        idiomas	      4.1
armando	      m	        idiomas	      3.1

Grades at the school are assigned on the following rank scale:

Rango de notas	    Calificación 
(4.5 - 5]	            Excelente
(3.5 - 4.5]	        Sobresaliente
(2.5 - 3.5]	          Regular
(1 - 2.5]	          Insuficiente
[0 - 1]	              Deficiente

The algorithm must be able to answer the following questions:
● How many exams have a score lower than the group average?
● How many exams are underrated?
● What is the subject with the best average performance for the whole group?
● Who is the student with the best performance for biology?

## Folder Structure 

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
