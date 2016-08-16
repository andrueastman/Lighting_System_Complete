F?=nothing
OUTPUT_DIR = Output

#all
all: outputdir pdf
#create directory for output
outputdir:
	$(shell mkdir $(OUTPUT_DIR) 2>/dev/null)

#generate pdf output
pdf:
	pdflatex --output-directory=$(OUTPUT_DIR) $F
