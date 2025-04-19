# Day 3

cover the following concepts and answers for the questions 

- [Day 3](#day-3)
  - [Programming Language for AI](#programming-language-for-ai)
    - [Why Python?](#why-python)
  - [What is a Conda Environment?](#what-is-a-conda-environment)
    - [Why Conda Environments](#why-conda-environments)

---

1. ## **History of AI** 

![History of AI](images/history_of_ai.png)

* **Origin of AI (1943)**: The concept of neural networks was first introduced by Warren McCulloch and Walter Pitts in 1943, inspired by how human brain neurons work. 
  
* **Turing Test (1950)**: Alan Turing proposed the idea of machine intelligence and introduced the famous "Turing Test" to evaluate if a machine can exhibit human-like intelligence.

* **Birth of the Term “AI” (1955)**: John McCarthy coined the term Artificial Intelligence. Collaborating with Stanford and MIT, he developed early AI programs using the Lisp language.

*** AI as a Field (1956)**: The Dartmouth Conference officially marked AI as a separate research field.

* **Intelligence Explosion Concept (1965)**: Based on Bayesian statistics, the idea of rapid AI development, or “intelligence explosion,” emerged.

* **Early AI Systems (1966–1985)**:
  * Joseph Weizenbaum developed ELIZA (1966), a natural language processing chatbot.
  * The first influential AI textbook appeared in 1969.
  * Stanford developed DENDRAL in 1975, an expert system to analyze chemical compounds.
  * In 1979, the first question-answering system called SCHOLAR was created.
  * In 1985, the Boltzmann machine was developed (a type of recurrent neural network).

* **AI in Games (1997)**: IBM’s Deep Blue defeated the world chess champion, marking a major milestone in AI.

* **AI in Quiz Shows (2011)**:IBM Watson beat human champions in the quiz show Jeopardy!
  
* **Deep Learning Revolution (2012 onwards)**:With the rise of deep neural networks, AI began transforming industries such as:
    * Computer vision
    * Speech recognition
    * Robotics
    * Healthcare
    * Industry
    * And many more

* **Current Impact**: AI is now deeply embedded in our daily lives. Tools like OpenAI and advancements from companies like Google and Microsoft are accelerating AI’s reach. Programming languages like Python, R, and Julia have become essential due to the growth in data and computing power.

---

## Programming Language for AI
There are so many langugaes around there but the best choice for AI & Data Science is Python. 

### Why Python?
  * Python is open-source, free, and community-supported.
  * It has huge libraries and frameworks for AI, ML, data analysis, and more.
  * Cross-platform compatible – usable in small apps to large-scale systems.
  * Strong ecosystem for interactive coding, testing, and rapid prototyping.

-----

## What is a Conda Environment?
A Conda environment is a self-contained space for your Python project — it has its own Python version, libraries, and dependencies.
💡 Think of it like:
> A separate room for each project, where everything it needs is inside — and it doesn’t mess up other rooms (projects).


### Why Conda Environments 
![MiniConda Environment ](images/why%20miniconda.png)

Conda Environments are Helpful in Data Science & AI for the following reasons.
1. **Avoid Conflicts Between Projects**: Different projects may require different versions of libraries (e.g., TensorFlow 1.x vs 2.x). Conda helps isolate them.

2. **Custom Python Versions** You can use Python 3.11 for one project and Python 3.9 for another — without breaking your system's Python.

3. **Reproducibility**: You can export environments (.yml file) and share them — so anyone can replicate your exact setup easily.

4. **Easy Dependency Management** Install hundreds of packages (e.g., NumPy, Pandas, scikit-learn) using one tool, from Conda’s own package repositories.

5. **Compatible with Both Pip & Conda**: You can use both conda install and pip install in the same environment.

> Miniconda = Mini + Conda 
> A minimal installer for Conda.
> [Miniconda official Site](https://www.anaconda.com/docs/getting-started/miniconda/main)

Using Conda environments (via Miniconda) is a best practice in Data Science & AI development to manage dependencies, isolate projects, and ensure reproducibility — all while avoiding "it works on my machine" problems.

-----
