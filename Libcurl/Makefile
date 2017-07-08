#
#
#
PROGRAMS = \
	debug

CC	= gcc

LDLIBS	+= -g -lcurl

all: $(PROGRAMS)

clean:
	@rm -rf $(PROGRAMS)

check: $(PROGRAMS)
	./debug
