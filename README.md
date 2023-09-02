# curriculum_vitae
Alice curriculum vitae

# how to convert a .tex file to a PDF

Install texlive and all the extras (Tested on Ubuntu 22.04.2).

In addition to the main texlive program, there are some extras and extra fonts and things you might want too. 

1. Install texlive (copy and paste and run this whole block of lines at once)

```
sudo apt install -y \  
    texlive \  
    texinfo \  
    texlive-fonts-recommended \  
    texlive-fonts-extra \  
    texlive-latex-extra
```

2. Use it:

```
pdflatex alice_en.tex  
pdflatex alice_fr.tex  
```

# how to clean up your working directory
```
git clean -f -d 
```
