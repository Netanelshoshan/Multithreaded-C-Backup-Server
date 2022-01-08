# Multithreaded-C-Backup-Server

My server can backup files up to 4GB each. (and even more if wanted)\
I wrote the client in Python and used Boost library for networking. \
\
I used cmake to compile the server.\
You can either run the Makefile or just type:\
cmake -S. -B build\
cmake --build build\
cd build\
./server
