# CSUF-MATH-170B-LINEAR-ALGEBRA

## [CLICK HERE TO OPEN NOTEBOOK](https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/notebook/table%20of%20contents.md)
[<img src="https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/data/Linear%20Algebra%20Card.png" width="600">](https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/data/Linear%20Algebra%20Card.png)
### [Syllabus](https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/Math%20170B-02.pdf)
### [textbook](https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/Nicholson-OpenLAWA-2021A.pdf)
### [Course Notes (provided by prof)](https://github.com/jlursenbach/CSUF-MATH-170B-LINEAR-ALGEBRA/blob/main/170B_CourseNotes.pdf)


## About this repository:
The purpose of this repository is to act as a resource and record of the materials
and concepts covered in this course. I try to keep my notes organized and complete as 
possible, but it can be hard, and if you see anything that could be corrected, improved,
or added feel free to include that. It could help myself, or future students. 
Anyone is welcome to contribute! 

### What is not allowed: 
No blank tests, test answers, or completed homework should be added to this repository.
Uploading projects as examples and records of work should be ok and is encouraged  
if they are creative works and not something that can have answers copy/pasted. 
Blank homework assignments are fine. 
While I hope this can be a resource for myself and others, 
that resource should and will adhere to strict academic integrity. 

> (note) The following instructions are courtesy of Stanford Vision Lab https://github.com/StanfordVL/cs131_notes
> I will be running through them and eventually customizing them for my own notes 

## Instructions for creating class notes:

### Overall workflow
1. Fork this repository by clicking the "Fork" button on the top right of [this
page](https://github.com/StanfordVL/cs131_notes).

2. Next, clone your forked repository into your local machine:
```
git clone github.com/YOUR_GITHUB_ACCOUNT/cs131_notes.git
```
3. Give others permission to commit to your forked repository by clicking on
"Settings" and then "Collaborators".
3. Write up the class notes.
4. Push your changes to your forked repository.
5. Send a pull request to the official
[repository](https://github.com/StanfordVL/cs131_notes).

### Downloading the software and testing the repository.
1. Download [pdfltex](https://www.tug.org/applications/pdftex/) so that you can
compile the tex documents. You can also use [Overleaf](overleaf.com) or
[Sharelatex](sharelatex.com) to compile your tex documents.

2. Go into the template folder and compile the format and template files:
```
cd template

pdflatex format.tex
bibtex format
pdflatex format.tex

pdflatex template.tex
bibtex template
pdflatex template.tex
```

3. Make sure that template.pdf and format.pdf have been generated and are correctly
displayed. Read format.pdf to understand how we expect the class notes to be
formatted.

### Writing class notes for a given lecture
1. Create a folder called `LectureXX` where `XX` is `01` for the first lecture
or `18` for the eighteenth lecture.

2. Copy over template.tex and bibliography.bib to your folder.
```
cp template/template.tex lectureXX/lectureXX.tex
cp template/bibliography.bib lectureXX/bibliography.bib
```

3. Write the lecture notes. Make sure to include pictures, references and
tables. If you add images, make sure to give credit to the source of those
images.

4. Compile your lecture template to make sure that it formats correctly.
```
cd lectureXX
pdflatex lectureXX.tex
bibtex lectureXX
pdflatex lectureXX.tex
```
5. Submit a pull request to have your lecture notes merged.

(note) (note) instructions courtesy of Stanford Vision Lab https://github.com/StanfordVL/cs131_notes
