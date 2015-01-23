FLAGS=`pkg-config --cflags --libs libdrm`
FLAGS+=-Wall -O0 -g

all:
	$(CC) -o modeset modeset.c $(FLAGS)
	$(CC) -o modeset-double-buffered modeset-double-buffered.c $(FLAGS)
	$(CC) -o modeset-vsync modeset-vsync.c $(FLAGS)
