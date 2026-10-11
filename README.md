# c++-notes-
for Competetive Programing

1) COMBINATRONICS
 XOR : 1) a^0=a; 2) a^a=0; 3)a ^ b has a 1 exactly at positions where a and b differ ; 4)a ^ b <= a + b, and a + b = (a ^ b) + 2 * (a & b) ; 5)a | b = (a ^ b) + (a & b) ; 6)x ^ (all ones) flips every bit, and x ^ (1 << k) flips bit k ; 7)Parity: the XOR of a set of numbers has bit k set if and only if an odd number of them have bit k set.
 


3) Back Tracking:
   Problem : 78 LeetCode ( Generate all posible subset)
   : 
