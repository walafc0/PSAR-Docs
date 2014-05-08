# Simple makefile for Latex documents
# Author: walafc0 <contact@walafc0.org>

BIN=./bin
SRC=./src

DIR=mkdir -p $(BIN)

TEX=pdflatex
PROJECT=oral_presentation
TARGET=oral_presentation

all:
	$(DIR)
	BUILDTEX= $(TEX) -output-directory $(BIN) -jobname $(TARGET) $(SRC)/$(PROJECT).tex

clean:
	rm -f $(BIN)/*
