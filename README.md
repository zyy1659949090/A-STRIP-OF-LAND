# A-STRIP-OF-LAND

A STRIP OF LAND


Language:
A STRIP OF LAND
Time Limit: 20000MS		Memory Limit: 65536K
Total Submissions: 6799		Accepted: 2020
Case Time Limit: 5000MS

Description

The residents of Dingilville are trying to locate a region to build an airport. The map of the land is at hand. The map is a rectangular grid of unit squares, each identified by a pair of coordinates (x,y), where x is the horizontal (west-east) and y is the vertical (south-north) coordinate. The height of every square is shown on the map.

Your task is to find a rectangular region of squares with the largest area (i.e. a rectangular region consisting of the largest number of squares) such that
1.the height difference between the highest and the lowest squares of the region is less than or equal to a given limit C, and
2.the width (i.e. the number of squares along the west-east direction) of the region is at most 100.

In case there is more than one such region you are required to report only one of them.

Input

The first line contains three integers: U, V and C.
Each of the following V lines contains the integers Hxy for x = 1,...,U. More specifically, Hxy occurs as the x'th number on the (V-y+2)'th input line.
a.1 <= U <= 700, 1 <= V <= 700 where U and V designate the dimensions of the map. More specifically, U is the number of squares in the west-east direction, and V, in the south-north direction.
b.0 <= C <= 10
c.-30,000 <= Hxy <= 30,000 where the integer Hxy is the height of the square at coordinates (x, y), 1 <= x <= U, 1 <= y <= V.
d.The southwest corner square of the map has the coordinates (1,1) and the northeast corner has the coordinates (U,V).

Output

Output the largest area.

Sample Input

10 15 4
41 40 41 38 39 39 40 42 40 40
39 40 43 40 36 37 35 39 42 42
44 41 39 40 38 40 41 38 35 37
38 38 33 39 36 37 32 36 38 40
39 40 39 39 39 40 40 41 43 41
39 40 41 38 39 38 39 39 39 42
36 39 39 39 39 40 39 41 40 41
31 37 36 41 41 40 39 41 40 40
40 40 40 42 41 40 39 39 39 39
42 40 44 40 38 40 39 39 37 41
41 41 40 39 39 40 41 40 39 40
47 45 49 43 43 41 41 40 39 42
42 41 41 39 40 39 42 40 42 42
41 44 49 43 46 41 42 41 42 42
45 40 42 42 46 42 44 40 42 41

Sample Output

35

Source
IOI 1999
