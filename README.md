# falseSharing
Performance hit due to false sharing in parallel computing


This repository contains a C file which gives the computation time differences between two scenarios : parallel processing with false sharing and parallel processing without false sharing.

You need gcc to compile the code:<br>
$gcc -pthread -o parallelComputing parallelComputing.c

Run the code:<br>
$./parallelComputing.c

<b> For explanation on false sharing and the code refer my blog : https://parallelcomputing2017.wordpress.com/2017/03/17/understanding-false-sharing/ <b>

