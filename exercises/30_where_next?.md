# Python for Linguists 2023

## 30. Where next?

Effort profile: `(▁▁▁▁▁▁▁▁▁)` 



----

🦉 **_This entire section is OPTIONAL!_**

----

**30.1.** First of all, **download this repository**, or at least the exercises folder, to your computer. I'm not sure how long these exercises will be available here, and in any case, at some point they will be updated -- sections split and merged and exercises reordered -- after which the numbering in your notes and solutions will no longer correspond to the files in this repository.

**30.2.** Now would be the _perfect_ time to read the official **Python tutorial** (https://docs.python.org/3/tutorial/), which provides an excellent, detailed but readable overview of everything you have learned, and some things you haven't learned yet. Although it's called a 'tutorial', it is not very well-suited to people with no programming experience -- but it makes for the _perfect_ recap at the end of this course!

**30.3.** The book **Humanities Data Analysis: Case Studies with Python** (https://www.humanitiesdataanalysis.org/) is a perfect continuation of this course; virtually a 'Python for Linguists part II'. It is aimed at students and researchers in the humanities (primarily working with textual data) who are already familiar with the Python programming language. The case studies are _very_ interesting and diverse (cookbooks, naming and gender data, historical text stylometry, geographical data, readership trends), and introduce you to widely used libraries such as `pandas` for tabular data, `matplotlib` for plotting and `sklearn` for statistical analysis.

**30.4.** Any of the central libraries for data analysis, linguistics and natural language processing (`pandas`; `matplotlib` and `seaborn`; `sklearn`; `spacy`) have their own documentation, as well as tons of examples and tutorials provided by the community. The Python ecosystem is enormous. It will be worthwhile to read a summary of each of these libraries (such as '10 minutes to pandas', https://pandas.pydata.org/docs/user_guide/10min.html), just so you know where to look if you ever need something. However, try not to get stuck in 'tutorial hell', as you will never know all there is to know. Instead, move on to the next point as soon as possible.

**30.5.** The present course has taught you enough Python for you to **start your own small projects and learn more by doing**, searching the web as required. Depending on your interest, this could involve:
 - Finding _existing datasets_ in a domain you find interesting, and exploring the data with Python -- and of course not all linguistic data is text: there are Python libraries for dealing with audio and images as well. 
 - Finding a study in _experimental linguistics_ that comes with published experimental results, and in Python try to reproduce their statistical analyses, or go beyond them by programming a theoretically informed 'human participant simulator' that can reproduce the raw data. 
 - Taking an approach from _theoretical linguistics_ to try to implement some of its components computationally, or integrate it with an existing computational approach (e.g., the integration of distributional and formal semantics is a hot topic).

**30.6.** A huge and important topic in natural language processing, for both applications and research, is **machine learning**, and especially **deep learning** with artificial neural networks. Core libraries to familiarize yourself with are `sklearn`, `transformers` (https://huggingface.co/docs/transformers/quicktour) and `pytorch` (https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html). While it is fairly easy nowadays to run existing examples for training and testing a neural network model (e.g., this example about audio classification: https://huggingface.co/docs/transformers/tasks/audio_classification), taking it into new directions will require, besides Python, a basic understanding of the underlying maths. Leiden University offers a bachelor course on this topic, using Python (https://studiegids.universiteitleiden.nl/courses/109780/natural-language-processing). There are also free courses; the first few classes here seem excellent: https://www.nlpdemystified.org/.

**30.7.** For a detailed overview of central concepts in computational linguistics independently of Python, have a look at Jurafsky & Martin's **Speech and Language Processing** (https://web.stanford.edu/~jurafsky/slp3/). You will find thorough coverage of by-now familiar topics (regular expressions, n-grams, sentiment, parts of speech, named entities, dependency grammar, word vectors) as well as many topics not covered by the present course (e.g., deep learning, coreference resolution, word senses, chatbots, phonetics).

**30.8.** For anything but the tiniest Python script, **version management** quickly becomes indispensible. PyCharm comes with integrated support for different version control systems (VCS) including `git`. The easiest way to get started is to sign up to `github.com`, create a new repository there containing only the default readme file, then go to the PyCharm welcome screen (e.g., by closing any active projects), click the `VCS` button and paste the github link to your repository. If `git` is installed on your system, this will 'clone' the repository hosted on `github` to your local drive, and open it as a project in PyCharm. Within PyCharm, try opening the readme file and make some changes. You should see that it now tracks your changes (indicated by blue file names and in the margin). Whenever you finish a meaningful change, `commit` it. Whenever you have committed a bunch of related changes, `push` those commitments from your local drive to the repository on `github`. (Conversely, whenever the files on `github` have changed (e.g., if you are collaborating, or changed something on `github.com` directly from within the web browser), you need to `pull` the changes to your local drive.) For an introduction to `git` + `PyCharm` see https://www.youtube.com/watch?v=-_g3QITLaQA (among many others).

**30.9.** Consider revisiting the various Python exercise sections in this repository some time in the future. The various Coding Quests can still provide you with plenty of relevant challenges, but also the more 'boring' exercises can deepen your understanding and entrench some fruitful programming habits. Challenge yourself to a speedrun.



-------

**_The homework exercises for week 16 end here (nothing to submit this week)._**

-------




