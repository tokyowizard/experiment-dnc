#
# Makefile for dnc
#

CLEANFILES	 = dnc
CFLAGS		+= -O2 -Werror -Wall -Wextra -m64 -fno-omit-frame-pointer
LDFLAGS		+= -lnsl

dnc: dnc.c
	$(CC) -o $@ $(CPPFLAGS) $(CFLAGS) $(LDFLAGS) $^

clean:
	rm -f $(CLEANFILES)
