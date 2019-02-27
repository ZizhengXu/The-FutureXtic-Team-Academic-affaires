# The-FutureXtic-Team-Academic-affaires

It’s the year 2027, and you are a professor at the FutureXtic University, the first fully-online,degree-granting institution that has managed to rival the likes of Harvard and MIT. You havejoined the Statistical Inference Division and are in charge of teaching Decision Theory. Unfor-tunately – or fortunately – given its business model, the university is quite “overcrowded” andeach semester there are close to10,000FutureXtic students that take Decision Theory.Given the size of your class, and a disturbing lack of teaching assistants, you are forced tolimit the number of questions given to each student on the mid-term exam to only five multiplechoice questions. To further complicate matters the department head has mandated that all testquestions be pulled from a bank of approximately400“approved” test questions. To increasethe robustness and ease of creation of your midterm exam you decide to randomly and uniformlychoose5questions from the question bank for each student. This means that each student’s examconsists of disjoint, intersecting, or identical sets of5questions. To assist you with running sucha large class, the university has provided you with last year’s student performance data (wherethe professor created exams using a process similar to your own). Additionally, the departmenthead has admitted to you that she thinks that not all the questions in the “approved” questionbank are actually useful for evaluating each student’s relative understanding of Decision Theory.She also warns you that while it is OK not to use all the questions from the bank, you must, atminimum, use75% of them in order to achieve sufficient coverage of the curriculum.With the mid-term exam only a few days away, which questions should you exclude from theexam generation algorithm such that the exam results will provide the most meaningful evalua-tion of the students in the class? Why? Please explain both your reasoning and methodology.The data set –inclassprob2_traning_data.csvunderFiles/Dataon Canvas – you aregiven by the department has one record per line, where each record consists of:

1. A unique identifier for a question.

2. A unique identifier for a student.

3. The correctness of a student’s response. 

A correct answer is marked as a 1; an incorrectresponse is marked as a 0.

