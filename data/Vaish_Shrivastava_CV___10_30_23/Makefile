PDFLATEX ?= pdflatex
BUILD_DIR := build
CV := ../Vaishnavi_Shrivastava_CV.pdf
UNNUMBERED_CV := ../Vaishnavi_Shrivastava_CV_unnumbered.pdf

.PHONY: all unnumbered clean
all: $(CV) $(UNNUMBERED_CV)

unnumbered: $(UNNUMBERED_CV)

$(CV): main.tex templates/resume.cls Makefile
	mkdir -p $(BUILD_DIR)
	$(PDFLATEX) -interaction=nonstopmode -halt-on-error -file-line-error -output-directory=$(BUILD_DIR) main.tex
	cp $(BUILD_DIR)/main.pdf $(CV)

$(UNNUMBERED_CV): unnumbered.tex main.tex templates/resume.cls Makefile
	mkdir -p $(BUILD_DIR)
	$(PDFLATEX) -interaction=nonstopmode -halt-on-error -file-line-error -output-directory=$(BUILD_DIR) unnumbered.tex
	cp $(BUILD_DIR)/unnumbered.pdf $(UNNUMBERED_CV)

clean:
	rm -rf $(BUILD_DIR)
