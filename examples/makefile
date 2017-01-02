# Include configuration file

include config.mk

EXES= example1 example2
#-----------------------------------------------------------------------
# Main targets 

all: $(EXES) 

clean:
	rm -f $(EXES) 
#-----------------------------------------------------------------------
DEFINES=
INCLUDES=-I ../

%:%.cpp
	$(CXX) $(CPPFLAGS) $(CXXFLAGS) $(INCLUDES) $(DEFINES) -o $@ $<
#-----------------------------------------------------------------------
