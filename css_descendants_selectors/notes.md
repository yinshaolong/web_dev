Relative Units         Absolute Units 
-EM                     -PX
-REM                    -PT
-VH                     -CM
-VW                     -IN
-%                      -MM
-ETC

===================================================================================================

One px does not neccasarily equal the width of one pixel!
not recommended for repsonsive websites

===================================================================================================

Descendant Selector
Select all <a> that are in <li>

li a {
  color: red;
}

===================================================================================================

Adjacent Sibling Selector
select all <a> that are directly after <h1>

h1 + a {
  color: red;
}
===================================================================================================
Direct Child Selector
select all <a> that are direct children of <li>

li > a {
  color: red;
}