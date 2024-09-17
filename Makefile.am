AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = helloworld
helloworld_SOURCES = main.c func.c
include_HEADERS = header.h
tmp_files = autom4te.cache compile config.log config.status configure depcomp .deps helloworld Makefile.in Makefile aclocal.m4 install-sh missing
clean-all:
	$(RM) -rf $(DESTDIR)$(bindir)/helloworld $(DESTDIR)$(includedir)/header.h
	$(RM) -rf *.o
	$(RM) -rf $(tmp_files)
