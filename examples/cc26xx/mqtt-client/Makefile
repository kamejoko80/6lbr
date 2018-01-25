DEFINES+=PROJECT_CONF_H=\"project-conf.h\"

all: mqtt-client

PROJECT_SOURCEFILES += mqtt-client.c

CONTIKI_WITH_IPV6 = 1

# REST Engine shall use mqtt implementation
APPS += mqtt

CONTIKI=../../..
include $(CONTIKI)/Makefile.include
