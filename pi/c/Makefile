FC=gcc
CFLAGS=-O3
EXE=pi.x
SRC=pi.c
OBJ=pi.o

all: $(EXE)

$(EXE): $(OBJ)
	$(FC) $(CFLAGS) $(OBJ) -o $(EXE)

$(OBJ): $(SRC)
	$(FC) $(CFLAGS) -c $< -o $@

clean:
	rm -f *.o $(EXE)
