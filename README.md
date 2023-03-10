# LINQ-SetsOperations


> **&raquo;**	**.Concat()**  &rarr;	use to cancat to lists together and return IEnumerable<T> where T is the type of list member

## .Distinct() 
<li> Returns distinct elements from a sequence by using the default equality comparer to compare values</li>
<li> You need to <b>override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>

## .DistinctBy()
<li>Returns distinct elements from a sequence according to a specified key selector function.</li>
<li> You don't need to <b> override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>
<hr>

## .Except() 
<li> Returns a sequance that contains the set defferance of the elements of two sequences</li>
<li> You need to <b>override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>

## .ExceptBy()
<li>Returns a sequance that contains the set defferance of the elements of two sequences according to a specified key selector function.</li>
<li> You don't need to <b> override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>
<hr>

## .Intersect() 
<li>Produces the set intersection of two sequences</li>
<li> You need to <b>override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>

## .IntersectBy()
<li>Produces the set intersection of two sequences according to a specified key selector function.</li>
<li> You don't need to <b> override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>
<hr>

## .Union() 
<li>Produces the set union of two sequences.</li>
<li> You need to <b>override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>

## .UnionBy()
<li>Produces the set union of two sequences according to a specified key selector function.</li>
<li> You don't need to <b> override Equals() and GetHashCode()</b> to make Distinct() function don't repeat object on the property you want</li>
