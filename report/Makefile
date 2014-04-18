# Simple makefile for Latex documents

BIN=./bin
SRC=./src

DIR=mkdir -p $(BIN)

TEX=pdflatex
PROJECT=report
TARGET=PSAR_Gallardo_Lombardet_Peneau-report

all:
	$(DIR)
	BUILDTEX= $(TEX) -output-directory $(BIN) -jobname $(TARGET) $(SRC)/$(PROJECT).tex

clean:
	rm -f $(BIN)/*
