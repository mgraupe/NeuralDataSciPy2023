# 2022 Course : Neural Data Science with Python

![Logo](miscFiles/course-logo.png "Course Logo")

This course provides a general introduction in the high-level, general-purpose porgramming lanuage [Python](https://www.python.org). 
It will furthermore cover basic analysis concepts used in the field of Neuroscience. 

### Objective of the Course 

The field of neuroscience is becoming more and more quantitative and this development is accompanied by an ever-increasing stream of data derived from the brain. It is essential that this development
is performed by neuroscientists who are ready and able to process this data. Data science is an emerging field dedicated to understanding principles in data sets. This teaching unit aims to introduce the principles of data science applied to neural data.


Concretely, *Neural Data Science with Python* teaches how to handle, analyze, visualize neural data, to create models and to run simulations of neural systems using the Python programming language. The students will acquire to use different general and specific Python modules such as numpy, scipy, matplotlib, pandas, brian and the use of the Jupyter Notebook environment. The course will be supplemented with interactive courses on [DataCamp](https://www.datacamp.com/) aimed at helping students build programming skills at their own pace. 

### Prerequisites

Bases in neuroanatomy and physiology of the central nervous system are useful. All data science- and programming concepts are introduced, explained and applied in the course. No prior knowledge in programming is required as this course is for beginners.

The below <i>resources</i> can be used for optional preparation of the course. In particular, the Python Tutorial (Online Resources) is useful for a first contact or a refresher with the programming language.  

<b>Literature Resources</b> 
The course is loosely based on the book [“Neural Data Science : A primer with Matlab and Python”](https://www.amazon.com/Neural-Data-Science-MATLAB%C2%AE-PythonTM/dp/0128040432). As in the course, the book introduces basic concepts of data analysis applied to neuroscience examples and discusses their implementation with Python (and Matlab). 

<b>Online Resources</b>
To get familiar or to recall programming concepts in Python, I recommend to use the W3Schools interactive tutorial with explanations and clarifying examples. The tutorial consists of short chapters introducing all essential basics which will be used in the course. Notably, the interactive web-programming interface allows to write and test python code. 


W3Schools - Python Tutorial : https://www.w3schools.com/python/default.asp


In particular, the following chapters are relevant for the course : 


1. Python Tutorial (https://www.w3schools.com/python/default.asp) <br />
   Python Intro <br />
   ... <br />
   Python Arrays

2. Numpy Tutorial (https://www.w3schools.com/python/numpy/default.asp) <br /> 
NumPy Intro <br />
... <br />
NumPy Array Filter

3. Python Matplotlib (https://www.w3schools.com/python/matplotlib_intro.asp) <br />
Matplotlib Intro <br />
... <br />
Matplotlib Pie Charts

### Competences Acquired

* Learning to program in Python.
* The basic principles of simple and advanced data analysis applied to neural data.
* The construction and implementation of single neuron and neural network simulations.

### What is Expected from You

* Curiosity and desire to learn.
* Active participation and contribution in particular during the tutorials.
* Feedback during the course and contributions to an open dialog to achieve on optimal learning experience.

### Basic Reference for Beginner - Cheat Sheet

This <b>cheat sheet</b> includes the python code we routinely use in the course. It provides a basic reference for beginner. 

![Logo](miscFiles/NeuralDataSciPy_cheat-sheet.png "Cheat Sheet")

It can be downloaded as pdf [here](miscFiles/NeuralDataSciPy_cheat-sheet.pdf).

### Lecture Organization and Material

Each course lasts for 2 hours. It consists of approximately 45 min lecture introducing the general motivation, scientific background and
analysis principles. The lecture is followed by an 1h 10 min long guided tutorial during which the programming/analysis is performed by the students based on a pre-prepared [Jupyter Notebook](https://jupyter.org). Students can follow the teachers tutorial progress in real-time on [Deepnote](https://deepnote.com/project/Neural-Data-Science-with-Python-Tutorial-DteRzlWZSbuTNmXj3nqDVA). Lecture and tutorial are separated by a short 5 min break. 

Most lectures and guided tutorials take place at **9h-11h on Fridays's in room Durkheim (unless otherwise noted in the table below), 2nd floor, access code: C2164, 45 rue des Saints-Pères** between **September 8th and November 25th, 2022**.


**Lecture Overview**

| #                                   | Date                                                         | Title                                                                                                      | Lecturer                                    | Material                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| 1                                   | Thu Sep 8, 14h                                               | Introduction to Python : first steps                                                                       | Michael Graupner                            | [Lecture 1](lectures/L1_Introduction_Python.pdf), [Tutorial 1](tutorials/T01_Python-first-steps.ipynb), See Moodle, [Deepnote link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/%2FT01_Python-first-steps.ipynb)                                                                                                                                                                                    |
| 2                                   | Fri Sep 16, 9h                                               | Time series : basic operations                                                                             | Michael Graupner                            | [Lecture 2](lectures/L2_Time_Series.pdf), [Tutorial 2](tutorials/T02_Time-series.ipynb), [Homework 2](exercises/E02_Time-series.ipynb), [Solutions 2](exercises/E02Solutions_Time-series.ipynb), [Deepnote link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/%2FT02_Time-series-Empty.ipynb)                                                                                                        |
| <span style="color:gray">A</span>   | <span style="color:gray"> Mon Sep 19, 15h45, room Grignard C | <span style="color:gray"> Single-cell RNAseq                                                               | <span style="color:gray"> Frédéric Causeret | <span style="color:gray">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 3                                   | Fri Sep 23, 9h                                               | Wrangling spike trains : basic analysis, raster plot, PSTH, Poisson spike trains                           | Michael Graupner                            | [Lecture 3](lectures/L3_Spike-trains.pdf), [Tutorial 3](tutorials/T03_Spike-trains.ipynb), [Homework 3](exercises/E03_Spike-trains.ipynb), [Solutions 3](exercises/E03Solutions_Spike-trains.ipynb), [Deepnote Link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/%2FT03_Spike-trains-Empty.ipynb)                                                                                                   | 
| <span style="color:gray"> B </span> | <span style="color:gray"> Mon Sep 26, 15h45, room Grignard C | <span style="color:gray"> TD RNAseq 1                                                                      | <span style="color:gray"> Frédéric Causeret | <span style="color:gray">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 4                                   | Fri Sep 30, 9h                                               | Spectral analysis of analog signals : Fourier transform, Spectrogram, Signal Filtering                     | Michael Graupner                            | [Lecture 4](lectures/L4_Analog-signals.pdf), [Tutorial 4](tutorials/T04_Analog-signals.ipynb), [Homework 4](exercises/E04_Analog-signals.ipynb), [Solutions 4](exercises/E04Solutions_Analog-signals.ipynb), [Deepnote Link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/notebook/T04_Analog-signals-Empty-662acfa1652e4f7caef54b251b3c2951)                                                        |
| 5                                   | Fri Oct 7, 9h                                                | Bioinformatics and Systems biology I                                                                       | Karine  Audouze                             | Lecture, Tutorial, Homework, Solutions (see moodle)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |  
| <span style="color:gray"> C </span> | <span style="color:gray"> Mon Oct 10, 15h45, room Grignard C | <span style="color:gray"> TD RNAseq 2                                                                      | <span style="color:gray"> Frédéric Causeret | <span style="color:gray">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 6                                   | Fri Oct 14, 9h15                                             | Bioinformatics and Systems biology II                                                                      | Karine  Audouze                             | Lecture, Tutorial, Homework, Solutions  (see moodle)                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| 7                                   | Fri Oct 28, 9h                                               | Spiking neural network simulations with Brian  | Marcel Stimberg   | [Lecture 7](lectures/L7_Spiking-Neural_Networks.pdf), [Tutorial 7](tutorials/T07_Spiking-networks_commented.ipynb), [Homework 7](exercises/E07_Spiking-Neural_Networks.ipynb), [Solutions 7](exercises/E07Solution_Spiking-Neural_Networks.ipynb), [Deepnote Link](https://deepnote.com/workspace/marcel-stimberg-486e6e20-59ec-4161-b083-f8adeb9a6ccf/project/T07-Neural-Data-Science-with-Python-2022-d5571872-9152-4cc9-9d53-de9346e395be)                                                                                      |
| 8                                   | Fri Nov 4, 9h                                                | Regression analysis : correlation analysis, logisitic regression, nonlinear regression                     | Michael Graupner                            | [Lecture 8](lectures/L8_Regression-analysis.pdf), [Tutorial 8](tutorials/T08_Regression-analysis.ipynb), [Homework 8](exercises/E08_Regression-analysis.ipynb), [Solutions 8](exercises/E08Solutions_Regression-analysis.ipynb), [Deepnote Link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/notebook/T08_Regression-analysis-Empty-a82020247e9648fb829dd12b9149e497)                               |
| 9                                   | Mon Nov 7, 11h, room Grignard F                              | Biophysical modelling of single neurons : integrate-and-fire neuron, introduction to numerical integration | Jonas Ranft                                 | [Lecture 9](lectures/L9_Biophysical-Neuron-Models-LIF.pdf), [Tutorial 9](tutorials/T9_Biophysical-Neuron-Models-LIF_complete.ipynb), [Homework 9](exercises/E9_noisy_LIF.ipynb), [Solutions 9](exercises/E9Solutions_noisy_LIF.ipynb), [Deepnote Link](https://deepnote.com/workspace/j-ranft-8c52a0fa-1cd2-43d1-8f85-98960187fcb1/project/Untitled-project-24c08b9d-1eaf-4919-a326-84f8f99f549f/notebook/T9_Biophysical-Neuron-Models-LIF-8e51d3fc15be41cc826703fc8fd30817)                                                       |
| 10                                  | Mon Nov 7, 14h                                               | Dimensionality reduction : PCA, covariance matrix, factor extraction                                       | Michael Graupner                            | [Lecture 10](lectures/L10_Dimensionality-reduction.pdf), [Tutorial 10](tutorials/T10_Dimensionality-reduction.ipynb), [Free Exercise](exercises/E10_Dimensionality-reduction.ipynb), [Solutions](exercises/E10Solutions_Dimensionality-reduction.ipynb) , [Deepnote Link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/notebook/T10_Dimensionality-reduction-Empty-38ed247742ee42e68458989d5796c29e) |
| 11                                  | Fri Nov 18, 9h                                               | End-of-Course projects presentation; Open Tutorial                                                         | Michael Graupner                            | [Lecture 11](lectures/End-of-Course-Projects.pdf), [Tutorial 11](tutorials/T11_Project-LFP_from_raw_ephys_trace.ipynb), [Homework 10](exercises/E10_Dimensionality-reduction.ipynb), [Solutions 10](exercises/E10Solutions_Dimensionality-reduction.ipynb)                                                                                                                                                                                                                                                                         |
| 12                                  | Fri Nov 25, 9h                                               | Classification and clustering : SVM, KMeans estimate                                                       | Michael Graupner                            | [Lecture 12](lectures/L12_Classification-Clustering.pdf), [Tutorial 12](tutorials/T12_Classification-Clustering.ipynb), [Deepnote Link](https://deepnote.com/workspace/michael-graupner-e9d4435c-f54a-4f14-88e8-811d825c828c/project/Neural-Data-Science-with-Python-Tutorial-0ed791ce-5599-49bb-9336-65e3de7a8354/notebook/T12_Classification-Clustering-Empty-f6aab2c8fc1546d092539cb860dbbdbb)                                                                                                                                  |


### Course Evaluation

**Continuous control (50 % of the final mark) :** The students receive small **homework assignments** which are an extension of the 
in-course tutorial. The subject is related to the last course. The homeworks assignments with the respective Notebook file are posted in the **moodle** of the course. The results have **to be submitted through the moodle by Friday 9am** before the next course (e.g., the assignments of the course on Friday Sep 30th have to be submitted by Friday Oct 7th 9am). Practically, use the provided Jupyter Notebook (see table above or the moodle), add your edits to this file, and submit the modified Jupyter Notebook through the moodle.

Some homework assignments will consist in completing interactive, online assignments on [DataCamp](https://www.datacamp.com/).

**Final exam (50 % of the final mark) :** Students will receive a list of projects they will work on for an extended period of time (about 1.5 months). Projects are small programming projects aimed at independently applying analysis methods acquired during the course. The project can be worked on individually or in teams of two students. More information on the End-of-Course projects and a concrete list of available projects are available [here](EndOfYearProjects.md).

All student work - the weekly homework assignments and the End-of-Course project report - can prepared in English or French, up to the choice of the student. 

### Accessible Computer Rooms and Account

There are three computer rooms available outside the hours of the course. The machines in these rooms feature the same Python installation as in the course and the same home directories (files stored during the course can be accessed 
from these machine) : 
*  Room **Durkheim** : left staircase from the main entrance hall to access lecture halls Delmas or balcon Binet, second floor (access code C2164). There are courses in that room during which it is not accessible.
*  Room **T209 bis** : 2nd floor, in front of Avogadro D, free access 
*  Room **T117** : 1st floor, free access 

You connect to your account on those machines - as well as on the classroom machines - with your university UID as login.  The password is your full student number. It it highly recommended to change the default password, 
which can be done with the command `passwd` in a command line terminal. Please contact [Isabelle Moisenier](mailto:isabelle.moisenier@parisdescartes.fr) 
or [Luc Tamisier](mailto:Luc.Tamisier@parisdescartes.fr) in case of problems with the machines or your account. 


### Identification

M1 S1 Neuro

Code UE : NS0AM020

Acronym : DataSciPython

ECTS : 3

Time volume : 24 hours

### Language of the Course 

The dominant teaching language of the course with be English, while the lecturers provided by Karine Audouze will be in French with slides and material in English. 

### Course Organizers and Teachers  

The course is organized by [Michael Graupner](mailto:michael.graupner@parisdescartes.fr). Lectures will furthermore be taught by [Jonas Ranfts](mailto:jonas.ranft@ens.fr),  [Karine Audouze](mailto:audouze.p7@gmail.com), and  [Marcel Stimberg](mailto:marcel.stimberg@inserm.fr). All questions regarding access to your university account can be addressed to  [Luc Tamisier](mailto:luc.tamisier@parisdescartes.fr) or [Isabelle Moisenier](mailto:isabelle.moisenier@parisdescartes.fr).

Please direct all basic inquiries to [Michael Graupner](mailto:michael.graupner@parisdescartes.fr) by email or pass by his office : 

> Saints-Pères Paris Institute for the Neurosciences <br>
> CNRS UMR 8003, Université de Paris <br>
> bureau : H 358 <br>
> 45 rue des Saints Pères <br>
> 75270 Paris Cedex 06 <br>
> France


**Overview of all Lecturers**

| Picture                                                | Name              | Email                                                                | Address                                                                                                                    | 
|--------------------------------------------------------|-------------------|----------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------| 
| <img src="miscFiles/jonas.jpg" width="100px" />        | Jonas Ranft       | [jonas.ranft@ens.fr](mailto:jonas.ranft@ens.fr)                      | Ecole Normale Supérieure, Institute de Biologie, 46 rue d'Ulm, 75005 Paris                                                 |
| <img src="miscFiles/karine.jpg" width="100px" />       | Karine Audouze    | [audouze.p7@gmail.com](mailto:audouze.p7@gmail.com)                  | Université Paris Cité, Systems Toxicology Group, 45 rue des Saints-Pères, 75006 Paris                                      |
| <img src="miscFiles/marcel.jpg" width="100px" />       | Marcel Stimberg   | [marcel.stimberg@inserm.fr](mailto:marcel.stimberg@inserm.fr)        | Institut de la Vision, Computational Neuroscience of Sensory Systems, 17 rue Moreau, 75012 Paris                           |
| <img src="miscFiles/frederic_cut.jpg" width="100px" /> | Frédéric Causeret | [frederic.causeret@inserm.fr](mailto:frederic.causeret@inserm.fr)    | Institut Imagine, Institut des Maladies Génétique, 24 Boulevard du Montparnasse 75015 Paris |
| <img src="miscFiles/michael_cut.jpg" width="100px" />  | Michael Graupner  | [michael.graupner@u-paris.fr](mailto:michael.graupner@parisdescartes.fr) | Université Paris Cité, SPPIN, 45 rue des Saints-Pères, 75006 Paris                                                         |

### Python Requirements

All course material will run smoothly on the classroom machines, which will have all the required modules installed. 

In case you want to run the course material on your private computer, the following packages are required : 
* Python 3.8 (or the common versions 3.7, 3.8, 3.9)
* numpy
* scipy
* jupyter
* matplotlib 
* pandas
* xlrd 
* biopython
* scikit-learn
* [Brian2](http://briansimulator.org/)

We will set up a Python programming party in the beginning of the academic year for all students who are interested in installing the Python environment required for the class on their laptops. 

Find [here](lectures/PythonInstallation.pdf) the slides with details of the Python installation. 

### External Resources

This class is supported by [<img src="miscFiles/datacamp.png" width="100px" />](https://www.datacamp.com/), an intuitive learning platform for data science and analytics. For education, Datacamp provides courses for free. We have arranged for you to have access to these courses while you are enrolled in the ***Neuroscience Master*** of the Université de Paris.

This class is also supported by [<img src="miscFiles/deepnote.png" width="100px" />](https://deepnote.com/), a new kind of data science notebook : Jupyter-compatible with real-time coding and running in the cloud. The ***Neural Data Science with Python*** class profits from the free education plan of Deepnote. 

### Licence 

See the [LICENSE](LICENSE) file for license rights and limitations (Attribution 4.0 International). 