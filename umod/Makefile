lib%.so: lib%.o
	$(CC) -shared -fPIC -o $@ $^;
lib%.o: lib%.c
	$(CC) ${CFLAGS} -D_INIT=lib$*_init -fPIC -c -o $@ $<;
