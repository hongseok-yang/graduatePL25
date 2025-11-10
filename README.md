# CS520 Theory of Programming Languages, Fall 2025, KAIST 

This is a webpage of the course "CS520 Theory of Programming Languages", which is offered at the KAIST CS department in the fall of 2025. The webpage will contain links to course-related materials and announcements.

We change the course completely this year. Instead of following Reynolds's textbook as we did in the past seven years, we will study type theory, in particular, dependent type theory by following Angiuli and Gratzer's book ["Principles of Dependent Type Theory"](https://www.danielgratzer.com/courses/type-theory-s-2024/lecture-notes.pdf). Type theory is the theoretical basis of interactive theorem provers and the advanced type systems of modern programming languages. In particular, dependent type theory  forms the foundation of popular  interactive theorem provers, such as Rocq, Lean and Agda. Understanding this foundation is the goal of the course. 

We remind the students that this is a math-heavy theory course. It is likely that we use category theory a lot, since category theory is closely related to type theory. We assume that students are familiar with basic concepts of programming languages, including those related to their type systems, and also they are fluent in mathematics and have experiences in stating or proving properties using categories.

## 1. Important Announcements

#### [10 November] No lecture on 4 December.

There will not be a lecture on 4 December. We will cover all the course materials by 2 December.

#### [10 November] [Homework2](https://github.com/hongseok-yang/graduatePL25/blob/main/Homework/homework2.pdf) is out.

The homework assignment 2 is out. Submit your solutions in KLMS by 6:00pm on 28 November 2025 (Friday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.


#### [1 October] [Homework1](https://github.com/hongseok-yang/graduatePL25/blob/main/Homework/homework1.pdf) is out.

The homework assignment 1 is out. Submit your solutions in KLMS by 6:00pm on 17 October 2025 (Friday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.

#### [1 September] Q&A and use of a LLM.

We strongly recommend students to ask questions in KLMS, instead of in github, if they have any. This would help fellow students to access those questions and corresponding answers more easily. It would also help TAs and the lecturer not to miss those questions.

We do not permit students to ask homework questions directly to ChatGPT, Gemini, or other LLMs. Doing so would be regarded as the violation of the honour code. However, students can use LLMs to get help for their study, for instance, using CoPilot to solve LaTeX typesetting issues and asking ChatGPT to get an overview of a concept or a technique covered in the course or encountered in your group project. If a student or a project group gets help from LLMs for an assignment, such as a project report, the student or the group should do the following two things:

1. In a submission, the student or the project group should explain how and where LLMs are used.
2. LLMs are well-known to give false information. Ensuring correctness is the responsibility of the student or the project group.

#### [1 September] Policy for handling late submissions.

We will adopt the following scheme for handling late submissions for all types of assignments, including homework assignments. The scheme assumes that the total marks are 100.

1. <= One day late (by the midnight of the next day): -10
2. <= Two days late: -20
3. <= Three days late: -30
4. <= Four days late: -40
5. More than four days late: -100.

#### [1 September] Honour code.

We adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for any assignment, he or she will get F.

We also handle the case of plagiarism strictly. Plagiarism means that students copy texts from other sources in their reports. They shouldn't do it. If students have to use texts from other sources, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of their own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed; if a large part of the report is just a series of rephrases of existing texts, the report won't get good marks. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If a report of a student or a project group is found to plagiarise, the student or everyone in the group will get F. 

## 2. Logistics

#### Evaluation

* Final exam (40%). Group project (40%). Homework (20%). 

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com). Office hour: 6:00pm - 7:00pm on Monday, at 3403 in E3-1.
* TAs: Gyeongwon Jeong (email: jgyw0910@kaist.ac.kr) and Seonghun Park (email: hun57@kaist.ac.kr). Office hour: 4:00pm - 5:00pm on Thursday, at 3419 in E3-1.

#### Time and Place

* Time: 14:30 - 16:00 on Tuesday and Thursday.
* Place: 2445 in E3-1.

## 3. Final Exam

The final exam for this course will happen in our usual classroom on the 18th of December (Thursday) during the final-exam period. Note that the exam starts at 1:00pm.

* Date: 18 December 2025 (Thursday).
* Time: 13:00 - 15:00.
* Place: 2445 in E3.
* Closed-book exam. The scope of the exam is all the topics covered in the classes.

## 4. Group Project

One important part of this course is to form a group of 2-4 students, study an advanced research topic on dependent type theory with fellow students in the group, and present what the group studied if the group is selected for presentation. Here are the detailed instructions on this group project.

1. Form a group.
  * Deadline - 11:59PM on 25 September 2025 (Thursday).
  * Form a group with 2-4 students.
2. Select a topic and write a proposal (5 marks out of 40 marks).
  * Deadline - 11:59PM on 16 October 2025 (Thursday).
  * Pick a paper or papers on dependent type theory that will be studied by your group. The paper or papers should be chosen among the suggested papers in the document by Daniel Gratzer and Lars Birkedal ([link](https://www.danielgratzer.com/courses/type-theory-s-2024/project-description.pdf)).
  * Submit a 1-page proposal in KLMS that contains the title(s) of the selected paper(s), the reasoning for choosing it or them, and the plan to study the paper in depth.
  * The proposal can be submitted by only one member of each team.
3. Write a report (15 marks out of 40 marks).
  * Deadline - 11:59PM on 20 November 2025 (Thursday).
  * Submit a report with at most 4 pages excluding bibliography and figures in KLMS.
  * The report can be submitted by only one member of each team.
  * The report should explain not just the topic studied by your group but also how the group studied the topic. The latter can be about how the group members studied the topic together, which questions they asked in order to understand the topic in depth, which other papers they studied, which existing implementations or mechanised proofs they looked at if there are any such, and how each member of the group contributed to the study, etc.
  * We encourage the students to go beyond a simple summary of the topic, and to have their own thoughts on the topic in the form of mathematical or experimental analyses. 
4. Submit the slides of a presentation on the studied topic (15 marks out of 40 marks).
  * Deadline - 11:59PM on 27 November 2024 (Thursday).
  * Prepare the slides for a 35-minute talk on the studied topic, and submit them in KLMS.
  * The slides can be submitted by only one member of each team.
  * The slides should be in the pdf format.
5. Present your study if your group project is chosen (5 marks out of 40 marks).
  * Four projects will be selected based on the votes by the students, TAs, and the lecturer.
  * Two projects will be presented on 9 December 2025 (Tuesday), and the other two will be presented on 11 December 2025 (Thursday).
6. Warning on plagiarism.
  * Students should not copy texts from other sources in their reports. If students have to use such texts, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of the students' own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If any of the reports of a group is found to plagiarise, everyone in the group will get F.

## 5. Homework

Submit your solutions in KLMS. We will create submission folders for all the homework assignments in KLMS.

* [Homework1](https://github.com/hongseok-yang/graduatePL25/blob/main/Homework/homework1.pdf) - Deadline: 6:00pm on 17 October 2025 (Friday).
* [Homework2](https://github.com/hongseok-yang/graduatePL25/blob/main/Homework/homework2.pdf) - Deadline: 6:00pm on 28 November 2025 (Friday).

## 6. Tentative Plan

* 09/02(Tue) - Introduction (Ch1).
* 09/04(Thu) - Extensional Type Theory (Ch2).
* 09/09(Tue) - Extensional Type Theory (Ch2).
* 09/11(Thu) - Extensional Type Theory (Ch2).
* 09/16(Tue) - Extensional Type Theory (Ch2).
* 09/18(Thu) - Extensional Type Theory (Ch2).
* 09/23(Tue) - Extensional Type Theory (Ch2).
* 09/25(Thu) - Extensional Type Theory (Ch2).
* 09/30(Tue) - Extensional Type Theory (Ch2).
* 10/02(Thu) - Extensional Type Theory (Ch2).
* 10/07(Tue) - __NO LECTURE. National Holiday.__
* 10/09(Thu) - __NO LECTURE. National Holiday.__
* 10/14(Tue) - Extensional Type Theory (Ch2).
* 10/16(Thu) - Extensional Type Theory (Ch2).
* 10/21(Tue) - __NO LECTURES. Week for Mid-term Exams.__
* 10/23(Thu) - __NO LECTURES. Week for Mid-term Exams.__
* 10/28(Tue) - Extensional Type Theory (Ch2).
* 10/30(Thu) - Extensional Type Theory (Ch2).
* 11/04(Tue) - Metatheory and Implementation (Ch3).
* 11/06(Thu) - Metatheory and Implementation (Ch3).
* 11/11(Tue) - Metatheory and Implementation (Ch3).
* 11/13(Thu) - Metatheory and Implementation (Ch3).
* 11/18(Tue) - Intensional Type Theory (Ch4).
* 11/20(Thu) - Intensional Type Theory (Ch4).
* 11/25(Tue) - Intensional Type Theory (Ch4).
* 11/27(Thu) - __NO LECTURE. Interview for Undergraduate Admission.__
* 12/02(Tue) - Intensional Type Theory (Ch4).
* 12/04(Thu) - __NO LECTURE.__
* 12/09(Tue) - Project Presentations.
* 12/11(Thu) - Project Presentations.
* 12/16(Tue) - __NO LECTURE. Week for Final Exams.__
* 12/18(Thu) - __FINAL EXAM (1:00pm - 3:00pm, 2445 E3).__

## 7. Study Materials

We will follow the book by Carlo Angiuli and Daniel Gratzer.

* [Principles of Dependent Type Theory](https://www.danielgratzer.com/courses/type-theory-s-2024/lecture-notes.pdf), Carlo Angiuli and Daniel Gratzer, 2025. To be published by Cambridge University Press.

The authors of the book taught courses on dependent type theory based on the book.

* [Link](https://www.danielgratzer.com/courses/type-theory-s-2024/) to the course by Birkedal and Gratzer.
* [Link](https://carloangiuli.com/courses/b619-sp24/index.html) to the course by Angiuli.
