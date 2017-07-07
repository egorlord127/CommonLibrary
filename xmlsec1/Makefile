#
#
#
PROGRAMS = \
	verify3

CC	= gcc
CFLAGS	+= -g $(shell xmlsec1-config --cflags) -DUNIX_SOCKETS
LDLIBS	+= -g $(shell xmlsec1-config --libs)

all: $(PROGRAMS)

clean:
	@rm -rf $(PROGRAMS)

check: $(PROGRAMS)
	./verify3  sign-res.xml  public.pem
