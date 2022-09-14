# Созданный make-file

.PHONY: all debug release clean

all: debug release

debug: KazinoRoyal-dbg

KazinoRoyal-dbg: KazinoRoyal.cpp
	g++ -g -O0 KazinoRoyal.cpp -o KazinoRoyal-dbg -Wall

release: KazinoRoyal

KazinoRoyal: KazinoRoyal.cpp
	g++ -O2 KazinoRoyal.cpp -o KazinoRoyal -DNDEBUG -Wall

clean:
	rm -f KazinoRoyal *.cpp
