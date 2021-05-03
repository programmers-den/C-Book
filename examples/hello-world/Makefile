CFLAGS=--std=c99 -Wall -Werror -Wextra -Wpedantic --pedantic -O2

all: build

build: hello-world.o
	$(CC) $(CFLAGS) -o hello-world $^

clean:
	rm -vf ./*.o
	rm -vf ./hello-world
