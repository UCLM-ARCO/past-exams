P1=$(patsubst ../../%, ./%, $(wildcard ../../redes-2_*_P1*.pdf))

all: $(P1)

%.pdf: ../../%.pdf
	ln -s $< $@
