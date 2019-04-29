cd tmp/
docker run --rm -it -w=/root -v $PWD:/root eisoku9618/kuroiwa_dockefiles_for_latexmk /bin/bash -c "latexmk -pvc manuscript.tex"
open .tmp/manuscript.pdf

# Write & update tmp/manuscript.txt
