<h1>Sanku Dheemanth Reddy</h1>
<h2>My favourite place is california</h2>
<p>Aside from the beautiful <b> beaches </b> and beautiful <b> mountains </b></p>
<hr>  </hr>
<h3>location to marryville</h3>
<ol>
<li>start form california through tulare</li>
<li>take a slight left from bakersfield</li>
<li>then drive straight to tehachapi</li>
<li>take a slight right towards bekar</li>
<li>take right towards denver</li>
<li>drive straight towards nebraska</li>
<li>again take right on rockpoint</li>
<li>drive towards marryville</li>
<li>we will reach our destination marryville</li>
</ol>
<ul>
<li>Food</li>
<li>Drinks</li>
</ul>
<a href=https://github.com/dheemanthreddy/assignment2-Sanku/blob/main/README.md>AboutMe</a>
<hr></hr>
<h4>FOOD SECTION</h4>
<p>here comes the menu of the food</p>
<table>
  <tr>
    <th>Food/Drinks</th>
    <th>Location</th>
    <th>Cost</th>
  </tr>
  <tr>
    <td>Burger</td>
    <td>Burger King</td>
    <td>$5</td>
  </tr>
  <tr>
    <td>Biryani</td>
    <td>Flavours</td>
    <td>$12</td>
  </tr>
  <tr>
    <td>Coke</td>
    <td>Wallmart</td>
    <td>$1</td>
  </tr>
</table>
<a href=https://github.com/dheemanthreddy/assignment2-Sanku/blob/main/AboutMe.md >AboutMe</a>
<hr><h5>Quotes</h5>
<blockquote><q>If life were predictable it would cease to be life, and be without flavor -<i>Eleanor Roosevelt </i></q><br>
<q>The greatest glory in living lies not in never falling, but in rising every time we fall -<i> Nelson Mandela</i></q>
</blockquote >
</hr>
<hr><h5>Polygons-Oriented area of a triangle</h5>
<blockquote><q>There are formulas for the area of a triangle in terms of the coordinates of the vertices that automatically give the algebraic area. For example, to find the algebraic area of a triangle with first vertex at (0, 0), second vertex at (a, b) and third vertex at (c, d), we may use the formula (1/2)(ad - bc). This will be positive if the slope d/c of the line from (0, 0) through (c, d) is greater than the slope b/a of the line from (0, 0) through (a, b), since d/c > b/a implies that ad > bc and ad - bc > 0. In terms of vectors, if the line along (a, b) rotates in a counterclockwise direction to get to the line along (c, d), then the triangle from (0, 0) to (a, b) to (c, d) has positive area, and if it rotates in a clockwise direction, the algebraic area of the triangle is negative.
</q></blockquote>
<a href=https://www.techhouse.org/~mdp/midpoint/oriented1.php >Source link for definition </a><br>

```
int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}
```

<br>
<a href=https://cp-algorithms.com/geometry/oriented-triangle-area.html >Source link for code </a>



</hr>