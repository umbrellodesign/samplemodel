# samplemodel
this is an open platform git repository for umbrello object collaboration
if you want to work on umbrello based diagrams this repostory can act as your project control or object analysis
blog.
how to use
1.on this hub multiple users can work on the same project.
2.easy to commit and clone.

how to use

to get a clone of the project  

$ git clone https://github.com/umbrellodesign/samplemodel.git

this creates a working model of the project on your local system 
you can modify it the way you like./////

if suppose you already have an object to share you can upload it here on the repository
for this purpose you should know how to create a git repository on your local system.
to create a git repository

$ git init project_name

this creates an empty git repository for your project.
move your umbrello object in this folder.

$ git add diagram1

check the git status


$ git status

to commit your change to your local repository



$ git commit diagram1

Now you can easily merge your project in the global repository on github


$ git remote add origin https://github.com/umbrellodesign/modelname.git 


$ git push -u origin master



