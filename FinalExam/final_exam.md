# BMI 6018 Final Exam
## Fall 2018
## Due December 20th 11:59 PM

The purpose of this final exam is to give you the opportunity to demonstrate your independence in developing and using software to work with biomedical data.

To complete this exam you will need to create a Jupyter notebook that demonstrates topics that we have not covered in class. This includes but is not limited to:

* Demonstrating elements of the standard library. For example, you may wish to
  * [zipfile](https://docs.python.org/3/library/zipfile.html) for reading or creating zip files.
  * [smtplib](https://docs.python.org/3/library/smtplib.html#module-smtplib) to send e-mail
  * [email](https://docs.python.org/3/library/email.html) and [imaplib](https://docs.python.org/3.7/library/imaplib.html) to read and parse messages in an inbox.
  * [multiprocessing](https://docs.python.org/3.7/library/multiprocessing.html) (or [ipyparallel](https://github.com/ipython/ipyparallel)) for parallel computing.

* Demonstrating third-party packages
  * [scikit-image](https://scikit-image.org/)
  * [cython](https://cython.org/) for increasing execution speed
  * [spacy](https://spacy.io/) for natural languae processing
  * [NetworkX](https://networkx.github.io/) for working with graph data
  * Interactive visualization with packages such as [Bokeh](https://bokeh.pydata.org/en/latest/) or [Altair](https://altair-viz.github.io/)
  * Web scrapping with [scrapy](https://doc.scrapy.org/en/latest/intro/tutorial.html)
* Demonstrating functional programming with Python (See, for example, [Functional Programming with Python](https://utah-primoprod.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=UUU_ALMA51454290470002001&context=L&vid=UTAH&lang=en_US&search_scope=EVERYTHING&adaptor=Local%20Search%20Engine&tab=everything&query=any,contains,%E2%80%9CFunctional%20Programming%20in%20Python%E2%80%9D&sortby=rank&offset=0))

* Create a notebook summarizing one of the chapters in the textbook not covered in class (e.g. Chapters 9, 10, or 20)

* "Translate" one of the notebooks from modules (week7-pandas, weekk11-monte-carlo, week14-text_processing, or week15-text_processing_part2) into a different language (e.g. R, Julia, Elm, Haskell). A list of available Jupyter kernels is [here](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels). My experience is limtied to Julia, Elm, Haskell, and Gopher.  
  * I will be happy to install a kernel if you want to use something other than R or Julia.
* This notebook may be part of a larger project for extra credit (e.g. air quality and health).

The notebooks should take you no more than 3-4 hours to create. Do not just copy and paste materials from another notebook. Feel free to contact the TAs or me for help, but do not work with other students.

# Rubric

* *10 points:* A clear explanation of how to install any software that your notebook depends on, including any third-party packages that might already be installed on our system.
* *20 points:* A description of why this package is of interest and how it would be useful within a relevant domain (presumably biomedicine).
* *20 points:* Reading and writing relevant domain data
  * Preferably use data available on bmi6018 either in the DATA directory or the MySQL server we used in the text processing module
* *20 points:* Well written, modular code. Functions should have doc strings (or the equivalent in an alternative language), perform a single task, etc.
* *10 points:* Platform, data independent code. No hardwired directories, fixed data sizes, etc.
* *20 points:* References to materials (books, websites, etc.) you used in creating the notebook.
* *Extra Credit of 20 points:* Posting your notebook on the Slack Class Participation channel so that classmates can learn from your work.
