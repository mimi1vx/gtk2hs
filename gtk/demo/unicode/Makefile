
PROG  = arabic
SOURCES = Arabic.hs

$(PROG) : $(SOURCES)
	$(HC) --make $< -o $@ $(HCFLAGS)

clean:
	rm -f $(SOURCES:.hs=.hi) $(SOURCES:.hs=.o) $(PROG)

HC=ghc
