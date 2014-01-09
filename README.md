## compiling to PDF

To get a PDF, simply run the following code:

```{sh}
git clone https://github.com/seandavi/PIRetreat2014ComputePoster.git
cd PIRetreat2014ComputePoster
pdflatex PIRetreat2014Compute.tex
```

Make changes to the .tex file using any text-based editor.  Recompile pdf to make sure it looks like you think it should.  Then:

```{sh}
git add .
git commit -m 'PUT IN YOUR COMMENT HERE'
git push origin master
```
