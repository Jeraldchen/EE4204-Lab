# Define compiler
CC = gcc

# Define target executables
SERVER = tcp_ser4
CLIENT = tcp_client4

# Define source files
SERVER_SRC = tcp_ser4.c
CLIENT_SRC = tcp_client4.c

# Rule to build all targets
all: $(SERVER) $(CLIENT)

# Rule to build server
$(SERVER): $(SERVER_SRC)
	$(CC) -o $(SERVER) $(SERVER_SRC)

# Rule to build client
$(CLIENT): $(CLIENT_SRC)
	$(CC) -o $(CLIENT) $(CLIENT_SRC)

# Rule to clean all targets
clean:
	rm -f $(SERVER) $(CLIENT)