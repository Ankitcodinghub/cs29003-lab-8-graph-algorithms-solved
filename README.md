# cs29003-lab-8-graph-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [CS29003 Lab 8-Graph Algorithms Solved](https://www.ankitcodinghub.com/product/cs29003-lab-8-graph-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92911&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS29003 Lab 8-Graph Algorithms Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Graph Algorithms

Consider a N × N grid of squares (or blocks) with co-ordinates ranging from (0, 0) to (N − 1, N − 1). Each value of the grid (grid[i][j]) represents the elevation at that particular block (i,j). When you start to move at time t = 0, the blocks rise such that at time t the elevation of (i, j)th block would be max(grid[i][j], t). You can only move to your adjacent blocks (top, bottom, left or right) if and only if the elevation of both the blocks individually are at most t. You can move infinite distance in zero time, but you must stay within the boundaries of the grid during your move.

Initially you are standing at (Sx, Sy)th block.

◃ What is the least time in which you can reach the (Fx, Fy)th block?

◃ Print the path travelled to reach (Fx, Fy)th block.

◃ Also print the number of blocks traversed to reach (Fx, Fy)th block.

There are many ways to solve this problem. Solve using BFS or DFS. Consider the blocks as nodes and edges run to the four neighboring blocks (top, bottom, right and left). Usage of STL is not allowed.

Input

<ul>
<li>◃ &nbsp;First line of input contains the integer N denoting the size of the grid.</li>
<li>◃ &nbsp;Next N lines contain N integers each where each integer Xij represents the initial elevation of
(i, j)th block in the grid.
</li>
<li>◃ &nbsp;The next line contains two pairs of integers (Sx, Sy) and (Fx, Fy), representing your start and target</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
positions, respectively.

Sample Input and Output

Test Case 1

Input: 5

01234 24232221 5 12 13 14 15 16 11 17 18 19 20 10 9 8 7 6

0044

Output:

Minimum time taken is: 16

</div>
<div class="column">
0 􏰀 Sx, Sy 􏰀 N − 1

</div>
<div class="column">
0 􏰀 Fx, Fy 􏰀 N − 1

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The Path to reach from (0,0) to (4,4) is:

(0, 0), (0, 1), (0, 2), (0, 3), (0, 4), (1, 4), (2, 4), (2, 3), (2, 2), (2, 1), (2, 0), (3, 0), (4, 0), (4, 1), (4, 2), (4, 3), (4, 4)

The Number of Blocks traversed are: 17

Explanation:

At t = 0, you start at (0, 0)th block. The neighbouring block with smallest height is (0, 1) which is 1. So, at t = 1, the height of your standing block ((0, 0)th block) will become 1. Therefore you can move from (0, 0)th block to (0, 1)th block at t = 1.

At t = 5, you will be at (1,4)th block whose elevation is 5. The elevations of the blocks at t = 5 is shown below. The bold numbers indicate the path travelled till now.

55555 24232221 5 12 13 14 15 16 11 17 18 19 20 10 9 8 7 6

At (1,4)th block, the neighbour with smallest height is (2,4)th block which is 16. So you have to wait until t = 16 to move to (2, 4)th block. The elevations of the blocks at t = 16 are:

16 16 16 16 16 24 23 22 21 16 16 16 16 16 16 16 17 18 19 20 16 16 16 16 16

Now at t = 16, the elevation at (1, 4)th block would be 16. Now you can move to any block of height 16. Therefore you can reach the (4, 4)th block at t = 16.

16 16 16 16 16 24 23 22 21 16 16 16 16 16 16 16 17 18 19 20 16 16 16 16 16

The final route is marked in bold above. You need to wait until time 16 so that (0,0) and (4,4) are connected.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Test Case 2

Input: 10

55 33 29 78 47 62 60 79 41 54 34169364384691 8 4065 2274127028809032 6 45 23498552115683 5 3695 31 48 14 89 76 82 19 26 97 63

0 75 9 77 2 51 94 7 71 99 35 81 44 87 43 18 67 17 13 57 92 53 37 39 20 88 15 68 24 66 276984 3 721061305058 73969825 4 2186 1 5942

0099

Output:

Minimum time taken is: 61

The Path to reach from (0,0) to (9,9) is:

(0, 0), (1, 0), (2, 0), (3, 0), (4, 0), (4, 1), (4, 2), (5, 2), (6, 2), (7, 2), (7, 3), (8, 3), (9, 3), (9, 4), (9, 5), (8, 5), (8, 6), (8, 7), (9, 7), (9, 8), (9, 9)

The Number of Blocks traversed are: 21

Explanation:

55 33 29 78 47 62 60 79 41 54 34169364384691 8 4065 2274127028809032 6 45 23498552115683 5 3695 31 48 14 89 76 82 19 26 97 63

0 75 9 77 2 51 94 7 71 99 35 81 44 87 43 18 67 17 13 57 92 53 37 39 20 88 15 68 24 66 276984 3 721061305058 73969825 4 2186 1 5942

The final route is marked in bold. You need to wait until time 61 so that (0, 0) and (9, 9) are connected. BONUS QUESTION: All students can attempt. Will be checked only when you are

at borderline of grades at the end of the semester.

Use Dijkstra’s Algorithm to find the least time to reach (Fx, Fy)th block. Write the code in function

leastTimeDijkstra. Usage of STL is not allowed.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
