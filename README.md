# Research_Project
## Applying ML techniques in Engineering Education
## Cheating detection in Semester exams

## Abstract

The spread of COVID-19 poses a threat to humanity because it has caused numerous international activities to close, especially educational ones, to be suspended. Education institutions have been compelled to transition to e-learning in order to stop the virus's spread.
E-learning is the name given to the formal educational system that uses electronic resources. Despite the difficulties and data that suggests that students are less likely to benefit from this kind of education, e-learning is the best option currently available to ensure that diseases do not spread since it guarantees geographical distance.
However, there are a number of problems to e-learning, the most significant of which being that academic dishonesty in higher education occurs frequently and is by no means a recent development during online final exams. Technology, according to Carnevale [18], is "giving students new and faster techniques to cheat" (para.1). Based on the findings of a study conducted by King, Guyette Jr., and Piotrowski [19] on business students' attitudes and behaviours towards cheating on an online exam, 73.6% of the respondents believed that doing so was simple. Moreover, learning primarily on a theoretical level, applying all students have learned without using practical skills, and cheating on exams since students lack the necessary skills and don’t have any proper practice.
In this paper, our objective is to spot instances of exam cheating using post-exam scoring analysis to identify anomalous results. Our method's new application of machine learning techniques to detect the exam's abnormal grades is what makes it significant.
So, in order to enhance online education, we have come up with some solutions using machine learning algorithms.

## Introduction

Academic dishonesty is pervasive and by no means a recent occurrence during online final exams in higher education. Technology, according to Carnevale [18], is "giving learners new and faster means to cheat" (para.1). In accordance with the results of a study conducted by King, Guyette Jr., and Piotrowski [19] on business students' attitudes and behaviours towards trying to cheat on an online exam, 73.6% of the respondents were of the view that doing so was simple.
Exam irregularities can be found by evaluating students' scores on the continuous assessment with their scores on the final exam. An average student's sudden and surprisingly high final exam grades could cause a few questions, warning lights, and be viewed as unusual. But things are not always as simple as they appear to be. Any fault would be less obvious if the final exam is comparatively easy and the majority of students obtain high grades. Additionally, it's critical to remember that the order of the scores matters and that the course assessments are consecutive.
Quizzes, midterm exams, and final exams are used as the algorithm's inputs, and its output is a list of labels, one for each student, indicating whether or not they have cheated.

## #PROPOSED ALGORITHM-

•	using a network to estimate the final exam score based on the results of the preceding exams. Scores on quizzes, midterm exams, projects, and other pre-final exam examinations are some of the input variables in our model. The final exam's score is the model's output. The model is trained to reduce the predictions' mean squared error.

1.	Using the provided dataset, train a regression model.
a)	The input characteristics (X) are the results from quizzes, midterm exams, projects, and other assessments taken before the final exam.
b)	 The final exam score is the output (y).    

   
       2.  Calculate the error between the scores predicted by the trained model and the  
            actual exam scores. Apply a detection method on the set of errors to 
            determine the abnormal scores.
## Methodology


•	The algorithm's inputs are a class's series of grades from quizzes, midterms, and   finals; its output is a list of labels, one for each student, indicating whether or not that student cheated.

•	First, a linear neural network model is trained to forecast the results of the final exam based on the results of the earlier assessments.

•	After that, an outlier detection model is used to spot situations where the discrepancy between the actual and anticipated final exam scores is odd.

•	Projects, term examinations, final exams, and quizzes are all taken in order. Information that is crucial is contained in the assessments' order. In contrast to the scores 50, 61, 70, 79, 90, and 95, the scores 79, 90, 70, 61, and 50 offer distinct information.

•	While the second score sequence is odd, the previous score sequence is regular. We determine whether the student has cheated on the exam by identifying the abnormality based on the projected values of the external marks




### References 

1.	Kamalov F, Sulieman H, Santandreu Calonge D (2021) Machine learning based approach to exam cheating detection. PLoS ONE 16(8): e0254340. https://doi.org/10.1371/journal.pone.0254340

2.	J. Sinclair and S. Kalvala, "Student engagement in massive
open online courses", Int. J. Learn. Technol., vol. 11, no. 3, pp. 218-237, 2016.
https://dl.acm.org/doi/abs/10.1504/IJLT.2016.079035
      
3.	Latham, A., Crockett, K., McLean, D., Edmonds, B.: A conversational intelligent tutoring system to automatically predict learning styles. Computers & Education 59(1), 95–109 (2012)
https://www.researchgate.net/publication/224807038_A_Conversational_Intelligent_Tutoring_System_to_Automatically_Predict_Learning_Styles

4.	Application of Deep Learning on Student Engagement in e-learning environments
https://doi.org/10.1016/j.compeleceng.2021.107277

