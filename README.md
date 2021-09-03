<!DOCTYPE html>
<html>

<body>
<h1>Madi Combe</h1>
<h3>My House</h3>
<p>I think <b>my house</b> is my most favorite place in the world because my <b>bed</b> is there and I really like to <b>sleep</b>.</p>
</body>
<hr>
<h1>Directions</h1>
<ol>
    <li>My house is already in Missouri, so heres hot to get to Maryville from LA</li>
    <li>Get on a plane at LAX</li>
    <li>Fly for a few hours</li>
    <li>Get off the plane in Kansas City</li>
    <li>Welcome to Missouri</li>
    <ol>
    <li>Get on a bus</li>
    <li>Ride on the bus for a few hours</li>
    <li>Welcome to Maryville</li>
    </ol>
</ol>
<h1>Some Things You'll Need</h1>
<ul>
    <li>Blanket</li>
    <li>Comfy clothes</li>
    <li>A snack</li>
    <li>Fluffy socks</li>
    <li>1 or 2 Squishmallows</li>
</ul>
<hr>
<h1>Table</h1>
<table>
<tr>
    <th>Food / Drink</th>
    <th>Where to get it</th>
    <th>Cost</th>
</tr>
<tr>
    <td>Thai Boba Tea</td>
    <td>Simply Siam / BGC</td>
    <td>$6</td>
</tr>
<tr>
    <td>Waffle House Waffles</td>
    <td>Waffle House</td>
    <td>$3</td>
</tr>
<tr>
    <td>Filet Mignon</td>
    <td>Outback Steakhouse</td>
    <td>$23</td>
</tr>
</table>
<hr>
<h1>Quotes</h1>
<blockquote cite="https://www.brainyquote.com/quotes/trixie_mattel_941486">I'm an optimistic realist. I kind of expect the worst but prepare for the best. <br> <i>Trixie Mattel</i></blockquote>
<blockquote cite="https://www.brainyquote.com/quotes/tom_holland_836230">If I can bring happiness to people all around the world, then I will try my best to do so. <br> <i>Tom Holland</i></blockquote>
<hr>
<h1>Code Fencing</h1>
<block quote="https://brilliant.org/wiki/fenwick-tree/">A Fenwick tree or binary indexed tree is a data structure that helps compute prefix sums efficiently. Computing prefix sums are often important in various other algorithms, not to mention several competitive programming problems. For example, they are used to implement the arithmetic coding algorithm. Fenwick trees were invented by Peter M. Fenwick in 1994.<br>According to <a href="https://brilliant.org/wiki/fenwick-tree/">Brilliant.org</a></blockquote>
<pre><code>
def sum(int r):
    res = 0
    while (r >= 0):
        res += t[r]
        r = g(r) - 1
    return res

def increase(int i, int delta):
    for all j with g(j) <= i <= j:
        t[j] += delta
</code></pre>
<a href="https://cp-algorithms.com/data_structures/fenwick.html">cp-algorithms.com</a>

</html>