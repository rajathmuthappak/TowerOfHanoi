According to the legend, the monks in a remote mountain monastery knew how to predict when the world would end. They had a set of three diamond needles. Stacked on the first diamond needle were 64 gold disks of decreasing size. The monks moved one disk to another needle each hour, subject to the following rules:
  1.Only one disk could be moved at a time.
  2.A larger disk must never be stacked above a smaller one.
  3.One and only one auxiliary needle could be used for the intermediate storage of disks.
  
This project deals with the solution of the Tower Of Hanoi problem as described above using openGL.The solution involves moving of the disks one after the other over the pegs obeying the above specified rules.
User interface requires the user to enter the number of disks on the source peg. Using the intermediate peg all the n disks are moved to the destination peg and the number of moves required are 2^n -1.

How to solve this problem?
We use recursion to solve this problem,
If we assume the number of disks to be three then we follow the below mentioned steps:
Step 1:Move disk 1 from source to destination.
Step 2:Move disk 2 from source to auxiliary peg.
Step 3:Move disk 1 from destination to auxiliary peg.
Step 4:Move disk 3 from source to destination.
Step 5:Move disk 1 from auxiliary to source.
Step 6:Move disk 2 from auxiliary to destination.
Step 7:Move disk 1 from source to destination
