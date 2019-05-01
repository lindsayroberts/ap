# Writing Problem: Everyday Algorithms

**tl;dr**

Write up algorithms to exhaustively describe in text and pseudocode, steps to brush one’s teeth, eat an orange, and something you do everyday.

## Academic Honesty

This course’s philosophy on academic honesty is best stated as "be reasonable." The course recognizes that interactions with classmates and others can facilitate mastery of the course’s material. However, there remains a line between enlisting the help of another and submitting the work of another. This policy characterizes both sides of that line.

The essence of all work that you submit to this course must be your own. Collaboration on problems is not permitted (unless explicitly stated otherwise) except to the extent that you may ask classmates and others for help so long as that help does not reduce to another doing your work for you. Generally speaking, when asking for help, you may show your code or writing to others, but you may not view theirs, so long as you and they respect this policy’s other constraints. Collaboration on quizzes and tests is not permitted at all. Collaboration on the final project for College Board is permitted to the extent prescribed by its specification.

## Assessment
Your work on this writing problem will be evaluated along three axes primarily.

*Correctness* To what extent does your submission align with the requirements of the specification?

*Design* To what extent is your submission written well (i.e., clearly, efficiently, elegantly, and/or logically)?

*Style* To what extent is your submission readable (i.e., thoughtfully organized, coherent, words properly spelled)?

To obtain a passing grade in this course, all students must ordinarily submit all assigned problems unless granted an exception in writing by the instructor.

## Step 1: Watch This.
Let’s start off by watching David’s video (from Ted-ED) on Algorithms.

<iframe width="913" height="514" src="https://www.youtube.com/embed/6hfOvs8pY1k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

As we see from that video, algorithms are sets of instructions for completing a task step-by-step. Sometimes these algorithms can be quite simple. One way to express an algorithm for deciding how to dress based on the weather might be to say something like this.

Look out the window. If it is raining outside, put on your rain boots and raincoat. Then go outside.
Sometimes they can be a bit more complex. Dropbox, if unfamiliar, is a service that provides storage of files "in the cloud"—on physical machines that are not your own but rather are typically owned by a hosting company—and delivers those files to you via the Internet. It also can synchronize your files between all machines on which you’ve installed the Dropbox client and has a web interface for downloading your synchronized files, which is handier than e-mailing yourself a copy of the file you worked on at school so you can continue working on that same file at home.

As the company began to grow and have many users, Dropbox needed many more file servers and a way to organize their millions of users and their billions of files across those servers. As computer scientists might say, they had to develop algorithms for dealing with issues of chunking and sharding:
