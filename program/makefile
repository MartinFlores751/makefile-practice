objects = main.o proto.o


final : $(objects)
	g++ -o final $(objects)

main.o : proto.h
proto.o : proto.h

.PHONY : clean
clean :
	-rm final $(objects)
