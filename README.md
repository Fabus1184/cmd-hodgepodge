# cmd-hodgepodge
Collection of useful linux commands

# Table of Contents
- [Files](#Files)
- [Stream editing](#Stream editing)
- [Documents](#Documents)
- [Music](#Music)

# Files
-foreach file
```shell
find . -name "*.test" -exec testcommand {} \;
```

-file size
```shell
du -h file
```

-copy with rsync
```shell
rsync -av --progress from/ to/
```

-make tar archive
```shell
tar -czvf archive.tar.gz folder/
```

# Stream editing
-grep invert
```shell
grep -v 'test'
```

-grep regex
```shell
grep -E 'regex'
```

-replace
```shell
sed 's/a/b/g'
```

# Documents
-combine PDFs
```shell
sudo apt install poppler-utils
pdfunite a.pdf b.pdf c.pdf output.pdf
```

-Image to PDF
```shell
sudo apt install img2pdf
img2pdf in.jpeg --output out.pdf
```

# Music
-compute replaygain
```shell
pip3 install rgain3
replaygain --no-album *.mp3
```
-generate spectrogram
```shell
sudo apt install sox
sox test.mp3 -n spectrogram -o spg.png
```
