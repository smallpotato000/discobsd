#
# Copyright (c) 1987 Regents of the University of California.
# All rights reserved.
#
# Redistribution and use in source and binary forms are permitted
# provided that the above copyright notice and this paragraph are
# duplicated in all such forms and that any documentation,
# advertising materials, and other materials related to such
# distribution and use acknowledge that the software was developed
# by the University of California, Berkeley.  The name of the
# University may not be used to endorse or promote products derived
# from this software without specific prior written permission.
# THIS SOFTWARE IS PROVIDED ``AS IS'' AND WITHOUT ANY EXPRESS OR
# IMPLIED WARRANTIES, INCLUDING, WITHOUT LIMITATION, THE IMPLIED
# WARRANTIES OF MERCHANTIBILITY AND FITNESS FOR A PARTICULAR PURPOSE.
#
#	@(#)Makefile	5.4.15 (2.11BSD) 1997/12/8
#
TOPSRC!=cd ../../..; pwd
include ${TOPSRC}/share/mk/sys.mk

MDIR=	/usr/share/man/cat3
SRCS1=	abort.3 abs.3 alarm.3 asinh.3 assert.3 atof.3 \
	basename.3 bstring.3 byteorder.3 \
	compat-sys5.3 crypt.3 ctime.3 ctype.3 curses.3 dbm.3 daemon.3 \
	devname.3 directory.3 dirname.3 \
	ecvt.3 end.3 erf.3 err.3 execl.3 exit.3 \
	exp.3 fclose.3 ferror.3 floor.3 \
	fopen.3 fread.3 frexp.3 fseek.3 getc.3 getdisk.3 getenv.3 getfsent.3 \
	getgrent.3 gethostbyname.3 getnetent.3 getopt.3 getpass.3 \
	getgrouplist.3 getloadavg.3 getmntinfo.3 getsubopt.3 \
	getprotoent.3 getpwent.3 gets.3 getservent.3 getttyent.3 \
	getusershell.3 getwd.3 hypot.3 ieee.3 inet.3 infnan.3 initgroups.3
SRCS2=	insque.3 intro.3 j0.3 l3tol.3 ldfps.3 lgamma.3 lib2648.3 \
	malloc.3 math.3 mktemp.3 monitor.3 mp.3 ndbm.3 nice.3 nlist.3 ns.3 \
	pause.3 perror.3 plot.3 popen.3 printf.3 psignal.3 putc.3 puts.3 \
	qsort.3 rand.3 random.3 rcmd.3 regex.3 resolver.3 rexec.3 scandir.3 \
	scanf.3 setbuf.3 setjmp.3 siginterrupt.3 signal.3 sin.3 \
	sinh.3 sleep.3 sqrt.3 stdio.3 strftime.3 string.3 strtok.3 stty.3 \
	setmode.3 setruid.3 sigsetops.3 \
	strcspn.3 strlcpy.3 strpbrk.3 \
	strsep.3 strspn.3 strtol.3 strtoul.3 strstr.3 \
	swab.3 sysctl.3 syslog.3 \
	system.3 termcap.3 time.3 times.3 ttyname.3 ualarm.3 uname.3 ungetc.3 \
	syserrlst.3 \
	utime.3 valloc.3 varargs.3
OBJS1=	abort.0 abs.0 alarm.0 asinh.0 assert.0 atof.0 \
	basename.0 bstring.0 byteorder.0 \
	compat-sys5.0 crypt.0 ctime.0 ctype.0 curses.0 dbm.0 daemon.0 \
	devname.0 directory.0 dirname.0 \
	ecvt.0 end.0 erf.0 err.0 execl.0 exit.0 \
	exp.0 fclose.0 ferror.0 floor.0 \
	fopen.0 fread.0 frexp.0 fseek.0 getc.0 getdisk.0 getenv.0 getfsent.0 \
	getgrent.0 gethostbyname.0 getnetent.0 getopt.0 getpass.0 \
	getprotoent.0 getpwent.0 gets.0 getservent.0 getttyent.0 \
	getgrouplist.0 getloadavg.0 getmntinfo.0 getsubopt.0 \
	getusershell.0 getwd.0 hypot.0 ieee.0 inet.0 infnan.0 initgroups.0
OBJS2=	insque.0 intro.0 j0.0 l3tol.0 ldfps.0 lgamma.0 lib2648.0 \
	malloc.0 math.0 mktemp.0 monitor.0 mp.0 ndbm.0 nice.0 nlist.0 ns.0 \
	pause.0 perror.0 plot.0 popen.0 printf.0 psignal.0 putc.0 puts.0 \
	qsort.0 rand.0 random.0 rcmd.0 regex.0 resolver.0 rexec.0 scandir.0 \
	scanf.0 setbuf.0 setjmp.0 siginterrupt.0 signal.0 sin.0 \
	sinh.0 sleep.0 sqrt.0 stdio.0 strftime.0 string.0 strtok.0 stty.0 \
	setmode.0 setruid.0 sigsetops.0 \
	strcspn.0 strlcpy.0 strpbrk.0 \
	strsep.0 strspn.0 strtol.0 strtoul.0 strstr.0 \
	swab.0 sysctl.0 syslog.0 \
	system.0 termcap.0 time.0 times.0 ttyname.0 ualarm.0 uname.0 ungetc.0 \
	syserrlst.0 \
	utime.0 valloc.0 varargs.0
REMO1=	edata.0 etext.0 j1.0 jn.0 ns_addr.0 ns_ntoa.0 y0.0 y1.0 yn.0 acos.0 \
	asin.0 atan.0 atan2.0 atoi.0 atol.0 cos.0 dbm_clearerr.0 dbm_close.0 \
	dbm_delete.0 dbm_error.0 dbm_fetch.0 dbm_firstkey.0 dbm_nextkey.0 \
	dbm_open.0 dbm_store.0 dbminit.0 delete.0 erfc.0 expm1.0 fcvt.0 \
	fetch.0 firstkey.0 gcvt.0 log.0 log10.0 log1p.0 nextkey.0 pow.0 \
	rresvport.0 ruserok.0 store.0 tan.0 addr.0 arc.0 asctime.0 cbrt.0 \
	circle.0 comp.0 cont.0 copysign.0 cosh.0 drem.0 encrypt.0 environ.0 \
	erase.0 execle.0 execlp.0 exect.0 execv.0 execve.0 execvp.0 fgetc.0 \
	fgets.0 finite.0 fputc.0 fputs.0 ftime.0 getchar.0 getw.0 gmtime.0 \
	gtty.0 inet_addr.0 inet_lnaof.0 inet_makeaddr.0 inet_netof.0 \
	inet_network.0 inet_ntoa.0 isalnum.0 isalpha.0 isascii.0 iscntrl.0 \
	isdigit.0 islower.0 isprint.0 ispunct.0 isspace.0 isupper.0 \
	isxdigit.0 label.0 ldexp.0 line.0 linemod.0 localtime.0 logb.0 modf.0 \
	move.0 network.0 ntoa.0 openpl.0 pclose.0 point.0 putchar.0 putw.0
REMO2=	re_comp.0 re_exec.0 scalb.0 setkey.0 space.0 srand.0 tanh.0 \
	timezone.0 toascii.0 tolower.0 toupper.0 ltol3.0 _longjmp.0 \
	_setjmp.0 acosh.0 alloca.0 atanh.0 cabs.0 calloc.0 ceil.0 \
	closelog.0 fabs.0 fdopen.0 free.0 freopen.0 fscanf.0 \
	ftell.0 fwrite.0 index.0 initstate.0 longjmp.0 mkstemp.0 openlog.0  \
	realloc.0 remque.0 rewind.0 rindex.0 rint.0 \
	setlogmask.0 setstate.0 setrgid.0 srandom.0 \
	sscanf.0 strcat.0 strcmp.0 strcpy.0 strlen.0 strncat.0 strncmp.0 \
	strncpy.0 strcasecmp.0 strncasecmp.0 \
	strerror.0 \
	sprintf.0 vfprintf.0 vprintf.0 vsprintf.0 alphasort.0 bcmp.0 bcopy.0 \
	bzero.0 clearerr.0 feof.0 fflush.0 ffs.0 fileno.0 fprintf.0 gamma.0  \
	getdiskbyname.0 isatty.0 moncontrol.0 monstartup.0 setbuffer.0 \
	setlinebuf.0 setvbuf.0 sys_siglist.0 ttyslot.0 endfsent.0 endgrent.0 \
	endpwent.0 getfsfile.0 getfsspec.0 getfstype.0 getgrgid.0

REMO3=	getgrnam.0 getpwnam.0 getpwuid.0 setfsent.0 setgrent.0 setpwent.0 \
	setpwfile.0 tgetent.0 tgetflag.0 tgetnum.0 tgetstr.0 tgoto.0 tputs.0 \
	closedir.0 endttyent.0 getttynam.0 opendir.0 readdir.0 rewinddir.0 \
	seekdir.0 setttyent.0 telldir.0 endnetent.0 getnetbyaddr.0 \
	getnetbyname.0 htonl.0 htons.0 ntohl.0 ntohs.0 setnetent.0 \
	endservent.0 getservbyname.0 getservbyport.0 setservent.0 \
	endprotoent.0 endusershell.0 getprotobyname.0 getprotobynumber.0 \
	setprotoent.0 setusershell.0 endhostent.0 gethostbyaddr.0 gethostent.0 \
	sethostent.0 sethostfile.0 memccpy.0 memchr.0 memcmp.0 memcpy.0 \
	memset.0 strchr.0 strrchr.0 tmpnam.0 tmpfile.0 \
	tempnam.0 getmode.0 usleep.0 setenv.0 unsetenv.0

REMO4=	verr.0 errx.0 verrx.0 warn.0 warnx.0 vwarnx.0

REMO5 = sigaddset.0 sigdelset.0 sigemptyset.0 sigfillset.0 sigismember.0

.SUFFIXES: .3 .0

.3.0:
	${MANROFF} $*.3 > $*.0

all: _make_01 _make_02

_make_01: ${OBJS1}

_make_02: ${OBJS2}

clean: FRC
	rm -f ${OBJS1}
	rm -f ${OBJS2}

install: _make_01 _make_02
	cp ${OBJS1} ${DESTDIR}${MDIR}
	cp ${OBJS2} ${DESTDIR}${MDIR}
	for i in ${REMO4}; do \
		ln -f ${DESTDIR}/${MDIR}/err.0 ${DESTDIR}${MDIR}/$$i; \
	done
	for i in ${REMO5}; do \
		ln -f ${DESTDIR}/${MDIR}/sigsetops.0 ${DESTDIR}${MDIR}/$$i; \
	done

	ln -f ${DESTDIR}${MDIR}/end.0 ${DESTDIR}${MDIR}/edata.0
	ln -f ${DESTDIR}${MDIR}/end.0 ${DESTDIR}${MDIR}/etext.0
	ln -f ${DESTDIR}${MDIR}/j0.0 ${DESTDIR}${MDIR}/j1.0
	ln -f ${DESTDIR}${MDIR}/j0.0 ${DESTDIR}${MDIR}/jn.0
	ln -f ${DESTDIR}${MDIR}/ns.0 ${DESTDIR}${MDIR}/ns_addr.0
	ln -f ${DESTDIR}${MDIR}/ns.0 ${DESTDIR}${MDIR}/ns_ntoa.0
	ln -f ${DESTDIR}${MDIR}/j0.0 ${DESTDIR}${MDIR}/y0.0
	ln -f ${DESTDIR}${MDIR}/j0.0 ${DESTDIR}${MDIR}/y1.0
	ln -f ${DESTDIR}${MDIR}/j0.0 ${DESTDIR}${MDIR}/yn.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/acos.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/asin.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/atan.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/atan2.0
	ln -f ${DESTDIR}${MDIR}/atof.0 ${DESTDIR}${MDIR}/atoi.0
	ln -f ${DESTDIR}${MDIR}/atof.0 ${DESTDIR}${MDIR}/atol.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/cos.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_clearerr.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_close.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_delete.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_error.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_fetch.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_firstkey.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_nextkey.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_open.0
	ln -f ${DESTDIR}${MDIR}/ndbm.0 ${DESTDIR}${MDIR}/dbm_store.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/dbminit.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/delete.0
	ln -f ${DESTDIR}${MDIR}/erf.0 ${DESTDIR}${MDIR}/erfc.0
	ln -f ${DESTDIR}${MDIR}/exp.0 ${DESTDIR}${MDIR}/expm1.0
	ln -f ${DESTDIR}${MDIR}/ecvt.0 ${DESTDIR}${MDIR}/fcvt.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/fetch.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/firstkey.0
	ln -f ${DESTDIR}${MDIR}/ecvt.0 ${DESTDIR}${MDIR}/gcvt.0
	ln -f ${DESTDIR}${MDIR}/exp.0 ${DESTDIR}${MDIR}/log.0
	ln -f ${DESTDIR}${MDIR}/exp.0 ${DESTDIR}${MDIR}/log10.0
	ln -f ${DESTDIR}${MDIR}/exp.0 ${DESTDIR}${MDIR}/log1p.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/nextkey.0
	ln -f ${DESTDIR}${MDIR}/exp.0 ${DESTDIR}${MDIR}/pow.0
	ln -f ${DESTDIR}${MDIR}/rcmd.0 ${DESTDIR}${MDIR}/rresvport.0
	ln -f ${DESTDIR}${MDIR}/rcmd.0 ${DESTDIR}${MDIR}/ruserok.0
	ln -f ${DESTDIR}${MDIR}/dbm.0 ${DESTDIR}${MDIR}/store.0
	ln -f ${DESTDIR}${MDIR}/sin.0 ${DESTDIR}${MDIR}/tan.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/addr.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/arc.0
	ln -f ${DESTDIR}${MDIR}/ctime.0 ${DESTDIR}${MDIR}/asctime.0
	ln -f ${DESTDIR}${MDIR}/sqrt.0 ${DESTDIR}${MDIR}/cbrt.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/circle.0
	ln -f ${DESTDIR}${MDIR}/regex.0 ${DESTDIR}${MDIR}/comp.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/cont.0
	ln -f ${DESTDIR}${MDIR}/ieee.0 ${DESTDIR}${MDIR}/copysign.0
	ln -f ${DESTDIR}${MDIR}/sinh.0 ${DESTDIR}${MDIR}/cosh.0
	ln -f ${DESTDIR}${MDIR}/ieee.0 ${DESTDIR}${MDIR}/drem.0
	ln -f ${DESTDIR}${MDIR}/crypt.0 ${DESTDIR}${MDIR}/encrypt.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/environ.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/erase.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/execle.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/execlp.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/exect.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/execv.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/execve.0
	ln -f ${DESTDIR}${MDIR}/execl.0 ${DESTDIR}${MDIR}/execvp.0
	ln -f ${DESTDIR}${MDIR}/getc.0 ${DESTDIR}${MDIR}/fgetc.0
	ln -f ${DESTDIR}${MDIR}/gets.0 ${DESTDIR}${MDIR}/fgets.0
	ln -f ${DESTDIR}${MDIR}/ieee.0 ${DESTDIR}${MDIR}/finite.0
	ln -f ${DESTDIR}${MDIR}/putc.0 ${DESTDIR}${MDIR}/fputc.0
	ln -f ${DESTDIR}${MDIR}/puts.0 ${DESTDIR}${MDIR}/fputs.0
	ln -f ${DESTDIR}${MDIR}/time.0 ${DESTDIR}${MDIR}/ftime.0
	ln -f ${DESTDIR}${MDIR}/getc.0 ${DESTDIR}${MDIR}/getchar.0
	ln -f ${DESTDIR}${MDIR}/getc.0 ${DESTDIR}${MDIR}/getw.0
	ln -f ${DESTDIR}${MDIR}/ctime.0 ${DESTDIR}${MDIR}/gmtime.0
	ln -f ${DESTDIR}${MDIR}/stty.0 ${DESTDIR}${MDIR}/gtty.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_addr.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_lnaof.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_makeaddr.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_netof.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_network.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/inet_ntoa.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isalnum.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isalpha.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isascii.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/iscntrl.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isdigit.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/islower.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isprint.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/ispunct.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isspace.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isupper.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/isxdigit.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/label.0
	ln -f ${DESTDIR}${MDIR}/frexp.0 ${DESTDIR}${MDIR}/ldexp.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/line.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/linemod.0
	ln -f ${DESTDIR}${MDIR}/ctime.0 ${DESTDIR}${MDIR}/localtime.0
	ln -f ${DESTDIR}${MDIR}/ieee.0 ${DESTDIR}${MDIR}/logb.0
	ln -f ${DESTDIR}${MDIR}/frexp.0 ${DESTDIR}${MDIR}/modf.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/move.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/network.0
	ln -f ${DESTDIR}${MDIR}/inet.0 ${DESTDIR}${MDIR}/ntoa.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/openpl.0
	ln -f ${DESTDIR}${MDIR}/popen.0 ${DESTDIR}${MDIR}/pclose.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/point.0
	ln -f ${DESTDIR}${MDIR}/putc.0 ${DESTDIR}${MDIR}/putchar.0
	ln -f ${DESTDIR}${MDIR}/putc.0 ${DESTDIR}${MDIR}/putw.0
	ln -f ${DESTDIR}${MDIR}/regex.0 ${DESTDIR}${MDIR}/re_comp.0
	ln -f ${DESTDIR}${MDIR}/regex.0 ${DESTDIR}${MDIR}/re_exec.0
	ln -f ${DESTDIR}${MDIR}/ieee.0 ${DESTDIR}${MDIR}/scalb.0
	ln -f ${DESTDIR}${MDIR}/crypt.0 ${DESTDIR}${MDIR}/setkey.0
	ln -f ${DESTDIR}${MDIR}/plot.0 ${DESTDIR}${MDIR}/space.0
	ln -f ${DESTDIR}${MDIR}/rand.0 ${DESTDIR}${MDIR}/srand.0
	ln -f ${DESTDIR}${MDIR}/sinh.0 ${DESTDIR}${MDIR}/tanh.0
	ln -f ${DESTDIR}${MDIR}/ctime.0 ${DESTDIR}${MDIR}/timezone.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/toascii.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/tolower.0
	ln -f ${DESTDIR}${MDIR}/ctype.0 ${DESTDIR}${MDIR}/toupper.0
	ln -f ${DESTDIR}${MDIR}/l3tol.0 ${DESTDIR}${MDIR}/ltol3.0
	ln -f ${DESTDIR}${MDIR}/setjmp.0 ${DESTDIR}${MDIR}/_longjmp.0
	ln -f ${DESTDIR}${MDIR}/setjmp.0 ${DESTDIR}${MDIR}/_setjmp.0
	ln -f ${DESTDIR}${MDIR}/asinh.0 ${DESTDIR}${MDIR}/acosh.0
	ln -f ${DESTDIR}${MDIR}/malloc.0 ${DESTDIR}${MDIR}/alloca.0
	ln -f ${DESTDIR}${MDIR}/asinh.0 ${DESTDIR}${MDIR}/atanh.0
	ln -f ${DESTDIR}${MDIR}/hypot.0 ${DESTDIR}${MDIR}/cabs.0
	ln -f ${DESTDIR}${MDIR}/malloc.0 ${DESTDIR}${MDIR}/calloc.0
	ln -f ${DESTDIR}${MDIR}/floor.0 ${DESTDIR}${MDIR}/ceil.0
	ln -f ${DESTDIR}${MDIR}/syslog.0 ${DESTDIR}${MDIR}/closelog.0
	ln -f ${DESTDIR}${MDIR}/perror.0 ${DESTDIR}${MDIR}/strerror.0
	ln -f ${DESTDIR}${MDIR}/floor.0 ${DESTDIR}${MDIR}/fabs.0
	ln -f ${DESTDIR}${MDIR}/fopen.0 ${DESTDIR}${MDIR}/fdopen.0
	ln -f ${DESTDIR}${MDIR}/malloc.0 ${DESTDIR}${MDIR}/free.0
	ln -f ${DESTDIR}${MDIR}/fopen.0 ${DESTDIR}${MDIR}/freopen.0
	ln -f ${DESTDIR}${MDIR}/scanf.0 ${DESTDIR}${MDIR}/fscanf.0
	ln -f ${DESTDIR}${MDIR}/fseek.0 ${DESTDIR}${MDIR}/ftell.0
	ln -f ${DESTDIR}${MDIR}/fread.0 ${DESTDIR}${MDIR}/fwrite.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/index.0
	ln -f ${DESTDIR}${MDIR}/random.0 ${DESTDIR}${MDIR}/initstate.0
	ln -f ${DESTDIR}${MDIR}/setjmp.0 ${DESTDIR}${MDIR}/longjmp.0
	ln -f ${DESTDIR}${MDIR}/mktemp.0 ${DESTDIR}${MDIR}/mkstemp.0
	ln -f ${DESTDIR}${MDIR}/syslog.0 ${DESTDIR}${MDIR}/openlog.0
	ln -f ${DESTDIR}${MDIR}/malloc.0 ${DESTDIR}${MDIR}/realloc.0
	ln -f ${DESTDIR}${MDIR}/insque.0 ${DESTDIR}${MDIR}/remque.0
	ln -f ${DESTDIR}${MDIR}/fseek.0 ${DESTDIR}${MDIR}/rewind.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/rindex.0
	ln -f ${DESTDIR}${MDIR}/floor.0 ${DESTDIR}${MDIR}/rint.0
	ln -f ${DESTDIR}${MDIR}/syslog.0 ${DESTDIR}${MDIR}/setlogmask.0
	ln -f ${DESTDIR}${MDIR}/random.0 ${DESTDIR}${MDIR}/setstate.0
	ln -f ${DESTDIR}${MDIR}/random.0 ${DESTDIR}${MDIR}/srandom.0
	ln -f ${DESTDIR}${MDIR}/scanf.0 ${DESTDIR}${MDIR}/sscanf.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strcat.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strcmp.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strcpy.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strlen.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strncat.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strncmp.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strncpy.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strcasecmp.0
	ln -f ${DESTDIR}${MDIR}/string.0 ${DESTDIR}${MDIR}/strncasecmp.0
	ln -f ${DESTDIR}${MDIR}/strlcpy.0 ${DESTDIR}${MDIR}/strlcat.0
	ln -f ${DESTDIR}${MDIR}/printf.0 ${DESTDIR}${MDIR}/sprintf.0
	ln -f ${DESTDIR}${MDIR}/printf.0 ${DESTDIR}${MDIR}/vfprintf.0
	ln -f ${DESTDIR}${MDIR}/printf.0 ${DESTDIR}${MDIR}/vprintf.0
	ln -f ${DESTDIR}${MDIR}/printf.0 ${DESTDIR}${MDIR}/vsprintf.0
	ln -f ${DESTDIR}${MDIR}/scandir.0 ${DESTDIR}${MDIR}/alphasort.0
	ln -f ${DESTDIR}${MDIR}/bstring.0 ${DESTDIR}${MDIR}/bcmp.0
	ln -f ${DESTDIR}${MDIR}/bstring.0 ${DESTDIR}${MDIR}/bcopy.0
	ln -f ${DESTDIR}${MDIR}/bstring.0 ${DESTDIR}${MDIR}/bzero.0
	ln -f ${DESTDIR}${MDIR}/ferror.0 ${DESTDIR}${MDIR}/clearerr.0
	ln -f ${DESTDIR}${MDIR}/ferror.0 ${DESTDIR}${MDIR}/feof.0
	ln -f ${DESTDIR}${MDIR}/fclose.0 ${DESTDIR}${MDIR}/fflush.0
	ln -f ${DESTDIR}${MDIR}/bstring.0 ${DESTDIR}${MDIR}/ffs.0
	ln -f ${DESTDIR}${MDIR}/ferror.0 ${DESTDIR}${MDIR}/fileno.0
	ln -f ${DESTDIR}${MDIR}/printf.0 ${DESTDIR}${MDIR}/fprintf.0
	ln -f ${DESTDIR}${MDIR}/lgamma.0 ${DESTDIR}${MDIR}/gamma.0
	ln -f ${DESTDIR}${MDIR}/getdisk.0 ${DESTDIR}${MDIR}/getdiskbyname.0
	ln -f ${DESTDIR}${MDIR}/ttyname.0 ${DESTDIR}${MDIR}/isatty.0
	ln -f ${DESTDIR}${MDIR}/monitor.0 ${DESTDIR}${MDIR}/moncontrol.0
	ln -f ${DESTDIR}${MDIR}/monitor.0 ${DESTDIR}${MDIR}/monstartup.0
	ln -f ${DESTDIR}${MDIR}/setbuf.0 ${DESTDIR}${MDIR}/setbuffer.0
	ln -f ${DESTDIR}${MDIR}/setbuf.0 ${DESTDIR}${MDIR}/setlinebuf.0
	ln -f ${DESTDIR}${MDIR}/setbuf.0 ${DESTDIR}${MDIR}/setvbuf.0
	ln -f ${DESTDIR}${MDIR}/psignal.0 ${DESTDIR}${MDIR}/sys_siglist.0
	ln -f ${DESTDIR}${MDIR}/ttyname.0 ${DESTDIR}${MDIR}/ttyslot.0
	ln -f ${DESTDIR}${MDIR}/getfsent.0 ${DESTDIR}${MDIR}/endfsent.0
	ln -f ${DESTDIR}${MDIR}/getgrent.0 ${DESTDIR}${MDIR}/endgrent.0
	ln -f ${DESTDIR}${MDIR}/getpwent.0 ${DESTDIR}${MDIR}/endpwent.0
	ln -f ${DESTDIR}${MDIR}/getfsent.0 ${DESTDIR}${MDIR}/getfsfile.0
	ln -f ${DESTDIR}${MDIR}/getfsent.0 ${DESTDIR}${MDIR}/getfsspec.0
	ln -f ${DESTDIR}${MDIR}/getfsent.0 ${DESTDIR}${MDIR}/getfstype.0
	ln -f ${DESTDIR}${MDIR}/getgrent.0 ${DESTDIR}${MDIR}/getgrgid.0
	ln -f ${DESTDIR}${MDIR}/getgrent.0 ${DESTDIR}${MDIR}/getgrnam.0
	ln -f ${DESTDIR}${MDIR}/getpwent.0 ${DESTDIR}${MDIR}/getpwnam.0
	ln -f ${DESTDIR}${MDIR}/getpwent.0 ${DESTDIR}${MDIR}/getpwuid.0
	ln -f ${DESTDIR}${MDIR}/getfsent.0 ${DESTDIR}${MDIR}/setfsent.0
	ln -f ${DESTDIR}${MDIR}/getgrent.0 ${DESTDIR}${MDIR}/setgrent.0
	ln -f ${DESTDIR}${MDIR}/getpwent.0 ${DESTDIR}${MDIR}/setpwent.0
	ln -f ${DESTDIR}${MDIR}/getpwent.0 ${DESTDIR}${MDIR}/setpwfile.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tgetent.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tgetflag.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tgetnum.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tgetstr.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tgoto.0
	ln -f ${DESTDIR}${MDIR}/termcap.0 ${DESTDIR}${MDIR}/tputs.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/closedir.0
	ln -f ${DESTDIR}${MDIR}/getttyent.0 ${DESTDIR}${MDIR}/endttyent.0
	ln -f ${DESTDIR}${MDIR}/getttyent.0 ${DESTDIR}${MDIR}/getttynam.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/opendir.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/readdir.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/rewinddir.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/seekdir.0
	ln -f ${DESTDIR}${MDIR}/getttyent.0 ${DESTDIR}${MDIR}/setttyent.0
	ln -f ${DESTDIR}${MDIR}/directory.0 ${DESTDIR}${MDIR}/telldir.0
	ln -f ${DESTDIR}${MDIR}/getnetent.0 ${DESTDIR}${MDIR}/endnetent.0
	ln -f ${DESTDIR}${MDIR}/getnetent.0 ${DESTDIR}${MDIR}/getnetbyaddr.0
	ln -f ${DESTDIR}${MDIR}/getnetent.0 ${DESTDIR}${MDIR}/getnetbyname.0
	ln -f ${DESTDIR}${MDIR}/byteorder.0 ${DESTDIR}${MDIR}/htonl.0
	ln -f ${DESTDIR}${MDIR}/byteorder.0 ${DESTDIR}${MDIR}/htons.0
	ln -f ${DESTDIR}${MDIR}/byteorder.0 ${DESTDIR}${MDIR}/ntohl.0
	ln -f ${DESTDIR}${MDIR}/byteorder.0 ${DESTDIR}${MDIR}/ntohs.0
	ln -f ${DESTDIR}${MDIR}/getnetent.0 ${DESTDIR}${MDIR}/setnetent.0
	ln -f ${DESTDIR}${MDIR}/getservent.0 ${DESTDIR}${MDIR}/endservent.0
	ln -f ${DESTDIR}${MDIR}/getservent.0 ${DESTDIR}${MDIR}/getservbyname.0
	ln -f ${DESTDIR}${MDIR}/getservent.0 ${DESTDIR}${MDIR}/getservbyport.0
	ln -f ${DESTDIR}${MDIR}/getservent.0 ${DESTDIR}${MDIR}/setservent.0
	ln -f ${DESTDIR}${MDIR}/getprotoent.0 ${DESTDIR}${MDIR}/endprotoent.0
	ln -f ${DESTDIR}${MDIR}/getusershell.0 ${DESTDIR}${MDIR}/endusershell.0
	ln -f ${DESTDIR}${MDIR}/getprotoent.0 ${DESTDIR}${MDIR}/getprotobyname.0
	ln -f ${DESTDIR}${MDIR}/getprotoent.0 ${DESTDIR}${MDIR}/getprotobynumber.0
	ln -f ${DESTDIR}${MDIR}/getprotoent.0 ${DESTDIR}${MDIR}/setprotoent.0
	ln -f ${DESTDIR}${MDIR}/getusershell.0 ${DESTDIR}${MDIR}/setusershell.0
	ln -f ${DESTDIR}${MDIR}/gethostbyname.0 ${DESTDIR}${MDIR}/endhostent.0
	ln -f ${DESTDIR}${MDIR}/gethostbyname.0 ${DESTDIR}${MDIR}/gethostbyaddr.0
	ln -f ${DESTDIR}${MDIR}/gethostbyname.0 ${DESTDIR}${MDIR}/gethostent.0
	ln -f ${DESTDIR}${MDIR}/gethostbyname.0 ${DESTDIR}${MDIR}/sethostent.0
	ln -f ${DESTDIR}${MDIR}/gethostbyname.0 ${DESTDIR}${MDIR}/sethostfile.0
	ln -f ${DESTDIR}${MDIR}/setmode.0 ${DESTDIR}${MDIR}/getmode.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/memccpy.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/memchr.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/memcmp.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/memcpy.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/memset.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/strchr.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/strrchr.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/tmpnam.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/tmpfile.0
	ln -f ${DESTDIR}${MDIR}/compat-sys5.0 ${DESTDIR}${MDIR}/tempnam.0
	ln -f ${DESTDIR}${MDIR}/sleep.0 ${DESTDIR}${MDIR}/usleep.0
	ln -f ${DESTDIR}${MDIR}/getenv.0 ${DESTDIR}${MDIR}/setenv.0
	ln -f ${DESTDIR}${MDIR}/getenv.0 ${DESTDIR}${MDIR}/unsetenv.0
	ln -f ${DESTDIR}${MDIR}/setruid.0 ${DESTDIR}${MDIR}/setrgid.0

FRC:
