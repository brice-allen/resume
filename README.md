Build using Docker
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
Preview
Resume Screenshot
![BriceAllenResume](https://user-images.githubusercontent.com/71028702/228368572-1f89c5f2-0cde-45dc-9d77-b191178f7fab.png)

License
Format is MIT but all the data is owned by Brice Allen
