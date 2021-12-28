A simple resume for software developers. It uses the base latex templates and fonts.
This repository is base on [sb2nov](https://github.com/sb2nov/resume)

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex dawid_kubicki_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Dawid Kubicki.
