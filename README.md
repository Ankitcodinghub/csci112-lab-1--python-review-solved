# csci112-lab-1--python-review-solved
**TO GET THIS SOLUTION VISIT:** [CSCI112  Lab 1- Python Review Solved](https://www.ankitcodinghub.com/product/csci112-python-review-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116918&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI112 &nbsp;Lab 1- Python Review Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Documentation: Each file should begin with a docstring that includes your name, the class number and name, the lab number, and a short description of the lab, as well as documentation pertinent to that particular file.

The Problems:

1. Create a function to take a two-dimensional matrix of N * N integer elements, represented as a list of lists, and return a new matrix which will be the original matrix rotated num times, where if num is positive, the rotation is clockwise, and if not, counterclockwise. Examples

&gt;&gt;&gt; rotate_transform([

[2, 4],

[0, 0]], 1)

[

[0, 2],

[0, 4]

]

&gt;&gt;&gt; rotate_transform([

[2, 4],

[0, 0]], -1)

[

[4, 0],

[2, 0]

]

1

2

3

4

5

6

7

8

9 10

11

12

13

14

2. Create a function called count_mines that takes a list representation of a Minesweeper board, and returns another board where the value of each cell is the amount of its neighbouring mines.

[

[0, 1, 0, 0],

[0, 0, 1, 0],

[0, 1, 0, 1],

[1, 1, 0, 0]

]

1

2

3

4

5

6

The 0 represents an empty space . The 1 represents a mine.

You will have to replace each mine with a 9 and each empty space with the number of adjacent mines, the output will look like this:

[

[1, 9, 2, 1],

[2, 3, 9, 2],

[3, 9, 4, 9],

[9, 9, 3, 1]

]

1

2

3

4

5

6

3. Create a function that takes in a nested list and an element and returns the frequency of that element by nested level.

Examples:

&gt;&gt;&gt; freq_count([1, 4, 4, [1, 1, [1, 2, 1, 1]]], 1)

[[0, 1], [1, 2], [2, 3]]

# The list has one 1 at level 0, 2 1’s at level 1, and 3 1’s at level 2.

&gt;&gt;&gt; freq_count([1, 5, 5, [5, [1, 2, 1, 1], 5, 5], 5, [5]], 5)

[[0, 3], [1, 4], [2, 0]]

&gt;&gt;&gt; freq_count([1, [2], 1, [[2]], 1, [[[2]]], 1, [[[[2]]]]], 2)

[[0, 0], [1, 1], [2, 1], [3, 1], [4, 1]]

1

2

3

4

5

6

7

8

9

4. Use and extend the textbook’s implementation of a Fraction class to help you build a function to find Farey sequences. The Farey sequence of order n is the set of all fractions with a denominator between 1 and n, reduced and returned in ascending order. Given n, return the Farey sequence as a list, with each fraction being represented by a string in the form ”numerator/denominator”. Examples

&gt;&gt;&gt; farey(1)

[“0/1”, “1/1”]

&gt;&gt;&gt; farey(4)

[“0/1”, “1/4”, “1/3”, “1/2”, “2/3”, “3/4”, “1/1”]

&gt;&gt;&gt; farey(5)

[“0/1”, “1/5”, “1/4”, “1/3”, “2/5”, “1/2”, “3/5”, “2/3”, “3/4”, “4/5”, “1/1”]

1

2

3

4

5

6

7

8

5. Write a function to determine the best Poker combination that is present in a hand of five cards. Every card is a string containing the card value (with the upper-case initial for face-cards and the lower-case initial for suits), as in the examples below:

”Ah” → Ace of hearts

”Ks” → King of spades

”3d” → Three of diamonds

”Qc” → Queen of clubs

There are 10 different combinations. Here’s the list, in decreasing order of importance:

Name Description

Royal Flush A, K, Q, J, 10, all with the same suit.

Straight Flush Five cards in sequence, all with the same suit.

Four of a Kind Four cards of the same rank.

Full House Three of a Kind with a Pair.

Flush Any five cards of the same suit, not in sequence.

Straight Five cards in a sequence, but not of the same suit.

Three of a Kind Three cards of the same rank.

Two Pair Two different Pair.

Pair Two cards of the same rank.

High Card No other valid combination.

For purposes of rank, Aces are considered both high and low, that is either 1 or 14, whichever gives the best hand.

Given a list hand containing five strings being the cards, implement a function that returns a string with the name of the highest combination obtained, accordingly to the table above.

Examples:

&gt;&gt;&gt; poker_hand_ranking([“10h”, “Jh”, “Qh”, “Ah”, “Kh”])

“Royal Flush”

&gt;&gt;&gt; poker_hand_ranking([“3h”, “5h”, “Qs”, “9h”, “Ad”])

“High Card”

&gt;&gt;&gt; poker_hand_ranking([“10s”, “10c”, “8d”, “10d”, “10h”])

“Four of a Kind”

1

2

3

4

5

6

7

8

Implement a Card class, with a reasonable representation for cards, to help solve this problem. Justify your choice of representation and the memeber functions in the comments, with particular reference to how they help you with the Poker hand problem.

Optional: Check for legal hands, so that, for example, Yosemite Sam’s “five aces” and Bugs Bunny’s “six aces” would each raise an exception.
