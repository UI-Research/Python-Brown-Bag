# Python-Brown-Bag
Code for Python Brown Bag, October 25 2016

To play with this code yourself, download the entire contents of this repository to a folder on your computer.  When you have Anaconda Python 3.5 installed, open `pythonbb_presentation_annotated.ipynb` to see the slides with comments.  Update the _path =_ statement at the top to your local folder that you saved everything to.

To build the actual slideshow from the presentation, from a command line (that is, not in Python), type:

    conda install pandoc
	
Followed by:

    jupyter nbconvert --to slides d:\users\jlevy\downloads\pythonbb_presentation.ipynb --post serve--reveal-prefix "http://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.3.0"

Where you replace the path to the notebook (e.g. d:\users\jlevy...) with the path to your local notebook.  It will then open the presentation in your browser.

  - To get Python installed on your system, email helpdesk@urban.org and ask for version 3.5 to be installed on your computer from here: https://www.continuum.io/downloads

  - For Python questions, please feel free to contact the Research Programming team or the author directly, JLevy@urban.org.  
  
  - Stay tuned for information on the forthcoming Python Users Group!