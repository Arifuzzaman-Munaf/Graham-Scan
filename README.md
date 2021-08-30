Problem Statement: You are given n points in a plane. Whenever I find three points that are collinear, I draw a line through them. How many different lines are there? Come up with an efficient algorithm. First, explain your solution. Then provide a code written in C++ or JAVA or python. Or you can just give me a
clearly written pseudo code.

Solution: In this problem, our main objective is to find collinear lines going through three consecutive points. For this problem, I can use the methodology of Graham Scan algorithm. In this algorithm, I have sorted the points according to their polar angles
or slopes which is a property of Graham Scan.
