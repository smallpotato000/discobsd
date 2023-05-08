#
# Public Domain.  1995/03/13 - Steven Schultz
#
TOPSRC		= $(shell cd ../..; pwd)
include $(TOPSRC)/target.mk

# XXX CFLAGS		+= -Werror -I${TOPSRC}/sys/include
CFLAGS		+= -I${TOPSRC}/sys/include

BIN		= fdisk
SRCS            = $(BIN).c
OBJS            = $(BIN).o
MAN             = $(BIN).0

all:            $(BIN) ${MAN}

$(BIN):    ${OBJS}
		${CC} ${LDFLAGS} -o $@.elf ${OBJS} ${LIBS}
		${OBJDUMP} -S $@.elf > $@.dis
		${SIZE} $@.elf
		${ELF2AOUT} $@.elf $@

.SUFFIXES:      .0 .1

.1.0:
		${MANROFF} $*.1 > $@

clean:
		rm -f *.o *.elf ${MAN} *.elf *.dis tags *~ $(BIN)

depend:         ${SRCS}
		mkdep ${CFLAGS} ${SRCS}

install:        all
		install -m 755 $(BIN) ${DESTDIR}/sbin
		cp ${MAN} ${DESTDIR}/usr/share/man/cat8

lint:           ${SRCS}
		lint -hax ${SRCS}

tags:           ${SRCS}
		ctags ${SRCS}