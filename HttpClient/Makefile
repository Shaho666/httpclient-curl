main.exe:main.cpp
	g++ -std=c++11 -o main.exe main.cpp \
	-ID:\curl\include \
	-IHttpClient.h HttpClient.cpp \
	-LD:\curl\lib \
	-lcurl -lwldap32 -lws2_32 -DCURL_STATICLIB