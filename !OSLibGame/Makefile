CC = gcc
CFLAGS = -mlibscl -IOSLib: -std=c99 -Wall -Wextra -pedantic
LD = gcc
LDFLAGS = -mlibscl 
LIBS = -LOSLib: -lOSLib32
OBJS = main.o logger.o
RM = delete                 

application: $(OBJS)
	$(LD) $(LDFLAGS) -o $@ $^ $(LIBS)

%.o: %.c
	$(CC) $(CFLAGS) -c -o $@ $<

clean:           
	$(RM) o.logger
	$(RM) o.main
	$(RM) application

#	$(RM) $(OBJS)
#	$(RM) application
