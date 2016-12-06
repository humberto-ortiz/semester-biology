---
layout: page
title: Syllabus
catalog: MATH 6685
credits: 3
semester: Spring 2017
professor: Dr. Humberto Ortiz-Zuazaga
office: NCL A-159
email: humberto.ortiz@upr.edu
phone: 787-764-0000 x88363
schedule: ['Monday and Wednesday, 1:00-2:20PM, CNL A-141']
office_hours: Thursdays 3-4 pm, or by appointment
---

## {{ site.title }} 

{{ page.catalog }}, {{ page.credits }} Credits, {{ page.semester }}

### Professor

{{ page.professor }}

Office: {{ page.office }}

Email (best way to contact me):
[{{ page.email }}](mailto:{{ page.email }})

Phone: {{ page.phone }}


### Times & Location

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Office Hours

Times: {{ page.office_hours }}

Location: {{ page.office }}

*Note: my schedule gets very busy during the semester so please try to schedule
appointments as far in advance as possible. In general it will be very difficult
to set up appointments less than 24 hours in advance.*


### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/).
Changes to the schedule will be posted to this site so please try to check it
periodically for updates.


### Course Communications

Email: [{{ page.email }}](mailto:{{ page.email }})


### Required Texts

There is no required text book for this class.


### Course Description
 
Computers are increasingly essential to the study of all aspects of
biology. Data management skills are needed for entering data without errors,
storing it in a usable way, and extracting key aspects of the data for
analysis. Basic programming is required for everything from accessing and
managing data, to statistical analysis, to modeling. This course will provide an
introduction to data management, manipulation, and analysis, with an emphasis on
biological problems. Class will typically consist of short introductions or
question & answer sessions, followed by hands on computing exercises. The course
will be taught using R and SQLite, but the concepts learned will easily apply to
all programming languages and database management systems. No background in
programming of databases is required.


### Prerequisite Knowledge and Skills

Knowledge of basic biology.


### Purpose of Course

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting biological research. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs, text files, and
databases. By learning how to get the computer to do your work for you, you will
be able to do more science faster.


### Course Goals and Objectives

Students completing this course will be able to:

* Create well structured databases
* Extract information from databases
* Write simple computer programs in R
* Automate data analysis
* Apply these tools to address biological questions
* Apply general data management and analysis concepts to other programming
  languages and database management systems


### How this course relates to the Student Learning Outcomes in ???

FIXME

This course contributes to the 'Quantitative Skills' and 'Conducting and
Analyzing Independent/Original Research' Student Learning Outcomes specified in
the
[Ph.D. and MS in Wildlife Ecology and Conservation Academic Assessment Plans](http://assessment.aa.ufl.edu/Data/Sites/22/media/2013-14gaap/cals/2013-14-cals-wildlife-ecol-and-consvn-phd-aap.pdf),
by providing students the skills and knowledge they need to manage and analyze
the data used in research.


### Teaching Philosophy

This class is taught using a flipped, learner-centered, approach, because
learning to program and work with data requires actively working on
computers. Flipped classes work well for all kinds of content, but I think they
work particularly well for computer oriented classes. If you're interested in
knowing more take a look at this great
[info-graphic](http://www.knewton.com/flipped-classroom-2/).


### Instructional Methods

As a flipped classroom, students are provided with either reading or video
material that they are expected to view/read prior to class. Classes will
involve brief refreshers on new concepts followed by working on exercises in
class that cover that concept. While students are working on exercises the
instructor will actively engage with students to help them understand material
they find confusing, explain misunderstandings and help identify mistakes that
are preventing students from completing the exercises, and discuss novel
applications and alternative approaches to the data analysis challenges students
are attempting to solve. For more challenging topics class may start with 20-30
minute demonstrations on the concepts followed by time to work on exercises.


## Course Policies


### Attendance Policy

Attendance will not be taken or factor into the grades for this class. However,
experience suggests that students who regularly miss class struggle to learn the
material.


### Quiz/Exam Policy

There are no quizzes or exams in this course.


### Make-up policy

Late assignments will be docked 20% and will not be accepted more than 48 hours
late except in cases of genuine emergencies that can be documented by the
student or in cases where this has been discussed and approved in advance. This
policy is based on the idea that in order to learn how to use computers well,
students should be working with them at multiple times each week. Time has been
allotted in class for working on assignments and students are expected to work
on them outside of class. It is intended that you should have finished as much
of the assignment as you can based on what we have covered in class by the
following class period. Therefore, even if something unexpected happens at the
last minute you should already be close to done with the assignment. This policy
also allows rapid feedback to be provided to students by returning assignments
quickly.


### Assignment policy

Assignments are due Monday night by 11:55 pm Eastern Time. Assignments should be
submitted via Moodle.


### Course Technology

Students are required to provide their own laptops and to install free and open
source software on those laptops (see [Setup]({{ site.baseurl }}/computer-setup)
for installation instructions). Support will be provided by the instructor in
the installation of required software. If you don't have access to a laptop
please contact the instructor and they will do their best to provide you with
one.


## UPR Policies


### University Policy on Accommodating Students with Disabilities

Students with disabilities properly registered with the Office of
Affairs for Persons with Disabilities <a
href="http://estudiantes.uprrp.edu/impedimentos/impedimentos.php">Oficina
de Asuntos para la Persona con Impedimento (O.A.P.I.)</a> should
notify the professor at the start of the semester. The professor will
make reasonable accommodations to support the student, in consultation
with OAPI.

### Academic integrity

> The University of Puerto Rico promotes the highest standards of
> academic and scientific integrity. Article 6.2 of the UPR Student
> Bylaws (Certification JS 13 2009–2010) states that “academic
> dishonesty includes but is not limited to: fraudulent actions,
> obtaining grades or academic degrees using false or fraudulent
> simulations, copying totally or partially academic work from another
> person, plagiarizing totally or partially the work of another
> person, copying totally or partially responses from another person
> to examination questions, making another person to take any test,
> oral or written examination on his/hers behalf, as well as assisting
> or facilitating any person to incur in the aforementioned
> conduct”. Fraudulent conduct refers to “behavior with the intent to
> defraud, including but not limited to, malicious alteration or
> falsification of grades, records, identification cards or other
> official documents of the UPR or any other institution.” Any of
> these actions shall be subject to disciplinary sanctions in
> accordance with the disciplinary procedure, as stated in the
> existing UPR Student Bylaws.

DISCLAIMER: The above statement is an English translation, prepared at
the Deanship of Academic Affairs of the Medical Sciences Campus, of
certain parts of Article 6.2 of the UPR Student Bylaws “Reglamento
General de Estudiantes de la Universidad de Puerto Rico”,
(Certificación JS 13 2009-2010). It is in no way intended to be a
legal substitute for the original document, written in Spanish.


### Netiquette and Communication Courtesy

All members of the class are expected to follow rules of common
courtesy in all email messages, threaded discussions and chats.


## Getting Help

For issues with technical difficulties for E-learning in Moodle, please contact the DTAA Help Desk at:

* http://helpdesk.uprrp.edu:9675/portal

Any requests for make-ups due to technical issues MUST be accompanied by the
ticket number received from DTAA when the problem was reported to them. The
ticket number will document the time and date of the problem. You MUST e-mail
your instructor within 24 hours of the technical difficulty if you wish to
request a make-up.

Most importantly, if you are struggling for any reason please come talk to me
and I will do my best to help.


## Grading Policies

Grading for this course will revolve around a combination of assignments (75%)
and an independent project (25%).

There will be 11 equally weighted assignments. One problem from each assignment
(selected at the instructors discretion after the assignments have been
submitted) will receive a thorough code review and a detailed grade. Other
problems will be graded as follows:

* Produces the correct answer using the requested approach: 100%
* Generally uses the right approach, but a minor mistake results in an incorrect
    answer: 90%
* Attempts to solve the problem and makes some progress using the core concept:
    50%
* Answer demonstrates a lack of understanding of the core concept: 0%

Independent projects may focus on databases, programming, or a combination or
the two.

### Grading scale

- **A 90-100**
- **B 80-89**
- **C 70-79**
- **D 60-69**
- **F <60**


## Course Schedule

The details course schedule is available on the course website at:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).


**Disclaimer:** This syllabus represents my current plans and objectives. As we
go through the semester, those plans may need to change to enhance the class
learning opportunity. Such changes, communicated clearly, are not unusual and
should be expected.
