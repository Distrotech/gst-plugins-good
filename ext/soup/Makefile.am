plugin_LTLIBRARIES = libgstsouphttpsrc.la

libgstsouphttpsrc_la_SOURCES = gstsouphttpsrc.c gstsouphttpclientsink.c gstsoup.c

libgstsouphttpsrc_la_CFLAGS = $(GST_PLUGINS_BASE_CFLAGS) $(GST_BASE_CFLAGS) $(GST_CFLAGS) $(SOUP_CFLAGS) 
libgstsouphttpsrc_la_LIBADD = $(GST_PLUGINS_BASE_LIBS) -lgsttag-@GST_API_VERSION@ $(GST_BASE_LIBS) $(SOUP_LIBS)
libgstsouphttpsrc_la_LDFLAGS = $(GST_PLUGIN_LDFLAGS)
libgstsouphttpsrc_la_LIBTOOLFLAGS = $(GST_PLUGIN_LIBTOOLFLAGS)

noinst_HEADERS = gstsouphttpsrc.h gstsouphttpclientsink.h
