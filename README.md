# cmd-hodgepodge
Collection of useful linux commands

# Table of Contents
- [Files][1]
- [WIP][2]
- [Documents][3]
- [Music][4]

# Files
- foreach file
```bash
find . -name "*.test" -exec testcommand {} \;
```

# WIP

# Documents
- combine PDFs
```bash
sudo apt install poppler-utils
pdfunite a.pdf b.pdf c.pdf output.pdf
```

- Image to PDF
```bash
sudo apt install img2pdf
img2pdf in.jpeg --output out.pdf
```

# Music
- compute replaygain
```bash
pip3 install rgain3
replaygain --no-album *.mp3
```
