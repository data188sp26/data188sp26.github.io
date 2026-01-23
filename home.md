---
layout: page
title: Welcome to Data 188!
nav_exclude: true
permalink: /
seo:
  type: Course
  name: Data 188 Spring 2026
---
# Main Page

{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This is the course website for Data 188, "Introduction to Deep Learning", Spring 2026, UC Berkeley.

## Course Description

From the [UC Berkeley course catalog](https://classes.berkeley.edu/content/2026-spring-data-188-001-sem-001):

This course is an introduction to deep learning (also known as "deep neural networks"), and will cover the fundamental techniques that power deep learning algorithms, as well as exploring the intuitions and various "rules of thumb" behind successful deep learning methods. Topics include: neural network architectures, backpropagation, convolutional neural networks, sequence models (such as the transformer model), applications to computer vision and natural language processing, and more.

**Important:** In this course, we will use Edstem to post announcements and important information.

**It is the student's responsibility to actively monitor the Ed for any important announcements.**

**Useful course links:**
- bCourse: [link](https://bcourses.berkeley.edu/courses/1551684)
- Ed: [link](https://edstem.org/us/courses/91872/discussion)
- Gradescope: [link](https://www.gradescope.com/courses/1217889)
- Lecture Zoom link (TuTh 3:30pm - 5:00pm): [link](https://berkeley.zoom.us/j/98594186696)

**Note**: lecture starts during Week 01 (2026-01-20).
Discussion section and office hours will not start until Week 02 (2026-01-26).

## Textbooks
We will be using the following textbooks, all fortunately freely available online:
<ul>
<li>"Deep Learning: Foundations & Concepts" by Christopher Bishop & Hugh Bishop.
The free-to-use online version is at <a href="https://www.bishopbook.com/">Bishop Book</a>. Further, UC Berkeley students can access the PDF version via this link (CalNet login required): <a href="https://link-springer-com.libproxy.berkeley.edu/book/10.1007/978-3-031-45468-4">PDF</a>.
  </li>
  <li> "Deep Learning" by Ian Goodfellow and Yoshua Bengio and Aaron Courville. Free online link is <a href="https://www.deeplearningbook.org/">here</a>.
  </li>
  <li>
    (optional) Dive into Deep Learning <a href="https://d2l.ai/">D2LAI</a> is an excellent interactive online textbook and set of resources for Deep Learning ! (a PDF version of the entire book is also available online)
  </li>
</ul>

## Lectures
Lectures are Tuesdays and Thursdays, 3:30PM - 5PM, online via Zoom.
Lecture slides are provided via this website, and lecture videos are
provided via the bCourses ["Media Gallery"](https://bcourses.berkeley.edu/courses/1551684/external_tools/90481).

<!-- This Ed post ["Lecture Schedule"](https://TODO/add/link) contains more info about the lecture schedule, including: Zoom lecture links. -->

<!-- Here is an **optional weekly reading list** of supplemental material: [link](https://docs.google.com/document/d/1asBPDgxrI47hiQ2rjGBmdAXLWv02kopqDgcE4yyW718/edit).
While this is not required for the course, we believe that the material here can enhance understanding of the course and, more broadly, gain further exposure to the DNN field. -->

### Lecture Slides
Regarding reading:
The provided reading links are optional and are provided for students interested in additional resources.
The content in the reading will not always be "fair game" for exams: if something isn't covered in lecture/discussion/assignments, then it won't be in scope for exams.
The Bishop textbook doesn't always cleanly map to our lectures, but I've done my best to line things up.
Note that the Bishop textbook sometimes takes a different approach to concepts (eg Bishop is sometimes relatively probability-heavy) that we won't always follow in our course.

- Lecture 01 [Week 1, 2026-01-20] <a href="assets/lecture_slides/01_intro.pdf">Introduction</a>
  - Reading: (Bishop) Ch1.1
- Lecture 02 [Week 1, 2026-01-22] <a href="assets/lecture_slides/02_softmax_regression.pdf">ML Refresher, Softmax Regression</a>
  - Reading: (Bishop) Ch 1.2, Ch 5.4.4, Ch 7.2
- Lecture 03 [Week 2, 2026-01-27] Manual Neural Networks
  - Reading: (Bishop) Ch 1.2, Ch 1.3, Ch 4.1, Ch. 6.2, 6.3, 6.4
- Lecture 04 [Week 2, 2026-01-29] Automatic Differentiation
  - Reading: (Bishop) Ch 8.1, 8.2
- Lecture 05 [Week 3, 2026-02-03] Optimization

<!-- <li>Lecture 01 [Week 1, 2024/08/29] <a href="assets/lecture_slides/data182_Lecture1_Introduction.pdf">Introduction</a> </li>
  <ul>
 <li> Bishop Book: Chapter 1 </li>
  </ul>
<li>Lecture 02 [Week 2, 2024/09/03] <a href="assets/lecture_slides/data182_Lecture2_MLReview_1.pdf"> ML Review Part 1 </a> </li>
 <ul>
  <li>Bishop Book: Chapter 2 </li>
 <li>Reading:  <a href="assets/readings/NLL.pdf"> Binary classification & logistic regression </a> </li>
 </ul>
<li> Lecture 03 [Week 2, 2024/09/05] <a href="assets/lecture_slides/data182_Lecture03_MLReview_2.pdf"> ML Review Part 2</a> </li>
<li> Lecture 04 [Week 3, 2024/09/10] <a href="assets/lecture_slides/data182_Lecture04_Neural_Networks.pdf">Neural Networks</a> </li>
<li>Lecture 05 [Week 3, 2024/09/12] <a href="assets/lecture_slides/data182_Lecture5_Optimization.pdf"> Optimization </a> </li>
 <ul>
  <li>Bishop Book: Chapter 7 </li>
 </ul>
<li> Lecture 06 [Week 4, 2024/09/17] <a href="assets/lecture_slides/data182_Lecture06_Building_Blocks.pdf">Building Blocks</a>
    <ul>
    <li>Python demo code:
<a href="assets/lecture_slides/python/lecture06/tensor_demo.py">[tensor_demo.py]</a>
<a href="assets/lecture_slides/python/lecture06/two_layer_linear_nn_demo.py">[two_layer_linear_nn_demo.py]</a>
<a href="assets/lecture_slides/python/lecture06/normalization_motivation.py">[normalization_motivation.py]</a>
<a href="assets/lecture_slides/python/lecture06/batch_norm_demo.py">[batch_norm_demo.py]</a>
<a href="assets/lecture_slides/python/lecture06/layer_norm_demo.py">[layer_norm_demo.py]</a>
<a href="assets/lecture_slides/python/lecture06/two_layer_nn_bells_and_whistles.py">[two_layer_nn_bells_and_whistles.py]</a>
    </li>
    </ul>
</li>
  <li>Lecture 07 [Week 4, 2024/09/19] <a href="assets/lecture_slides/data182_Lecture7_ConvolutionalNetworks.pdf"> Convolutional Neural Networks ("ConvNets") </a> </li>
 <ul>
  <li>Bishop Book: Chapter 10 </li>
 </ul>
<li> Lecture 08 [Week 5, 2024/09/24] <a href="assets/lecture_slides/data182_Lecture08_Backprop_Part2.pdf">Backprop Part 2</a> </li>
<li> Lecture 09 [Week 5, 2024/09/26] <a href="assets/lecture_slides/data182_Lecture9_RNNs.pdf"> Recurrent Neural Networks ("RNNs") </a> </li>
<li> Lecture 10 [Week 06, 2024/10/01] <a href="assets/lecture_slides/data182_Lecture10_Computer_Vision.pdf"> Computer Vision </a> </li>
<li> Lecture 11 [Week 06, 2024/10/03] <a href="assets/lecture_slides/data182_Lecture11_Transformers1.pdf"> Transformers - Part 1 </a> </li>
<li> Lecture 12 [Week 07, 2024/10/08] <a href="assets/lecture_slides/data182_Lecture12_Transformers_Part2.pdf"> Transformers - Part 2 </a> </li>
<li> Lecture 13 [Week 07, 2024/10/10] <a href="assets/lecture_slides/data182_Lecture13_Transformers3.pdf"> Transformers - Part 3 </a> </li>
  <ul>
<li>
  <a href="assets/notebooks/Transformers 3.ipynb">Transformers Notebook (Attention, Decoder-Encoder)</a>
</li>
  </ul>
<li> Lecture 14 [Week 08, 2024/10/15] <a href="assets/lecture_slides/data182_Lecture14_Transformers_Part4.pdf"> Transformers - Part 4 </a> </li>
<li> Lecture 15 [Week 08, 2024/10/17] <a href="assets/lecture_slides/data182_Lecture15_MTReview.pdf">  MidTerm Review </a> </li>
<li> Lecture N/A [Week 09, 2024/10/22] MidTerm </li>
<li> Lecture N/A [Week 09, 2024/10/24] No lecture </li>
<li> Lecture N/A [Week 10, 2024/10/29] No lecture </li>
<li> Lecture 16 [Week 10, 2024/10/31] <a href="assets/lecture_slides/data182_Lecture16_NLP.pdf"> NLP: Pretraining </a> </li>
  <ul>
<li>
  <a href="assets/notebooks/Pretraining_word2vec.ipynb">Pretraining word2vec</a>
</li>
    </ul>
<li> Lecture 17 [Week 11, 2024/11/05] <a href="assets/lecture_slides/data182_Lecture17_VisualTransformer_MAE.pdf"> Visual Transformer, Masked Autoencoder</a> </li>

<li> Lecture 18 [Week 10, 2024/10/31] <a href="assets/lecture_slides/data182_Lecture18_NLP_BERTandGPT.pdf"> NLP Pretraining: Deeply Encoded Representations </a> </li>
  <ul>
<li>
  <a href="assets/readings/GPT.pdf">GPT (Radford et al 2018)</a>
</li>
    <li>
  <a href="assets/readings/BERT.pdf">GPT (Devlin et al 2019) </a>
</li>
    <li>
  <a href="assets/readings/InstructGPT.pdf">InstructGPT (Ouyang et al 2022)</a>
</li>
    </ul>
<li> Lecture 19 [Week 12, 2024/11/12] <a href="assets/lecture_slides/data182_Lecture19_GPU_training.pdf"> Accelerating and scaling DNN training (GPU) </a> </li>
<ul>
    <li> Guest Talk. Speaker: William Chen (TA), <a href="assets/lecture_slides/data182_Lecture19_guest_talk_william_chen_robotics_deep_learning.pdf"> Robotics and DL </a> </li>
</ul>

<li> Lecture 20 [Week 12, 2024/11/14] <a href="assets/lecture_slides/data182_Lecture20_FinalProject.pdf"> Final Project: Overview and Context </a> </li>
<ul>
    <li> <a href="assets/readings/Ashish-CIS.pdf">Assessing Software Fault Risk with Machine Learning</a></li>
</ul>

<li> Lecture 21 [Week 13, 2024/11/19] <a href="assets/lecture_slides/data182_Lecture21_Retrieval_Systems.pdf"> Recommendation Systems </a> </li>
<li> Lecture 22 [Week 13, 2024/11/21] Guest Talk. Speaker: Yuxi Liu (TA), <a href="assets/lecture_slides/data182_Lecture22_Neural_Networks_1900-1990.pdf"> Neural Networks: 1900 - 1990 </a> </li>
<li> Lecture 23 [Week 14, 2024/11/26] Guest Talk. Speaker: Jinjian Liu (Tutor), <a href="assets/lecture_slides/data182_Lecture23_Repository_to_Environment.pdf">Repository to Environment </a></li>
<li> Lecture N/A [Week 14, 2024/11/28] No lecture (Thanksgiving holiday) </li>
<li> Lecture 24 [Week 15, 2024/12/03] Speaker: Eric Kim, <a href="assets/lecture_slides/data182_Lecture24_Closing_Lecture_Pt1.pdf">Closing Lecture (1/2)</a></li>
<li> Lecture 25 [Week 15, 2024/12/05] Principled structures in deep learning-based autoregressive modeling of high-dimensional multi-scale chaotic dynamical systems. Guest Lecture on Deep Learning for Climate Modeling by Prof Ashesh Chattopadhyay of UCSC </li>
</ul> -->

## Discussion Sections
You can attend any discussion section you like.
However, if there are less crowded sections that fit your schedule, those offer more opportunities for you to interact with your TA.
See this [calendar](calendar/) to view the available discussion section times and locations.

### Section Notes

Discussion 01 (Week 2): TODO

<!-- - Discussion 01 (Week 3): [Section Notes](/assets/section_notes/week03.pdf), [Solution](/assets/section_notes/week03_solution.pdf)

- Discussion 02 (Week 4): [Section Notes](/assets/section_notes/week04.pdf), [Solution](/assets/section_notes/week04_solution.pdf)

- Discussion 03 (Week 5): [Section Notes](/assets/section_notes/week05.pdf), [Solution](/assets/section_notes/week05_solution.pdf). [Notebook](/assets/section_notes/DataC182_DiscussionWorksheet_3.ipynb). Open notebook on [Google Colab](https://colab.research.google.com/github/datac182fa24/datac182fa24.github.io/blob/main/assets/section_notes/DataC182_DiscussionWorksheet_3.ipynb)

- Discussion 04 (Week 6): [Section Notes](/assets/section_notes/week06.pdf), [Solution](/assets/section_notes/week06_solution.pdf)

- Discussion 05 (Week 7): [Section Notes](/assets/section_notes/week07.pdf), [Solution](/assets/section_notes/week07_solution.pdf)

- Discussion 06 (Week 8): [Section Notes](/assets/section_notes/week08.pdf), [Solution](/assets/section_notes/week08_solution.pdf)

- Discussion 07 (Week 9): [Section Notes](/assets/section_notes/week09.pdf), [Solution](/assets/section_notes/week09_solution.pdf)

[//]: # (- Discussion 7: [Section Notes]&#40;/assets/section_notes/week7.pdf&#41;, [Solution]&#40;/assets/section_notes/week7_solution.pdf&#41;)

- Discussion 08 (Week 11): [Section Notes](/assets/section_notes/week11.pdf), [Solution](/assets/section_notes/week11_solution.pdf)

- Discussion 09 (Week 12): [Section Notes](/assets/section_notes/week12.pdf), [Solution](/assets/section_notes/week12_solution.pdf)

- Discussion 10 (Week 13): [Section Notes](/assets/section_notes/week13.pdf), [Solution](/assets/section_notes/week13_solution.pdf) -->

## Homeworks
All homeworks are graded for accuracy.
See the course syllabus for more info about homework policy.
For assignment due dates, see Gradescope.

**Tip**: For Colab notebooks, it's recommended to save your own copy of the notebook by doing "File -> Save a copy in Drive" before running any cells.

* (optional) [Python Colab Tutorial](https://colab.research.google.com/github/data-188-berkeley/hw0/blob/main/colab_tutorial.ipynb).

* [Homework 0](https://colab.research.google.com/github/data-188-berkeley/hw0/blob/main/hw0.ipynb): ML warmup, softmax classification.

<!-- - [Homework 1](https://github.com/datac182fa24/datac182_hw1_student), **due Tues Oct 8th 2024 11:59 PM PST**

- [Homework 2](/assets/homeworks/DataC182_FA24_HW2-2.pdf), **due Sun Oct 27th 2024 11:59 PM PST**

- [Homework 3](https://github.com/datac182fa24/datac182_hw3_student), **due Fri Nov 22nd 2024 11:59 PM PST**

- [Homework 4](https://github.com/datac182fa24/datac182_hw4_student), **due Sun Dec 15th 2024 11:59 PM PST**

- [Final Project](https://docs.google.com/document/d/1erKfrMXIY_JkPB_648wyaTXP89Llo4MyD68l_pZRwZo/edit?tab=t.0), **due Fri Dec 20th 2024 11:59 PM PST** -->
