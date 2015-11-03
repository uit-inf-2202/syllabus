---
layout: default
---

## Administrative information

Administrative course information is available [here](https://uit.no/studietilbud/emner/emne?p_document_id=408051)

We use the [inf-2202-f15@list.uit.no](https://list.uit.no/sympa/info/inf-2202-f15) mailing list to send important information.

We have the following rooms and hours:

- Tuesdays 14:15-16:00, A016.
- Thursdays 14:15-16:00, 2.019AUD (Teknobygget).
- Fridays 10:15-11:00, A016. (We will not usually use this hour)

## Staff

- Lars Ailo Bongo (larsab@cs.uit.no), Office: A259
- Ibrahim Umar (ibrahim.umar@uit.no), Office: A238

## Lecture plan

| Lecture 	| Date		| Subject	| Lecturer |
|-----------|-----------|-----------|----------|
| L1  | Fri 14.08 | [Introduction](lectures/01-introduction.pptx) | Lars Ailo |
| L2  | Thu 20.08 | [Threads and synchronization primitives](lectures/02-threads-synchronization.pptx)	| Lars Ailo |
| L3  | Thu 27.08 | Guest lecture: [Go](lectures/03-Go-Language.pdf)	| Giacomo Tartari |
| L4  | Thu 03.09 | [Parallel architectures](lectures/04-hardware-system.pptx)	| Lars Ailo |
| L5  | Thu 10.09 | [Parallel programs](lectures/05-parallel-programs.pptx) | Lars Ailo |
| L6  | Tue 15.09 | [Programming for performance](lectures/06-programming-for-performance.pptx)	| Lars Ailo |
| L7  | Thu 24.09 | [Performance evaluation](lectures/07-performance-evaluation.pptx) | Lars Ailo |
| L8  | Thu 01.10 | [Parallel program performance evaluation](lectures/08-parallel-program-performance.pptx) | Lars Ailo |
|     | Thu 08.10 | Postponed due to a major water leak!	| - |
| L10 | Thu 15.10 | Guest lecture: Scala and Spark			| Inge Alexander Raknes |
| L9  | Thu 22.10 | [Data-intensive computing](lectures/10-data-intensive-computing.pptx) | Lars Ailo |
| L11 | Thu 29.10 | [Spark libraries](lectures/11-spark-libraries.pptx) | Lars Ailo |
|     | Thu 05.11 | Cancelled 	| Lars Ailo |
| L12 | Tue 10.11 or Thu 12.11 | Guest lecture | ? |
| L13 | Tue 17.11 | Summary	| Lars Ailo |
|     | Thu 26.11 | Exam | - |

## Readings

All lecture noets are **Mandatory**, and in addition unless otherwise noted:

1. Introduction
	* None
2. Threads and synchronization primitives (operating systems course recap):
	* Modern operating systems, 3ed, Andrew S. Tanenbaum. Prentice Hall. 2007. Chapters: 2.2, 2.3, 2.5, 10.3, 11.4
	* Alternative to MOS: another operating systems textbook: the chapters about threading, IPC mechanisms, and classical IPC problems.
3. Go
	* Rob Pike. [SPLASH keynote talk](http://talks.golang.org/2012/splash.article)
	* [A tour of Go](http://tour.golang.org/)
	* [How to write Go code](http://golang.org/doc/code.html)
	* [Effective Go](http://golang.org/doc/effective_go.html)
	* Go concurrency patterns ([video](http://www.youtube.com/watch?v=f6kdp27TYZs), [slides](http://talks.golang.org/2012/concurrency.slide#1))
	* Advanced Go concurrecny patterns ([video](https://www.youtube.com/watch?v=QDDwwePbDtw), [slides](http://talks.golang.org/2013/advconc.slide#1))
4. Parallel architectures
	* Computer Organization and Design: the Hardware/Software Interface, 4ed. David A. Patterson, John L. Hennessy. Morgan Kaufmann. 2011. Chapter 8: “Multicores, Multiprocessors, and Clusters”.
5.	Parallel programs
	* None
6. Programming for performance
	* None
7.	Performance evaluation
	* None
8.	Parallel performance evaluation
	* [Amdahl’s law](http://dl.acm.org/citation.cfm?id=1465560)
	* [Gustafson’s law](http://dl.acm.org/citation.cfm?id=42415)
	* [Debunking the 100X GPU vs. CPU myth: an evaluation of throughput computing on CPU and GPU](http://dl.acm.org/citation.cfm?id=1816021) or [Can traditional programming bridge the ninja performance gap for parallel computing applications?](http://dl.acm.org/citation.cfm?id=2766485.2742910)
9.	Data-intensive computing
	* "Jim Gray on eScience", and chapters 1 and 2 from The Fourth Paradigm: Data-Intensive Scientific Discovery. Edited by Tony Hey, Stewart Tansley, and Kristin Tolle. 2010.
	* Optional: [Google File System paper](research.google.com/archive/gfs-sosp2003.pdf)
	* Optional: [MapReduce paper](http://cacm.acm.org/magazines/2010/1/55744-mapreduce-a-flexible-data-processing-tool/fulltext)
	* Optional: [Exascale Computing and Big Data](http://cacm.acm.org/magazines/2015/7/188732-exascale-computing-and-big-data/fulltext)
10. Scala and Spark
	* None
11. Spark libraries
	* Optional: videos, slides, and research papers at: http://spark.apache.org/documentation.html

The following are suggested **additional readings**:

* Parallel Computer Architecture: A Hardware/Software Approach. David Culler, J.P. Singh, Anoop Gupta. Morgan Kaufmann. 1998.
	* This book has a great introduction to parallel programming.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.
* The Art of Computer Systems Performance Analysis: Techniques for Experimental Design, Measurement, Simulation, and Modeling. R. K. Jain. Wiley. 1991.
	* A very good book about performance analysis.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.
* Computer Architecture, Fifth Edition: A Quantitative Approach, 5ed. John L. Hennessy, David A. Patterson. Morgan Kaufmann. 2011.
	* This book has a throughout description of different parallel architectures.
	* You can purchase this book from your favorite bookstore.
* The Fourth Paradigm: Data-Intensive Scientific Discovery. Edited by Tony Hey, Stewart Tansley, and Kristin Tolle. 2010.
	* This collection of essays describe many of the opportunities and challenges for data-intensive computing in different scientific fields.
	* The book is freely available as an ebook.
* Hadoop: The Definitive Guide, 3ed. Tom White. O’Reilly. 2012.
	* Nice overview of the Hadoop ecosystem, included detailed description of HDFS and hadoop MapReduce.
	* This book is available in the library as a Safari ebook.
* HBase: The Definitive Guide. Lars George. O’Reilly. 2012.
	* Detailed description of HBase included tips for tuning the system.
	* This book is available in the library as a Safari ebook.
* Learning Spark. Holden Karau, Andy Konwinski, Patrick Wendell, Matei Zaharia. O’Reilly. 2015.
* Advanced Analytics with Spark. Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills. O’Reilly. 2015.

## Mandatory assignments

| Project |	Start      | Due     | Subject | Lecturer |
|---------|------------|---------|----------|---------|
| P1 	  | 18.08.15   | 14.09.15 | Concurrent B+ trees ([repository](https://github.com/uit-inf-2202/assignment-1)) and ([public zip](assignments/assignment-1.zip)) | Ibrahim |
| P2	  | 17.09.15   | 12.10.15 | Deduplication ([repository](https://github.com/uit-inf-2202/assignment-2) and [public zip](assignments/assignment-2.zip)) | Ibrahim |
| P3      | 13.10.15   | 06.11.15 | PageRank using Spark on AWS ([repository](https://github.com/uit-inf-2202/assignment-3)) | Lars Ailo and Ibrahim |

Note! The mandatory assignment text and pre-code are available in private repositories accessible only for the members of the uit-inf-2202 github organization. 

## Exercises

1. Introduction
	1.  None
2. Threads and synchronization primitives
	1. Compare the overhead of forking a process vs. creating a Pthread
	2. Compare the overhead of forking a process vs. creating a Python thread
	3. Implement a solution the following classical IPC problems using pthreads/Python threads and semaphores/condition variables. Note that you also need to generate a use case, test data, and useful output:
		1. Producer/ consumer
		2. Reader/ writer
		3. Sleeping barber
		4. Dining philosophers
	4. Modify the code in 3) to use message passing.
3. Go
	1. [Take a tour of Go](http://tour.golang.org/welcome/1)
	2. Implement the classical IPC problems in exercise 2.3. in Go.
4. Parallel architectures
	1. None
5. Parallel programs
	1. Implement a simpliefied BLAST search program in Go that does similarity search on two lists of random DNA sequences.
	2. Implement a heat distribution program using Pthreads or (/and) Go.
6. Programming for performance
	1. Implement a tuple space in Python with semantics similar to Linda. Use your tuple space to implement a parallel version of Mandelbrot that uses dynamic assignment (pool of tasks).
7. Performance evaluation
	* None
8. Parallel program performance evaluation
	*  Go through either the [debunking](http://dl.acm.org/citation.cfm?id=1816021) or [ninja](http://dl.acm.org/citation.cfm?id=2766485.2742910) paper and find out how they did each of the “Steps for a performance evaluation study”.
9.	Data-intensive computing
	* Create an account at AWS and calculate the approximate cost for analyzing 1TB and 1PB of data.
	* Implement word count in MapReduce and run it on uvrocks or AWS.
	* Implement grep in MapReduce and run it on uvrocks or AWS.
10.	Scala and Spark
	* Run the provided WordCount in assignment 3 on AWS
	* Implement grep in Scala and run it on AWS
11. Scala libraries
	* Refactor your assignment 3 code to use GraphX


