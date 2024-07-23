COMPILER = clang

SOURCE_LIBS = -Ilib/

OSX_OPT = -Llib/ -framework CoreVideo -framework IOKit -framework Cocoa -framework GLUT -framework OpenGL lib/libraylib.a

OSX_OUT = -o "bin/build_mac"

CFILES = src/*.c

build_mac:
	$(COMPILER) $(CFILES) $(SOURCE_LIBS) $(OSX_OPT) $(OSX_OUT)
