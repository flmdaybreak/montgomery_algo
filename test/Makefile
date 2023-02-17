CC=nvcc
LDFLAGS=-lpthread -lgtest -lgmock -lgtest_main -L/usr/lib
INCLUDE=-I /usr/local/include/gtest -I include/ -I ../

all: Test

Test: test.cu
	$(CC) test.cu -o test $(LDFLAGS) $(INCLUDE)

clean:
	rm -rf *.o *~ *.h test