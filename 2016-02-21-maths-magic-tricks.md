<link href="grayscale.css" rel="stylesheet">
  

## Mathematics Tricks



I'm going to try my best to explain some maths tricks starting with some pretty simple ideas for which you can try yourself on firends and family. These are not new nor created by me but are centuries old tricks.  

1. How to guess **how much money** someone has in their wallet/purse or pocket.
2. **Magic Squares** - Simply to difficult.
3. How to work out the **day or the week** for any given date in history or the future.
4. Easy **Square Roots**
5. **Vedic** Maths.
6. Some fun **Fibonacci** facts and **The Golden Ratio**.


**1.** How to guess **how much money** someone has on them. Just guessing either dollars only or cents only.
STEPS - Ask person to do these steps
   1.       Ask them to take the amount he they in his pocket or wallet/purse, count it and remember the number.
   2.       Ask them to add 5 to the number.
   3.       Ask them to multiply by 5 the answer from step 2 .
   4.       Ask them to to double the answer from step 3.
   5.       Ask them to add any one digit number from 0 to 9 to the result from step 4.
   6.       Ask them to add 10 to the result from step 5.
   After the steps are over ask them to tell you the final answer.

ADDITIONAL STEPS - To be done by you
    ·      Ignore the digit in the unit’s place from the answer given.
    ·      From the remaining number, subtract 6 and you will come to know the amount of money they have.

EXAMPLE
Let us suppose a person has $23 on them. The steps are given below:
    1.      Take the amount in your wallet        = 23
    2.      Add 5                                 = 28
    3.      Multiply by 5                         = 140
    4.      Double the answer                     = 280
    5.      Add a single digit number (say, 7)    = 287
    6.      Add 10                                = 297

The final answer would have been 297.
Ignore the digit in the unit’s place (in this case it is 7). Now the remaining number is 29.
From 29, we subtract 6 to get 23.
The our answer is **$23**.

Another quick EXAMPLE
Assume money is $48
48 + 5 = 53 X 5 = 265 X 2 = 530 + 3 = 533 + 10 = 543, remove 3 = 54 - 6 = **48**!  

---  


**2.** **Magic Squares**   
Starting with a simple formula to fill in Magic Squares based on a 4 x 4 square given a total.

<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a total of 34</th>
        </tr>
        <tr>
          <th class="tg-q47l">1</th>
          <th class="tg-hw0o">15</th>
          <th class="tg-2gbq">14</th>
          <th class="tg-9tub">4</th>
          <th class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">12</td>
          <td class="tg-q47l">6</td>
          <td class="tg-9tub">7</td>
          <td class="tg-2gbq">9</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">8</td>
          <td class="tg-qvf1">10</td>
          <td class="tg-606q">11</td>
          <td class="tg-69zb">5</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">13</td>
          <td class="tg-0we2">3</td>
          <td class="tg-69zb">2</td>
          <td class="tg-606q">16</td>
          <td class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a total of 130</th>
        </tr>
        <tr>
          <th class="tg-q47l">25</th>
          <th class="tg-hw0o">39</th>
          <th class="tg-2gbq">38</th>
          <th class="tg-9tub">28</th>
          <th class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">36</td>
          <td class="tg-q47l">30</td>
          <td class="tg-9tub">31</td>
          <td class="tg-2gbq">33</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">32</td>
          <td class="tg-qvf1">34</td>
          <td class="tg-606q">35</td>
          <td class="tg-69zb">29</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">37</td>
          <td class="tg-0we2">27</td>
          <td class="tg-69zb">26</td>
          <td class="tg-606q">40</td>
          <td class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
        </tr>
      </table>
    </th>
  </tr>
</table>

**Instructions**    
 - Start at top left with 1, or Total - 34. Eg 130 total would require starting at 25 instead adding 24 to each cell which is the diffrence from 130 - 34 / 4 for each cell.  
 - Filling in the diagonal cells only going right to left on the top and bottom rows and right to left for the middle rows.  
 - When done go back to fill the blank cells with the missing numbers up to 16 going left to right on the bottom and top rows and right to left for the middle rows.  
 - All columns and rows with sum to total given.  
 - Both diagonal will sum to the total as well.  
 - The top 3 quads will also as will the bottom 3 quads.  
 - And the center quad will also sum to the total.  
 - As will the 4 corners sum to the total.  
**CAVEAT:** The total must be a multiple of 4, if not it cannot be done.

**Medium Difficulty**  
Now lets see the formula to fill in Magic Squares based on a 4 x 4 square given someones birthdate.
<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a birthdate of 03/09/1970</th>
        </tr>
        <tr>
          <th class="tg-q47l">1</th>
          <th class="tg-hw0o">15</th>
          <th class="tg-2gbq">14</th>
          <th class="tg-9tub">4</th>
          <th class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">12</td>
          <td class="tg-q47l">6</td>
          <td class="tg-9tub">7</td>
          <td class="tg-2gbq">9</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">8</td>
          <td class="tg-qvf1">10</td>
          <td class="tg-606q">11</td>
          <td class="tg-69zb">5</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-i6eq">13</td>
          <td class="tg-b44r">3</td>
          <td class="tg-b44r">2</td>
          <td class="tg-i6eq">16</td>
          <td class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a birthdate of 15/05/2004</th>
        </tr>
        <tr>
          <th class="tg-q47l">25</th>
          <th class="tg-hw0o">39</th>
          <th class="tg-2gbq">38</th>
          <th class="tg-9tub">28</th>
          <th class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">36</td>
          <td class="tg-q47l">30</td>
          <td class="tg-9tub">31</td>
          <td class="tg-2gbq">33</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">32</td>
          <td class="tg-qvf1">34</td>
          <td class="tg-606q">35</td>
          <td class="tg-69zb">29</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">37</td>
          <td class="tg-0we2">27</td>
          <td class="tg-69zb">26</td>
          <td class="tg-606q">40</td>
          <td class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
        </tr>
      </table>
    </th>
  </tr>
</table>

**Instructions**    
 - Start at top left with 1, or Total - 34. Eg 130 total would require starting at 25 instead adding 24 to each cell which is the diffrence from 130 - 34 / 4 for each cell.  
 - Filling in the diagonal cells only going right to left on the top and bottom rows and right to left for the middle rows.  
 - When done go back to fill the blank cells with the missing numbers up to 16 going left to right on the bottom and top rows and right to left for the middle rows.  
 - All columns and rows with sum to total given.  
 - Both diagonal will sum to the total as well.  
 - The top 3 quads will also as will the bottom 3 quads.  
 - And the center quad will also sum to the total.  
 - As will the 4 corners sum to the total.  
**CAVEAT:** The total must be a multiple of 4, if not it cannot be done.

**Most Difficult**  
Lets try the formula to fill in Magic Squares based on a 4 x 4 square given 3 random numbers to go into 3 chosen cells.

<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a total of 34</th>
        </tr>
        <tr>
          <th class="tg-q47l">1</th>
          <th class="tg-hw0o">15</th>
          <th class="tg-2gbq">14</th>
          <th class="tg-9tub">4</th>
          <th class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">12</td>
          <td class="tg-q47l">6</td>
          <td class="tg-9tub">7</td>
          <td class="tg-2gbq">9</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">8</td>
          <td class="tg-qvf1">10</td>
          <td class="tg-606q">11</td>
          <td class="tg-69zb">5</td>
          <td class="tg-yw4l">&lt;&lt; 34 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-i6eq">13</td>
          <td class="tg-b44r">3</td>
          <td class="tg-b44r">2</td>
          <td class="tg-i6eq">16</td>
          <td class="tg-yw4l">&gt;&gt; 34 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
          <td class="tg-yw4l">34</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Magic Square given a total of 130</th>
        </tr>
        <tr>
          <th class="tg-q47l">25</th>
          <th class="tg-hw0o">39</th>
          <th class="tg-2gbq">38</th>
          <th class="tg-9tub">28</th>
          <th class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">36</td>
          <td class="tg-q47l">30</td>
          <td class="tg-9tub">31</td>
          <td class="tg-2gbq">33</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">32</td>
          <td class="tg-qvf1">34</td>
          <td class="tg-606q">35</td>
          <td class="tg-69zb">29</td>
          <td class="tg-yw4l">&lt;&lt; 130 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">37</td>
          <td class="tg-0we2">27</td>
          <td class="tg-69zb">26</td>
          <td class="tg-606q">40</td>
          <td class="tg-yw4l">&gt;&gt; 130 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
          <td class="tg-yw4l">130</td>
        </tr>
      </table>
    </th>
  </tr>
</table>

**Instructions**    
 - Start at top left with 1, or Total - 34. Eg 130 total would require starting at 25 instead adding 24 to each cell which is the diffrence from 130 - 34 / 4 for each cell.  
 - Filling in the diagonal cells only going right to left on the top and bottom rows and right to left for the middle rows.  
 - When done go back to fill the blank cells with the missing numbers up to 16 going left to right on the bottom and top rows and right to left for the middle rows.  
 - All columns and rows with sum to total given.  
 - Both diagonal will sum to the total as well.  
 - The top 3 quads will also as will the bottom 3 quads.  
 - And the center quad will also sum to the total.  
 - As will the 4 corners sum to the total.  
**CAVEAT:** The total must be a multiple of 4, if not it cannot be done.  

---  

**3.** How to guess the **day of week** for any given date.

Formulas are:
**Year Codes** starting with 2014 (A Leap Year Add 1)
2013  2014  2015  2016  2017  2018 - 2000(LY) 1900  1800  1700  1600
2     3     4     6     7/0   1      0        1     3     5     0

**Day of Week Codes**
Monday  Tuesday Wednesday Thursday  Friday  Saturday  Sunday
1       2       3         4         5       6         7/0

**Month Codes** (Leap Year Minus 1)
Jan   Feb   Mar Apr May Jun Jul Aug Sep Oct Nov Dec
6(-1) 2(-1) 2   5   0   3   5   1   4   6   2   4

EXAMPLE To Follow Soon  

---  


**4.**  Easy **Square Roots** for any 2 digit Numbers x^2
EXAMPLE
17^2 - Round number up or down to closest 10
so 17^2 would round up to 20 which is a count of 3.
So calculation is 17 + 3 = 20 X 17 - 3 = 14
Read as 20 X 14 = 280
Now add count^2 which is 3^2 = 9
So 280 + 9 = **289**

ANOTHER EXAMPLE
63^2
Round down to 60 meaning a count of 3
So 63 - 3 = 60 X 63 + 3 = 66
Read as 60 X 66 = 3960
Add 3^2 = 9
So 3600 + 9 = **3969**  

---  


**5.** **Vedic** Maths - To Follow  

---  


**6.** **Fibonacci** Fun Facts and **The Golden Ratio**

Fibonacci numbers are those where the following number in a sequence is added to the previous number to get the next number usually read using the following mathematical formula.
Fn = Fn-1 + Fn-2

EXAMPLE
1 1 2 3 5 8 13  21  34  55  89

1 + 1 + 4 = 6 which = 2 X 3
1 + 1 + 4 + 9 = 15 which + 3 X 5
1 + 1 + 4 + 9 + 25 = 40 which = 5 X 8
1 + 1 + 4 + 9 + 25 + 64 = 104 which = 8 X 13 which is 1^2 + 1^2 + 3^2 + 5^2 + 8^2 = 8 X 13

These sequences can be represented as a box of squares/rectanlges
Once drawn as boxes you can get the area using the same as above 1^2 + 1^2 + 3^2 + 5^2 + 8^2 = 8 X 13
or height X length, 13 = 8 + 5

Another way to look at the same sequence
8 X 13  = 13 / 8  = 1.625
13 X 21 = 21 / 13 = 1.615
21 X 34 = 34 / 21 = 1.619
34 X 55 = 55 / 34 = 1.6176
55 X 89 = 89 / 55 = 1.61818

This is showing the **Golden Ration** known as 1.618033

