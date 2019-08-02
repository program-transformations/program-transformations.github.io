# Summary
Machine learning researchers often express complex models as a program, relying on program transformations to add functionality. New languages and transformations (e.g., TorchScript and TensorFlow AutoGraph) are becoming core capabilities of ML libraries. However, existing transformations, such as automatic differentiation (AD), inference in probabilistic programming languages (PPL), and optimizing compilers are often built in isolation, and limited in scope. This workshop aims at viewing program transformations in ML in a unified light, making these capabilities more accessible, and building entirely new ones.

Program transformations are an area of active study. AD transforms a program performing numerical computation into one computing the gradient of those computations. In PPL, a program describing a sampling procedure can be modified to perform inference on model parameters given observations. Other examples are vectorizing a program expressed on one data point, and learned transformations where ML models use programs as inputs or outputs.

This workshop will bring together researchers in the fields of AD, programming languages, compilers, and ML, with the goal of understanding the commonalities between disparate approaches and views, and sharing ways to make these techniques broadly available. It would enable ML practitioners to iterate faster on novel models and architectures (e.g., those naturally expressed through high-level constructs like recursion).

## Topics
- Abstractions and syntax (beyond meta-programming and operator overloading) to naturally express a program (expression, or procedure) as an object to be manipulated.
- Techniques from AD and PPL the ML community could adopt to enable research on new models
- How to overcome challenges due to the ML’s specific hardware (GPUs, specialized chips) and software (Python) stacks, and the particular demands of practitioners for their tools
- Greater collaboration between ML and programming languages communities

# Submissions
We will solicit contributions bridging the gap between the AD, (P)PL, ML and/or compiler/systems communities. Submissions should be 2 to 4 pages extended abstracts. They do not need to be anonymized. Submissions are non-archival. Work can include:
- recent work on these topics which was published in non-ML venues;
- preliminary or novel work demonstrating applications of program transformation techniques to ML (but not finalized work already published);
- a summary of multiple previous contributions on program transformation techniques with potential applications for ML.

Up to 6 submissions will be selected to give a contributed talk. The talks will be selected based on the quality of the submission, and with the aim of spanning the different research disciplines that this workshop aims to engage. Remaining submission will be considered for a poster session. Submissions will be reviewed by at least two, ideally three, people from the organizing committee, and will not be reviewed by people with a conflict of interest (i.e., a shared affiliation within the past 3 years).

The timeline for submissions is as follows:
- Monday 5 August, 2019: Submissions open
- Monday 16 September, 2019: Submissions deadline
- Wednesday 18 September, 2019: Reviewing period starts
- Wednesday 25 September, 2019: Reviews due
- Friday 27 September, 2019: Decision deadline
- Tuesday October 1, 2019: NeurIPS notification deadline

## Travel & registration support
We are planning to get sponsorship funding in order to support a part of the registration and/or travel costs of a number of attendees. If you require such assistance please let the organizers know by sending an email at the time of paper submission. More information will be available in due course.

# Tentative schedule
The aim of our workshop is to bridge the gap between several research communities. We will use a format that includes a relatively large number of talks (10) with the aim of covering breadth rather than depth, allowing people from different backgrounds to make relevant connections. The poster session will be the opportunity for small groups to form and discuss topics of interest. The day will conclude with a panel to kickstart discussions that we hope will continue after the workshop has ended (i.e, on how to improve existing ML tooling, or the exploration of modern PL ideas in the context of ML).

Time | Activity
-----|----------
08:50–09:00| Introduction
09:00–09:50| Keynote 1
09:50–10:10| Contributed talk 1
10:10–10:30| Contributed talk 2
10:30–11:00| Coffee break
11:00–11:50| Keynote 2
11:50–12:10| Contributed talk 3
12:10–13:50| Lunch and poster session
13:50–14:40| Keynote 3
14:40–15:00| Contributed talk 4
15:00–15:30| Coffee break
15:30–15:50| Contributed talk 5
15:50–16:10| Contributed talk 6
16:10–17:00| Keynote 4
17:00–18:00| Panel and general discussion

# Access to content
In order to provide access to the members of the machine learning community who cannot attend NeurIPS in person, we are planning to arrange the video recording of all the talks delivered in the workshop and potentially live stream these on YouTube during the event. We will provide talk summaries, videos, and presentation slides on our workshop website, along with all accepted papers and corresponding posters. We are planning to publish a workshop summary following the event, highlighting the main emerging trends and subjects discussed in our workshop.

# Previous related workshops
In the past, we organized a similar workshop on AD for machine learning at NeurIPS [2016](https://autodiff-workshop.github.io/2016.html) and [2017](https://autodiff-workshop.github.io). This year, we are broadening the scope of the workshop to involve more types of semantic program transformations, in particular for probabilistic programming, and hope to attract more experts in programming languages and compiler design as attendees.

Another similar effort was started this year at POPL, where the probabilistic programming languages workshop (PPL) became “Languages for Inference” ([LAFI](https://popl19.sigplan.org/track/lafi-2019)), bringing machine learning and differentiable programming into a programming languages conference. We believe that events with these goals should happen both in machine learning and programming language conferences, in order to help bridge these gaps and foster greater collaborations.

# Biographies
## Confirmed Keynote Speakers

**Jan-Willem van de Meent** is an assistant professor at Northeastern University. He is working on probabilistic programming frameworks at the intersection with machine learning, and co-author of [“An Introduction to Probabilistic Programming”](https://arxiv.org/abs/1809.10756).

**Soumith Chintala** is a Researcher at Facebook AI Research, where he works on deep learning, reinforcement learning, generative image models, agents for video games and large-scale high-performance deep learning. Prior to joining Facebook in August 2014, he worked at MuseAmi, where he built deep learning models for music and vision targeted at mobile devices. He holds a Masters in CS from NYU, and spent time in Yann LeCun’s NYU lab building deep learning models for pedestrian detection, natural image OCR, depth-images among others.

**Christine Tasson** is an associate professor at Université de Paris. Her research areas are at the boundary of Computer Science, Mathematics and Logics. She is interested in denotational semantics and its applications to distributed systems and functional probabilistic programming.

**Matt Johnson** is a research scientist at Google Brain interested in probabilistic models, approximate inference algorithms, and software systems to support them. He works on JAX, a system for composable function transformations in Python. His other recent work includes composing graphical models with neural networks to leverage specialized inference algorithms, automatically recognizing and exploiting conjugacy structure for approximate integration without a domain-specific language, and model-based reinforcement learning from pixels with structured latent variable models.

## Organizing committee
**Alex Wiltschko** is a research scientist at Google Brain, focusing on building more flexible machine learning software systems, and also applications of machine learning to biology and chemistry. He completed his PhD in Neurobiology at Harvard, focusing on quantifying animal body language using depth cameras and time-series modeling. Alex also co-organizes a regular symposium on the intersection of machine learning and biology.

[https://scholar.google.com/citations?user=GPnusKcAAAAJ](https://scholar.google.com/citations?user=GPnusKcAAAAJ)

<br>**Atılım Güneş Baydin** is a postdoctoral researcher at the University of Oxford, focusing on probabilistic programming and applications of machine learning to fundamental sciences. He is also a research consultant to Microsoft Research Cambridge and an AI Technical Committee member at NASA Frontier Development Lab. He is the author DiffSharp, a library for differentiable functional programming, and pyprob, a probabilistic programming system. Güneş was a co-organizer of the Deep Learning for Physical Sciences workshop at NeurIPS 2017.

[http://www.robots.ox.ac.uk/~gunes/](http://www.robots.ox.ac.uk/~gunes/)

<br>**Bart van Merriënboer** is a research scientist at Google Brain, who recently completed his PhD at Mila under the supervision of Yoshua Bengio. His work focuses on the application of deep learning to natural language processing and the development of machine learning tools and frameworks. He previously contributed to ML frameworks such as Theano, Torch, torch-autograd, and Blocks/Fuel and is an author of the Tangent and Myia frameworks.

[https://scholar.google.ca/citations?user=XE9SDzgAAAAJ](https://scholar.google.ca/citations?user=XE9SDzgAAAAJ)

<br>**Pascal Lamblin** is a research engineer at Google Brain. After completing an engineering degree at École Centrale Paris, he has done research under the supervision of Yoshua Bengio at Université de Montréal where he also worked on the development of Theano.

[https://scholar.google.ca/citations?user=bn4xHHIAAAAJ](https://scholar.google.ca/citations?user=bn4xHHIAAAAJ)

<br>**Emily Fertig** is an AI Resident in Google Research, working on quantifying uncertainty in the predictions of deep neural networks, for the purpose of improving risk management and decision-making under uncertainty in machine-learning systems. Previously she worked as a technical consultant and data scientist in the electricity industry, researched numerical methods for climate policy decision-making at MIT and Penn State, and completed a Ph.D. in Engineering and Public Policy at Carnegie Mellon.

[https://ai.google/research/people/EmilyFertig](https://ai.google/research/people/EmilyFertig)

<br>**Barak Pearlmutter** is a professor at Maynooth University in Ireland. His research spans adaptive systems, neural networks, machine learning, acoustic source separation and localization, neuroscience, and programming language design and implementation. He is a leading expert in functional automatic differentiation. He has a Ph.D. in Computer Science from Carnegie Mellon University.

[http://barak.pearlmutter.net](http://barak.pearlmutter.net)

<br>**Laurent Hascoët** is a Research Director at INRIA Sophia-Antipolis. His research focuses on software tools for scientific computing, partial evaluation and automatic parallelisation, and automatic differentiation. He is known for promoting the use of AD in the scientific computation community, including applications of AD technology to real programs, but also the definition of methodologies for a clever use of AD derivatives in optimization problems or inverse problems.

[http://www-sop.inria.fr/members/Laurent.Hascoet/](http://www-sop.inria.fr/members/Laurent.Hascoet/)

<br>**David Duvenaud** is an assistant professor in computer science and statistics at the University of Toronto.  He holds a Canada Research Chair in generative models.  His postdoctoral research was done at Harvard University, where he worked on hyperparameter optimization, variational inference, and chemical design. He did his Ph.D. at the University of Cambridge, studying Bayesian nonparametrics with Zoubin Ghahramani and Carl Rasmussen.  David spent two summers in the machine vision team at Google Research, and also co-founded Invenia, an energy forecasting and trading company.  David is a founding member of the Vector Institute and a Faculty Fellow at ElementAI.

[http://www.cs.toronto.edu/~duvenaud/](http://www.cs.toronto.edu/~duvenaud/)

