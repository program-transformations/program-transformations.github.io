# News
- Decisions are available on [OpenReview](https://openreview.net/group?id=NeurIPS.cc/2019/Workshop/Program_Transformations).
- The schedule is available [here](#schedule) and on the [official site](https://neurips.cc/Conferences/2019/Schedule?showEvent=13188).
- The workshop will take place on **Saturday, Dec. 14th**, West Level 1, **Room 114+115**.

# Summary
Machine learning researchers often express complex models as a program, relying on program transformations to add functionality. New languages and transformations (e.g., TorchScript and TensorFlow AutoGraph) are becoming core capabilities of ML libraries. However, existing transformations, such as **automatic differentiation (AD or autodiff)**, inference in **probabilistic programming languages (PPLs)**, and optimizing compilers are often built in isolation, and limited in scope. This workshop aims at viewing program transformations in ML in a unified light, making these capabilities more accessible, and building entirely new ones.

Program transformations are an area of active study. AD transforms a program performing numerical computation into one computing the gradient of those computations. In probabilistic programming, a program describing a sampling procedure can be modified to perform inference on model parameters given observations. Other examples are vectorizing a program expressed on one data point, and learned transformations where ML models use programs as inputs or outputs.

This workshop will bring together researchers in the fields of **AD, probabilistic programming, programming languages, compilers, and ML**, with the goal of understanding the commonalities between disparate approaches and views, and sharing ways to make these techniques broadly available. It would enable ML practitioners to iterate faster on novel models and architectures (e.g., those naturally expressed through high-level constructs like recursion).

## Topics
- Abstractions and syntax (beyond meta-programming and operator overloading) to naturally express a program (expression, or procedure) as an object to be manipulated
- Techniques from AD and probabilistic programming the ML community could adopt to enable research on new models
- How to overcome challenges due to the ML’s specific hardware (GPUs, specialized chips) and software (Python) stacks, and the particular demands of practitioners for their tools
- Greater collaboration between ML and programming languages communities

# Schedule
See the [official schedule](https://neurips.cc/Conferences/2019/Schedule?showEvent=13188).

Time | Activity
-----|----------
08:30–08:40| Introduction and opening statements
08:40–09:30| **Jan-Willem van de Meent** – TBA
09:30–09:50| Praveen Narayan – **Applications of a disintegration transformations** [[abstract](https://openreview.net/forum?id=r1xwBU5Vwr)]
09:50–10:30| Coffee break
10:30–11:20| **Christine Tasson** – TBA
11:20–11:40| Dimitrios Vytiniotis – **The Differentiable Curry** [[abstract](https://openreview.net/forum?id=ryxuz9SzDB)]
11:40–12:00| Fritz Obermeyer – **Functional Tensors for Probabilistic Programming** [[abstract](https://openreview.net/forum?id=HkecHuIaUS)]
12:00–14:00| Lunch and **poster session** [[accepted posters](#poster-session)]
14:00–14:50| *Zachary DeVito* – **Optimized execution of PyTorch programs with TorchScript**
14:50–15:40| *Skye Wanderman-Milne* – **JAX: accelerated machine-learning research via composable function transformations in Python**
15:40–16:20| Coffee break
16:20–16:40| Andreas Griewank – **Generalized Abs-Linear Learning** [[abstract](https://openreview.net/forum?id=rJg_5AF6LB)]
16:40–17:00| Jan Hückelheim – **Towards Polyhedral Automatic Differentiation** [[abstract](https://openreview.net/forum?id=B1glaOr0US)]
17:00–17:20| Jesse Bettencourt – **Taylor-Mode Automatic Differentiation for Higher-Order Derivatives in JAX** [[abstract](https://openreview.net/forum?id=SkxEF3FNPH)]
17:20–18:00| **Panel** and general discussion

The aim of our workshop is to bridge the gap between several research communities. We will use a format that includes a relatively large number of talks (10) with the aim of covering breadth rather than depth, allowing people from different backgrounds to make relevant connections. The poster session will be the opportunity for small groups to form and discuss topics of interest. The day will conclude with a panel to kickstart discussions that we hope will continue after the workshop has ended (i.e, on how to improve existing ML tooling, or the exploration of modern PL ideas in the context of ML).

## Poster session

The following submissions will be presented as posters:
- *Kotlin∇: A shape-safe DSL for differentiable programming* [[abstract](https://openreview.net/forum?id=SkluMSZ08H)]
- *Differentiation of High-Level Language Semantics* [[abstract](https://openreview.net/forum?id=ryllpA21vB)]
- *Composable Effects for Flexible and Accelerated Probabilistic Programming in NumPyro* [[abstract](https://openreview.net/forum?id=H1g1niFhIB)]
- *Dex: array programming with typed indices* [[abstract](https://openreview.net/forum?id=rJxd7vsWPS)]
- *Transforming Probabilistic Programs into Algebraic Circuits for Inference and Learning* [[abstract](https://openreview.net/forum?id=SygbjU6iBS)]
- *Transforming recursive programs for parallel execution* [[abstract](https://openreview.net/forum?id=B1lbS82pLS)]
- *Sparsity Programming: Automated Sparsity-Aware Optimizations in Differentiable Programming* [[abstract](https://openreview.net/forum?id=rJlPdcY38B)]
- *Approximations in Probabilistic Programs* [[abstract](https://openreview.net/forum?id=H1xM0lu6LS)]
- *Ad-Hoc Bayesian Program Learning* [[abstract](https://openreview.net/forum?id=H1xiDw_pIr)]
- *PyMC4: Exploiting Coroutines for Implementing a Probabilistic Programming Framework* [[abstract](https://openreview.net/forum?id=rkgzj5Za8H)]

# Submissions
We are soliciting contributions bridging the gap between the AD, (P)PL, ML and/or compiler/systems communities. Submissions should be 2 to 4 pages extended abstracts. They do not need to be anonymized. Submissions are non-archival. Work can include:
- recent work on these topics which was published in non-ML venues;
- preliminary or novel work demonstrating applications of program transformation techniques to ML (but not finalized work already published);
- a summary of multiple previous contributions on program transformation techniques with potential applications for ML.

Please submit your abstracts at [openreview.net/group?id=NeurIPS.cc/2019/Workshop/Program_Transformations](https://openreview.net/group?id=NeurIPS.cc/2019/Workshop/Program_Transformations).

Up to 6 submissions will be selected to give a contributed talk. The talks will be selected based on the quality of the submission, and with the aim of spanning the different research disciplines that this workshop aims to engage. Remaining submission will be considered for a poster session. Submissions will be reviewed by at least two, ideally three, people from the organizing committee, and will not be reviewed by people with a conflict of interest (i.e., a shared affiliation within the past 3 years).

The timeline for submissions is as follows:
- Monday 12 August, 2019: Submissions open
- Saturday 21 September, 2019: Submissions deadline
- Monday 23 September, 2019: Reviewing period starts
- Friday 27 September, 2019: Reviews due
- Monday 30 September, 2019: Decision deadline
- Tuesday October 1, 2019: NeurIPS notification deadline

## Travel & registration support
We are planning to get sponsorship funding in order to support a part of the registration and/or travel costs of a number of attendees. If you require such assistance please let the organizers know by sending an email at the time of paper submission. More information will be available in due course.

# Access to content
In order to provide access to the members of the machine learning community who cannot attend NeurIPS in person, we will be live streaming and recording all the talks delivered in the workshop, as arranged by the conference. We will provide talk summaries, videos, and presentation slides on our workshop website, along with all accepted papers and corresponding posters. We are planning to publish a workshop summary following the event, highlighting the main emerging trends and subjects discussed in our workshop.

# Previous related workshops
In the past, we organized a similar workshop on AD for machine learning at NeurIPS [2016](https://autodiff-workshop.github.io/2016.html) and [2017](https://autodiff-workshop.github.io). This year, we are broadening the scope of the workshop to involve more types of semantic program transformations, in particular for probabilistic programming, and hope to attract more experts in programming languages and compiler design as attendees.

Another similar effort was started this year at POPL, where the probabilistic programming languages workshop (PPL) became “Languages for Inference” ([LAFI](https://popl19.sigplan.org/track/lafi-2019)), bringing machine learning and differentiable programming into a programming languages conference. We believe that events with these goals should happen both in machine learning and programming language conferences, in order to help bridge these gaps and foster greater collaborations.

# Biographies
## Confirmed Keynote Speakers

**Jan-Willem van de Meent** is an assistant professor at Northeastern University. He is working on probabilistic programming frameworks at the intersection with machine learning, and co-author of [“An Introduction to Probabilistic Programming”](https://arxiv.org/abs/1809.10756).

**Zachary DeVito** is a research engineer at Facebook AI Research.

**Christine Tasson** is an associate professor at Université de Paris. Her research areas are at the boundary of Computer Science, Mathematics and Logics. She is interested in denotational semantics and its applications to distributed systems and functional probabilistic programming.

**Skye Wanderman-Milne** is a software engineer at Google Brain working on JAX, a system for composable function transformations in Python. Prior to that, she has worked on TensorFlow and Cloudera Impala, a high-performance distributed database.


## Organizing committee
**Alex Wiltschko** [[link](https://scholar.google.com/citations?user=GPnusKcAAAAJ)] is a research scientist at Google Brain, focusing on building more flexible machine learning software systems, and also applications of machine learning to biology and chemistry. He completed his PhD in Neurobiology at Harvard, focusing on quantifying animal body language using depth cameras and time-series modeling. Alex also co-organizes a regular symposium on the intersection of machine learning and biology.

**Atılım Güneş Baydin** [[profile](http://www.robots.ox.ac.uk/~gunes/)] is a postdoctoral researcher at the University of Oxford, focusing on probabilistic programming and applications of machine learning to fundamental sciences. He is also a research consultant to Microsoft Research Cambridge and an AI Technical Committee member at NASA Frontier Development Lab. He is the author DiffSharp, a library for differentiable functional programming, and pyprob, a probabilistic programming system. Güneş was a co-organizer of the Deep Learning for Physical Sciences workshop at NeurIPS 2017.

**Bart van Merriënboer** [[profile](https://scholar.google.ca/citations?user=XE9SDzgAAAAJ)] is a research scientist at Google Brain, who recently completed his PhD at Mila under the supervision of Yoshua Bengio. His work focuses on the application of deep learning to natural language processing and the development of machine learning tools and frameworks. He previously contributed to ML frameworks such as Theano, Torch, torch-autograd, and Blocks/Fuel and is an author of the Tangent and Myia frameworks.

**Pascal Lamblin** [[profile](https://scholar.google.ca/citations?user=bn4xHHIAAAAJ)] is a research engineer at Google Brain. After completing an engineering degree at École Centrale Paris, he has done research under the supervision of Yoshua Bengio at Université de Montréal where he also worked on the development of Theano.

**Emily Fertig** [[profile](https://ai.google/research/people/EmilyFertig)] is an AI Resident in Google Research, working on quantifying uncertainty in the predictions of deep neural networks, for the purpose of improving risk management and decision-making under uncertainty in machine-learning systems. Previously she worked as a technical consultant and data scientist in the electricity industry, researched numerical methods for climate policy decision-making at MIT and Penn State, and completed a Ph.D. in Engineering and Public Policy at Carnegie Mellon.

**Barak Pearlmutter** [[profile](http://barak.pearlmutter.net)] is a professor at Maynooth University in Ireland. His research spans adaptive systems, neural networks, machine learning, acoustic source separation and localization, neuroscience, and programming language design and implementation. He is a leading expert in functional automatic differentiation. He has a Ph.D. in Computer Science from Carnegie Mellon University.

**Laurent Hascoët** [[profile](http://www-sop.inria.fr/members/Laurent.Hascoet/)] is a Research Director at INRIA Sophia-Antipolis. His research focuses on software tools for scientific computing, partial evaluation and automatic parallelisation, and automatic differentiation. He is known for promoting the use of AD in the scientific computation community, including applications of AD technology to real programs, but also the definition of methodologies for a clever use of AD derivatives in optimization problems or inverse problems.

**David Duvenaud** [[profile](http://www.cs.toronto.edu/~duvenaud/)] is an assistant professor in computer science and statistics at the University of Toronto.  He holds a Canada Research Chair in generative models.  His postdoctoral research was done at Harvard University, where he worked on hyperparameter optimization, variational inference, and chemical design. He did his Ph.D. at the University of Cambridge, studying Bayesian nonparametrics with Zoubin Ghahramani and Carl Rasmussen.  David spent two summers in the machine vision team at Google Research, and also co-founded Invenia, an energy forecasting and trading company.  David is a founding member of the Vector Institute and a Faculty Fellow at ElementAI.
