
CC = /Users/nbeckman/dev/wla-dx/binaries/wla-z80
CFLAGS = -o
LD = /Users/nbeckman/dev/wla-dx/binaries/wlalink
LDFLAGS = -vds

SFILES = America.asm
IFILES = 
OFILES = America.o

all: $(OFILES) makefile
	$(LD) $(LDFLAGS) linkfile America.sms

America.o: America.asm
	$(CC) $(CFLAGS) America.asm America.o


$(OFILES): $(HFILES)


clean:
	rm -f $(OFILES) core *~ America.sms America.sym
