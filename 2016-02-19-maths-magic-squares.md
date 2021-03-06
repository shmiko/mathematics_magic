---
layout: post
section-type: post
title: Maths Magic Squares
category: maths
tags: [ 'maths']
---
  

## Mathematics Tricks



1. **Magic Squares** - Simple to difficult.

**1.** **Magic Squares**   
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
          <th class="tg-yw4l" colspan="5">Birthdate of 03/09/1970 using Formula 1</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <th class="tg-q47l">3</th>
          <th class="tg-hw0o">9</th>
          <th class="tg-2gbq">19</th>
          <th class="tg-9tub">70</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">71</td>
          <td class="tg-q47l">18</td>
          <td class="tg-9tub">6</td>
          <td class="tg-2gbq">6</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">7</td>
          <td class="tg-qvf1">5</td>
          <td class="tg-606q">72</td>
          <td class="tg-69zb">17</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">20</td>
          <td class="tg-0we2">69</td>
          <td class="tg-69zb">4</td>
          <td class="tg-606q">8</td>
          <td class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Formula 1</th>
        </tr>
        <tr>
          <th class="tg-q47l">Day-DD</th>
          <th class="tg-hw0o">Month-MM</th>
          <th class="tg-2gbq">Year-1st Half-YY1</th>
          <th class="tg-9tub">Year-2nd Half-YY2</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
        </tr>
        <tr>
          <td class="tg-hw0o">D+1</td>
          <td class="tg-q47l">C-1</td>
          <td class="tg-9tub">B-3</td>
          <td class="tg-2gbq">A+3</td>
        </tr>
        <tr>
          <td class="tg-0we2">B-2</td>
          <td class="tg-qvf1">A+2</td>
          <td class="tg-606q">D+2</td>
          <td class="tg-69zb">C-2</td>
        </tr>
        <tr>
          <td class="tg-qvf1">C+1</td>
          <td class="tg-0we2">D-1</td>
          <td class="tg-69zb">A+1</td>
          <td class="tg-606q">B-1</td>
        </tr>
      </table>
    </th>
  </tr>
</table>
<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Birthdate of 03/09/1970 using Formula 2</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <th class="tg-q47l">3</th>
          <th class="tg-hw0o">9</th>
          <th class="tg-2gbq">19</th>
          <th class="tg-9tub">70</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">22</td>
          <td class="tg-q47l">67</td>
          <td class="tg-9tub">6</td>
          <td class="tg-2gbq">6</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">68</td>
          <td class="tg-qvf1">17</td>
          <td class="tg-606q">11</td>
          <td class="tg-69zb">5</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">8</td>
          <td class="tg-0we2">8</td>
          <td class="tg-69zb">65</td>
          <td class="tg-606q">20</td>
          <td class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Formula 2</th>
        </tr>
        <tr>
          <th class="tg-q47l">Day-DD</th>
          <th class="tg-hw0o">Month-MM</th>
          <th class="tg-2gbq">Year-1st Half-YY1</th>
          <th class="tg-9tub">Year-2nd Half-YY2</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
        </tr>
        <tr>
          <td class="tg-hw0o">D+1</td>
          <td class="tg-q47l">C-1</td>
          <td class="tg-9tub">B-3</td>
          <td class="tg-2gbq">A+3</td>
        </tr>
        <tr>
          <td class="tg-0we2">B-2</td>
          <td class="tg-qvf1">A+2</td>
          <td class="tg-606q">D+2</td>
          <td class="tg-69zb">C-2</td>
        </tr>
        <tr>
          <td class="tg-qvf1">C+1</td>
          <td class="tg-0we2">D-1</td>
          <td class="tg-69zb">A+1</td>
          <td class="tg-606q">B-1</td>
        </tr>
      </table>
    </th>
  </tr>
</table>
<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Birthdate of 03/09/1970 using Formula 3</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <th class="tg-q47l">3</th>
          <th class="tg-hw0o">9</th>
          <th class="tg-2gbq">19</th>
          <th class="tg-9tub">70</th>
          <th class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">18</td>
          <td class="tg-q47l">71</td>
          <td class="tg-9tub">2</td>
          <td class="tg-2gbq">10</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">71</td>
          <td class="tg-qvf1">20</td>
          <td class="tg-606q">8</td>
          <td class="tg-69zb">2</td>
          <td class="tg-yw4l">&lt;&lt; 101 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">9</td>
          <td class="tg-0we2">1</td>
          <td class="tg-606q">72</td>
          <td class="tg-69zb">19</td>
          <td class="tg-yw4l">&gt;&gt; 101 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
          <td class="tg-yw4l">101</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Formula 3</th>
        </tr>
        <tr>
          <th class="tg-q47l">Day-DD</th>
          <th class="tg-hw0o">Month-MM</th>
          <th class="tg-2gbq">Year-1st Half-YY1</th>
          <th class="tg-9tub">Year-2nd Half-YY2</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
        </tr>
        <tr>
          <td class="tg-hw0o">C-1</td>
          <td class="tg-q47l">D+1</td>
          <td class="tg-9tub">A-1</td>
          <td class="tg-2gbq">B+1</td>
        </tr>
        <tr>
          <td class="tg-0we2">D+1</td>
          <td class="tg-qvf1">C+1</td>
          <td class="tg-606q">B-1</td>
          <td class="tg-69zb">A-1</td>
        </tr>
        <tr>
          <td class="tg-qvf1">B</td>
          <td class="tg-0we2">A-2</td>
          <td class="tg-69zb">D+2</td>
          <td class="tg-606q">C</td>
        </tr>
      </table>
    </th>
  </tr>
</table>
<table>
  <tr>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Birthdate of 12/05/2006 using Formula 2</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
          <th class="tg-yw4l">&gt;&gt; 43 &lt;&lt;</th>
        </tr>
        <tr>
          <th class="tg-q47l">12</th>
          <th class="tg-hw0o">5</th>
          <th class="tg-2gbq">20</th>
          <th class="tg-9tub">6</th>
          <th class="tg-yw4l">&gt;&gt; 43 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">23</td>
          <td class="tg-q47l">3</td>
          <td class="tg-9tub">15</td>
          <td class="tg-2gbq">2</td>
          <td class="tg-yw4l">&lt;&lt; 43 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-0we2">4</td>
          <td class="tg-qvf1">18</td>
          <td class="tg-606q">7</td>
          <td class="tg-69zb">14</td>
          <td class="tg-yw4l">&lt;&lt; 43 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">4</td>
          <td class="tg-0we2">17</td>
          <td class="tg-69zb">1</td>
          <td class="tg-606q">21</td>
          <td class="tg-yw4l">&gt;&gt; 43 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">43</td>
          <td class="tg-yw4l">43</td>
          <td class="tg-yw4l">43</td>
          <td class="tg-yw4l">43</td>
          <td class="tg-yw4l">43</td>
        </tr>
      </table>
    </th>
    <th></th>
    <th>
      <table class="tg">
        <tr>
          <th class="tg-yw4l" colspan="5">Birthdate of 15/05/2004 using Formula 3</th>
        </tr>
        <tr>
          <th class="tg-q47l">A</th>
          <th class="tg-hw0o">B</th>
          <th class="tg-2gbq">C</th>
          <th class="tg-9tub">D</th>
          <th class="tg-yw4l">&gt;&gt; 44 &lt;&lt;</th>
        </tr>
        <tr>
          <th class="tg-q47l">15</th>
          <th class="tg-hw0o">5</th>
          <th class="tg-2gbq">20</th>
          <th class="tg-9tub">4</th>
          <th class="tg-yw4l">&gt;&gt; 44 &lt;&lt;</th>
        </tr>
        <tr>
          <td class="tg-hw0o">19</td>
          <td class="tg-q47l">5</td>
          <td class="tg-9tub">14</td>
          <td class="tg-2gbq">6</td>
          <td class="tg-yw4l">&lt;&lt; 44 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-qvf1">5</td>
          <td class="tg-0we2">21</td>
          <td class="tg-69zb">4</td>
          <td class="tg-69zb">14</td>
          <td class="tg-yw4l">&lt;&lt; 44 &gt;&gt;</td>
        </tr>
        <tr>
          <td class="tg-i6eq">5</td>
          <td class="tg-b44r">13</td>
          <td class="tg-b44r">6</td>
          <td class="tg-606q">20</td>
          <td class="tg-yw4l">&gt;&gt; 44 &lt;&lt;</td>
        </tr>
        <tr>
          <td class="tg-yw4l">44</td>
          <td class="tg-yw4l">44</td>
          <td class="tg-yw4l">44</td>
          <td class="tg-yw4l">44</td>
          <td class="tg-yw4l">44</td>
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

