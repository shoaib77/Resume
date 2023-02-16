### My Resume Reference.
```
https://github.com/sb2nov/resume
```

### Build using Docker
```sh
// change the Path.
docker build -t latex .
docker run --rm -i -v C:\Users\Shoaib\Documents\Resume:/data latex pdflatex Shoaib_Resume.tex
```