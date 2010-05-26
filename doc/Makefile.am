man8_MANS = sjconf-modules.man
DISTCLEANFILES = sjconf-modules.man
EXTRA_DIST = sjconf-modules.t2t

SUFFIXES = .t2t

.t2t.man:
	$(TXT2TAGS) -o $@ $<
