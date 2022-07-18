include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_event_kafka

mod_LTLIBRARIES = mod_event_kafka.la
mod_event_kafka_la_SOURCES  = mod_event_kafka.cpp
mod_event_kafka_la_CFLAGS   = $(AM_CFLAGS)
mod_event_kafka_la_CPPFLAGS = $(CURL_CFLAGS) $(AM_CPPFLAGS)
mod_event_kafka_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_event_kafka_la_LDFLAGS  = $(CURL_LIBS) -avoid-version -module -no-undefined -shared
