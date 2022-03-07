# Pipeline templates (etc)

These files are text documents containing templates for various bioinformatic pipelines. They were developed for implementing
the major methods employed by the Vogler Lab at the NHM, and the associated detailed documentation and discussion of key 
concepts can be found in the (private) Vogler Lab wiki. They are uploaded here to make sharing with collaborators and students
easy, and if they can be useful to other researchers then I would be happy. Please contact me with any questions and I will
help if feasible.

Note that if you're interested in metabarcoding but are new to this area of bioinformatics, you may wish to head to our  
[Learn Metabarcoding](https://learnmetabarcoding.github.io/) course.

These pipelines are designed to be used as templates for your own analysis. They may require file names to be changed
or steps to be tweaked to fit your research questions. It is crucial you make sure you understand what each step is doing by 
reading the Vogler Lab wiki and the documentation for the function you're running. I suggest that you download or copy/paste
the files into your own text document, that you then modify. The pipelines are written such that, once you've customised the
template to fit your research questions, it should be trivial to convert them to bash scripts and/or simply copy-paste 
commands in order to run your analyses.

The scripts all assume you have installed or have available the software and scripts required, and that they are accessible on
your PATH. You may need to install software, download scripts, add directories to your PATH and/or modify the commands to get 
them to work for your situation. Note that any of my own scripts that I reference are available on other repositories on this
github - see the biotools and phylostuff repositories for most standalone scripts, and the mitocorrect and metamate repositories
for those tools.
