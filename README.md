# cmd-hodgepodge
Collection of useful linux commands

# Table of Contents
- 1 Files
- 2 WIP
- 3 Documents
- 4 Music

# 1 Files
- foreach file
```bash
find . -name "*.test" -exec testcommand {} \;
```

# 2 WIP

# 3 Documents
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

# 4 Music
- compute replaygain
```bash
pip3 install rgain3
replaygain --no-album *.mp3
```
