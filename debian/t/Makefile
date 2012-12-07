CFLAGS	+= -I.
CXFLAGS	+= -I.

compiletest:
	$(CC) $(CFLAGS) -c opencl_h.c
	$(CXX) $(CXXFLAGS) -c opencl_h.cpp
	$(CXX) $(CXXFLAGS) -c cl_hpp.cpp

clean:
	$(RM) *.o
