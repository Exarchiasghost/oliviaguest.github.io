---
layout: page
title: Connectionist Models and Cognitive Processes
permalink: /connectionism/
published: true
---

<h2>Course Materials</h2>
<b>This course is not running at the moment, as such the materials are made unavailable.</b> If you need them, you may email me.

<!--

<h3>1st Week: Introduction to Programming and Connectionist Networks</h3>
- Code: [pyceptron.py](https://github.com/oliviaguest/connectionism/raw/master/week1/pyceptron.py)
- Slides: [Part 1: Intro to Programming](https://github.com/oliviaguest/connectionism/raw/master/week1/slides/part_1_slides.pdf), [Part 2: Intro to Networks](https://github.com/oliviaguest/connectionism/raw/master/week1/slides/part_2_slides.pdf)
- Exercises: [Pyceptron](https://github.com/oliviaguest/connectionism/raw/master/week1/exercises/exercises.pdf)

<h3>2nd Week: Going from Two Network Layers to Three</h3>
- Code: [network_missing.py](https://github.com/oliviaguest/connectionism/raw/master/week2/network_missing.py), [network_hints.py](https://github.com/oliviaguest/connectionism/raw/master/week2/network_hints.py), [network.py](https://github.com/oliviaguest/connectionism/raw/master/week2/network.py)
- Slides: [Part 3: Feedfoward Networks](https://github.com/oliviaguest/connectionism/raw/master/week2/slides/part_3_slides.pdf)
- Exercises: [Backpropagation](https://github.com/oliviaguest/connectionism/raw/master/week2/exercises/exercises.pdf)

<h3>3rd Week: Replicating a Model</h3>
- Code: [network.py](https://github.com/oliviaguest/connectionism/raw/master/week3/network.py)
- Patterns: [tyler_patterns.csv](https://github.com/oliviaguest/connectionism/raw/master/week3/tyler_patterns.csv)
- Slides: [Part 4: Replicating a Model](https://github.com/oliviaguest/connectionism/raw/master/week3/slides/part_4_slides.pdf)
- Exercises: [Replication of Tyler et al. (2000)](https://github.com/oliviaguest/connectionism/raw/master/week3/exercises/exercises.pdf)
- Tyler, L. K., Moss, H. E., Durrant-Peatfield, M. R., & Levy, J. P. (2000). **[Conceptual structure and the structure of concepts: A distributed account of category-specific deficits](https://github.com/oliviaguest/connectionism/raw/master/week3/tyler_2000.pdf)**. *Brain and Language*, 75(2), 195-231.

<h3>4th Week: Writing up Experimental Results</h3>
- Code: [network.py](https://github.com/oliviaguest/connectionism/raw/master/week4/network.py), [graph.py](https://github.com/oliviaguest/connectionism/raw/master/week4/graph.py)
- Example file for errors: [errors1000.txt](https://github.com/oliviaguest/connectionism/raw/master/week4/errors1000.txt)
- Slides: [Part 5: Writing the Report](https://github.com/oliviaguest/connectionism/raw/master/week4/slides/part_5_slides.pdf)
- Exercises: [File Input/Output](https://github.com/oliviaguest/connectionism/raw/master/week4/exercises/exercises.pdf)

<h2>Reading Materials</h2>
- [Essay: A Brief Introduction to Connectionism](http://kimplunkett.org.uk/secondtry/page31/page32/index.html)
-->
<h2>Programming</h2>
<h3>Exercises</h3>
- [Codecademy](//www.codecademy.com)
- [LearnPython.org](http://www.learnpython.org/)
- [Codewars](http://www.codewars.com/)
- [Code School: Python](https://www.codeschool.com/paths/python)

<h3>Books</h3>
- [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)
- [How to Think Like a Computer Scientist: Learning with Python](http://www.openbookproject.net/thinkcs/python/english2e/)
- [Think Python: How to Think Like a Computer Scientist](http://www.greenteapress.com/thinkpython/)

<h2>Inspiration</h2>
<h3>Libraries</h3>
- [Numpy Tutorial](http://www.python-course.eu/numpy.php)
- [Matplotlib Examples](http://matplotlib.org/1.4.0/examples/index.html)
- [A Primer on Scientific Programming with Python](https://hplgit.github.io/scipro-primer/slides/index.html)
- [Scipy Lecture Notes](http://www.scipy-lectures.org)

<h3>Blogs</h3>
- [The Glowing Python](http://glowingpython.blogspot.co.uk/): This blog has various examples of interesting code to play with and give you ideas for your own projects.
- WildML: [Recurrent Neural Networks Tutorial, Part 1 – Introduction to RNNs](http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/): This blog also has other Machine Learning tutorials.

<h3>Video Lectures</h3>
- [Machine Learning](https://www.youtube.com/playlist?list=PLg7f-TkW11iX3JlGjgbM2s8E1jKSXUTsG), by The Royal Society
- [The Cognitive and Computational Neuroscience of Categorization, Novelty-Detection, and the Neural Representation of Similarity](https://www.youtube.com/watch?v=2Ei6wFJ9kCc), by Mark Gluck

<h2>Online Courses</h2>
- [Machine Learning](https://www.coursera.org/learn/machine-learning/), by Andrew Ng
- [Neural Networks for Machine Learning](https://www.coursera.org/course/neuralnets), by Geoffrey Hinton
- [Introduction to Neural Networks](http://ocw.mit.edu/courses/brain-and-cognitive-sciences/9-641j-introduction-to-neural-networks-spring-2005/index.htm), by Sebastian Seung

<h2>How to install Python</h2>
<h3>Windows Users</h3>
This is a little tricky:

- Install Python: [download from here](https://www.python.org/ftp/python/2.7.10/python-2.7.10.msi)

- Install matplotlib, numpy, and scipy using pip. Specifically you need to download the following from [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/):
  - matplotlib-1.4.3-cp27-none-win32.whl
  - numpy-1.10.0b1+mkl-cp27-none-win32.whl
  - scipy-0.16.0-cp27-none-win32.whl
 
  This requires you to be in the Scripts folder of the Python27 installation. And to use the windows command prompt. For me this looks like:

{% highlight doscon %}
C:\Python27\Scripts>pip install NAME_OF_WHEEL_FILE.whl
{% endhighlight %}

  For all three of those you need to run a pip command like above.  

- Install PyGTK: [download from here](http://ftp.gnome.org/pub/GNOME/binaries/win32/pygtk/2.24/pygtk-all-in-one-2.24.2.win32-py2.7.msi)

- To check that everything works, open network.py and see if it runs without any errors.

<h3>Mac Users</h3>
I finally managed to do this on my mac. Use [Homebrew](http://brew.sh/) to install matplotlib, numpy, scipy, pygtk.

<h3>Linux Users</h3>
Use your favourite package manager to install matplotlib, numpy, scipy, pygtk.
