CC = gcc
CFLAGS =  -std=c99 -I. -lbcm2835
DEPS = 
OBJ = Adafruit_DHT.o

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

temp: $(OBJ)
	gcc -o $@ $^ $(CFLAGS)
