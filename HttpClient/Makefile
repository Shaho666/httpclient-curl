CC=g++
CXX_FLAGS=-std=c++11

INCLUDE_DIR=E:/curl/curl/include
LIB_DIR=E:/curl/curl/lib
LIBS=-lcurl -lwldap32 -lws2_32
CXX_DEFINES=-DCURL_STATICLIB

main.exe:main.cpp HttpClient.cpp
	$(CC) $(CXX_FLAGS) -o $@ $^ -I$(INCLUDE_DIR) -L$(LIB_DIR) $(LIBS) $(CXX_DEFINES)

# HttpClient.o:HttpClient.cpp
# 	$(CC) $(CXX_FLAGS) -c $^ -I$(INCLUDE_DIR)

.PHONY clean:
clean:
	del *.o
	del *.gch
	del *.exe