# cmd-hodgepodge
Collection of useful linux commands

# Table of Contents
- [Files](#Files)
- [WIP](#WIP)
- [Documents](#Documents)
- [Music](#Music)

# Files
- foreach file
```shell
find . -name "*.test" -exec testcommand {} \;
```

# WIP

# Documents
- combine PDFs
```shell
sudo apt install poppler-utils
pdfunite a.pdf b.pdf c.pdf output.pdf
```

- Image to PDF
```shell
sudo apt install img2pdf
img2pdf in.jpeg --output out.pdf
```

# Music
- compute replaygain
```shell
pip3 install rgain3
replaygain --no-album *.mp3
```
