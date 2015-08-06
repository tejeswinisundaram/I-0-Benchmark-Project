# I-0-Benchmark-Project
I/O Bench-marking using the fio command in Linux

****************************************
README FILE FOR I/O Benchmarking Project
****************************************

The following folder consists of the following files :

1) lscpu.txt

	*This txt file consists of the lscpu command on the Host Laptop. It provides details of the no of cores, threads, sockets, cache size  	           etc.

2) lstopo.png

	*This image is a screenhot of the graphical representation of the topology of the architecture.

3) The .txt files named 

	*1M-read.txt
	*1M-write.txt
	*10M-read.txt
	*10M-write.txt 
	*100M-read.txt
	*100M-write.txt
	*1G-read.txt
	*1G-write.txt
	*10G-read.txt
	*10G-write.txt 

	are the results of the running *fio command* for ONE CORE for the respective file size represented as the prefix of the filename.

4)The .txt files named 

	*1M-read-t2.txt
	*1M-write-t2.txt
	*10M-read-t2.txt
	*10M-write-t2.txt 
	*100M-read-t2.txt
	*100M-write-t2.txt
	*1G-read-t2.txt
	*1G-write-t2.txt
	*10G-read-t2.txt
	*10G-write-t2.txt 

	are the results of the running *fio command* for TWO CORES for the respective file size represented as the prefix of the filename.

5) The worksheet "I_O benchmark .xlsx" contains a chart of runtime and bandwith for 1 core and 2 core for the different file sizes.

6) The image "1core.png" is a graph of KB/s versus File Size for sequential read and sequential write on 1 core.

7) The image "2core.png" is a graph of KB/s versus File Size for sequential read and sequential write on 2 cores.

