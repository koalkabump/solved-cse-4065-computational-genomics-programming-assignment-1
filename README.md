Download Link: https://assignmentchef.com/product/solved-cse-4065-computational-genomics-programming-assignment-1
<br>



<strong></strong>



In this assignment, you are going to search for motifs, and try to find the consensus string.

You will implement Randomized Motif Search and Gibbs Sampler, run both algorithms and compare the scores and consensus strings obtained for different k values.

<strong>Input File: </strong>

<ul>

 <li>Prepare an input file which has 10 lines, where each line contains strings of lengt 500.</li>

 <li>Each line will include a randomly generated DNA string with 500 bases.</li>

 <li>Insert a 10-mer with 4 mutations in random positions into the DNA string.</li>

 <li>You will have total of 10 DNA strings, so you will use 10 motifs and find the consensus string.</li>

</ul>

<strong>Details: </strong>

<ul>

 <li>Select a random position between 0 – 490 to insert the 10-mer. Also find 4 random positions to apply mutation to the 10-mer. Each 10-mer you have inserted should have 4 mutations.</li>

 <li>Your programs should take a file as input and a k value which will be the length of the consensus string. Run your algorithm for k=9, 10, 11 and comment about the strings in the project report. Both Randomized Motif Search and Gibbs Sampler are iterative algorithms. Let your Gibbs Sampler continue until the score of the algorithms no longer improve. For example, check your score every 50 iterations. If you see that the score remains the same for the last 50 iterations, then you can stop your algorithm.</li>

 <li>At the end of the programs, you will have 10 motifs. Use these motifs to find the consensus string. You can use the link below to draw the consensus strings. You need to give your motifs as the sequence data. <a href="http://weblogo.threeplusone.com/create.cgi">http://weblogo.threeplusone.com/create.cgi</a></li>

 <li>You will prepare a project report that will include the project details and conclusions about the results.</li>

</ul>





