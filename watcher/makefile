OBJECTS = main.o communicator.o status.o operation.o sys_helper.o path.o converter.o
SHARED = ../shared
VPATH = $(SHARED)
CXXFLAGS = -std=c++11 -I$(SHARED)
EXENAME = sswatcher

$(EXENAME): $(OBJECTS)
	$(CXX) $^ -o $@

.PHONY: clean

clean:
	-rm $(OBJECTS)
