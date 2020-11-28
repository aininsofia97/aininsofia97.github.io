<!-- ========= END OF TOP NAVBAR ========= -->
<span class="skip-nav" id="skip.navbar.top">
<!--   -->
</span></nav>
</header>
<div class="flex-content">
<main role="main">
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h1 title="Class WebScrapping" class="title">Class WebScrapping</h1>
</div>
<div class="inheritance" title="Inheritance Tree">java.lang.Object
<div class="inheritance">WebScrapping</div>
</div>
<section class="description">
<hr>
<pre>public class <span class="type-name-label">WebScrapping</span>
extends java.lang.Object</pre>
<div class="block">This the main class which the project should be run
 It will call other methods is other classes
 It also prints list of registered students, list of students who made comment and list of student who did not comment</div>
</section>
<section class="summary">
<ul class="summary-list">
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<li>
<section class="constructor-summary" id="constructor.summary">
<h2>Constructor Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Constructors</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Constructor</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<th class="col-constructor-name" scope="row"><code><span class="member-name-link"><a href="#%3Cinit%3E()">WebScrapping</a></span>()</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ========== METHOD SUMMARY =========== -->
<li>
<section class="method-summary" id="method.summary">
<h2>Method Summary</h2>
<div class="member-summary" id="method-summary-table">
<div class="table-tabs" role="tablist" aria-orientation="horizontal"><button role="tab" aria-selected="true" aria-controls="method-summary-table.tabpanel" tabindex="0" onkeydown="switchTab(event)" id="t0" class="active-table-tab">All Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t1" class="table-tab" onclick="show(1);">Static Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t4" class="table-tab" onclick="show(8);">Concrete Methods</button></div>
<div id="method-summary-table.tabpanel" role="tabpanel">
<table class="summary-table" aria-labelledby="t0">
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Method</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color" id="i0">
<td class="col-first"><code>static boolean</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#isNotNullOrEmpty(java.lang.String)">isNotNullOrEmpty</a></span>&#8203;(java.lang.String&nbsp;str)</code></th>
<td class="col-last">
<div class="block">This methods will check whether the input string empty or not empty</div>
</td>
</tr>
<tr class="row-color" id="i1">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#main(java.lang.String%5B%5D)">main</a></span>&#8203;(java.lang.String[]&nbsp;args)</code></th>
<td class="col-last">&nbsp;</td>
</tr>
<tr class="alt-color" id="i2">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#PrintNotSubmit(java.lang.String%5B%5D%5B%5D)">PrintNotSubmit</a></span>&#8203;(java.lang.String[][]&nbsp;studNotSubmit)</code></th>
<td class="col-last">
<div class="block">This method will display/print list of students who did not comment</div>
</td>
</tr>
<tr class="row-color" id="i3">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#PrintRegisteredStudent(java.lang.String%5B%5D%5B%5D)">PrintRegisteredStudent</a></span>&#8203;(java.lang.String[][]&nbsp;regStud)</code></th>
<td class="col-last">
<div class="block">This method will display/print list of students who registered for the class</div>
</td>
</tr>
<tr class="alt-color" id="i4">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#PrintStudentComment(java.lang.String%5B%5D%5B%5D)">PrintStudentComment</a></span>&#8203;(java.lang.String[][]&nbsp;studComment)</code></th>
<td class="col-last">
<div class="block">This method will display/print list of students who made comment</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="inherited-list">
<h3 id="methods.inherited.from.class.java.lang.Object">Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait</code></div>
</section>
</li>
</ul>
</section>
<section class="details">
<ul class="details-list">
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<li>
<section class="constructor-details" id="constructor.detail">
<h2>Constructor Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="&lt;init&gt;()">
<h3>WebScrapping</h3>
<div class="member-signature"><span class="modifiers">public</span>&nbsp;<span class="member-name">WebScrapping</span>()</div>
</section>
</li>
</ul>
</section>
</li>
<!-- ============ METHOD DETAIL ========== -->
<li>
<section class="method-details" id="method.detail">
<h2>Method Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="main(java.lang.String[])">
<h3>main</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">main</span>&#8203;(<span class="parameters">java.lang.String[]&nbsp;args)</span>
                 throws <span class="exceptions">java.io.IOException</span></div>
<dl class="notes">
<dt>Throws:</dt>
<dd><code>java.io.IOException</code></dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="PrintRegisteredStudent(java.lang.String[][])">
<h3>PrintRegisteredStudent</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">PrintRegisteredStudent</span>&#8203;(<span class="parameters">java.lang.String[][]&nbsp;regStud)</span></div>
<div class="block">This method will display/print list of students who registered for the class</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>regStud</code> - It will accept the list of registered students</dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="PrintStudentComment(java.lang.String[][])">
<h3>PrintStudentComment</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">PrintStudentComment</span>&#8203;(<span class="parameters">java.lang.String[][]&nbsp;studComment)</span></div>
<div class="block">This method will display/print list of students who made comment</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>studComment</code> - It will accept the list of registered students</dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="PrintNotSubmit(java.lang.String[][])">
<h3>PrintNotSubmit</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">PrintNotSubmit</span>&#8203;(<span class="parameters">java.lang.String[][]&nbsp;studNotSubmit)</span></div>
<div class="block">This method will display/print list of students who did not comment</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>studNotSubmit</code> - It will accept the list of students who did not comment</dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="isNotNullOrEmpty(java.lang.String)">
<h3>isNotNullOrEmpty</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">boolean</span>&nbsp;<span class="member-name">isNotNullOrEmpty</span>&#8203;(<span class="parameters">java.lang.String&nbsp;str)</span></div>
<div class="block">This methods will check whether the input string empty or not empty</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>str</code> - input string</dd>
<dt>Returns:</dt>
<dd>boolean indicate empty or not empty</dd>
</dl>
</section>
</li>
</ul>
</section>
</li>
</ul>
</section>
<!-- ========= END OF CLASS DATA ========= -->
</main>
</html>

<!DOCTYPE HTML>
<!-- NewPage -->
<html lang="en">
<head>
<!-- Generated by javadoc (15) on Sat Nov 28 15:54:33 SGT 2020 -->
<!-- ========= END OF TOP NAVBAR ========= -->
<span class="skip-nav" id="skip.navbar.top">
<!--   -->
</span></nav>
</header>
<div class="flex-content">
<main role="main">
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h1 title="Class StudentComment" class="title">Class StudentComment</h1>
</div>
<div class="inheritance" title="Inheritance Tree">java.lang.Object
<div class="inheritance">StudentComment</div>
</div>
<section class="description">
<hr>
<pre>public class <span class="type-name-label">StudentComment</span>
extends java.lang.Object</pre>
<div class="block">This class will read students' comments from https://github.com/STIW3054-A201/Main-Data/issues/1
 It extracts number, matric number, name and Github link</div>
</section>
<section class="summary">
<ul class="summary-list">
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<li>
<section class="constructor-summary" id="constructor.summary">
<h2>Constructor Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Constructors</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Constructor</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<th class="col-constructor-name" scope="row"><code><span class="member-name-link"><a href="#%3Cinit%3E()">StudentComment</a></span>()</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ========== METHOD SUMMARY =========== -->
<li>
<section class="method-summary" id="method.summary">
<h2>Method Summary</h2>
<div class="member-summary" id="method-summary-table">
<div class="table-tabs" role="tablist" aria-orientation="horizontal"><button role="tab" aria-selected="true" aria-controls="method-summary-table.tabpanel" tabindex="0" onkeydown="switchTab(event)" id="t0" class="active-table-tab">All Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t1" class="table-tab" onclick="show(1);">Static Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t4" class="table-tab" onclick="show(8);">Concrete Methods</button></div>
<div id="method-summary-table.tabpanel" role="tabpanel">
<table class="summary-table" aria-labelledby="t0">
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Method</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color" id="i0">
<td class="col-first"><code>static boolean</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#isNotNullOrEmpty(java.lang.String)">isNotNullOrEmpty</a></span>&#8203;(java.lang.String&nbsp;str)</code></th>
<td class="col-last">
<div class="block">This methods will check whether the input string empty or not empty</div>
</td>
</tr>
<tr class="row-color" id="i1">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#main(java.lang.String%5B%5D)">main</a></span>&#8203;(java.lang.String[]&nbsp;args)</code></th>
<td class="col-last">&nbsp;</td>
</tr>
<tr class="alt-color" id="i2">
<td class="col-first"><code>static java.lang.String[][]</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#Return_Array()">Return_Array</a></span>()</code></th>
<td class="col-last">
<div class="block">This method will read students' comments from https://github.com/STIW3054-A201/Main-Data/issues/1
 It extracts number, matric number, name and Github link</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="inherited-list">
<h3 id="methods.inherited.from.class.java.lang.Object">Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait</code></div>
</section>
</li>
</ul>
</section>
<section class="details">
<ul class="details-list">
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<li>
<section class="constructor-details" id="constructor.detail">
<h2>Constructor Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="&lt;init&gt;()">
<h3>StudentComment</h3>
<div class="member-signature"><span class="modifiers">public</span>&nbsp;<span class="member-name">StudentComment</span>()</div>
</section>
</li>
</ul>
</section>
</li>
<!-- ============ METHOD DETAIL ========== -->
<li>
<section class="method-details" id="method.detail">
<h2>Method Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="main(java.lang.String[])">
<h3>main</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">main</span>&#8203;(<span class="parameters">java.lang.String[]&nbsp;args)</span>
                 throws <span class="exceptions">java.io.IOException</span></div>
<dl class="notes">
<dt>Throws:</dt>
<dd><code>java.io.IOException</code></dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="isNotNullOrEmpty(java.lang.String)">
<h3>isNotNullOrEmpty</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">boolean</span>&nbsp;<span class="member-name">isNotNullOrEmpty</span>&#8203;(<span class="parameters">java.lang.String&nbsp;str)</span></div>
<div class="block">This methods will check whether the input string empty or not empty</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>str</code> - input string</dd>
<dt>Returns:</dt>
<dd>boolean indicate empty or not empty</dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="Return_Array()">
<h3>Return_Array</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">java.lang.String[][]</span>&nbsp;<span class="member-name">Return_Array</span>()</div>
<div class="block">This method will read students' comments from https://github.com/STIW3054-A201/Main-Data/issues/1
 It extracts number, matric number, name and Github link</div>
<dl class="notes">
<dt>Returns:</dt>
<dd>listStudCmt list of students who comment</dd>
</dl>
</section>
</li>
</ul>
</section>
</li>
</ul>
</section>
<!-- ========= END OF CLASS DATA ========= -->
</main>
<footer role="contentinfo">
<nav role="navigation">
<!-- ======= START OF BOTTOM NAVBAR ==
</body>
</html>

<!DOCTYPE HTML>
<!-- NewPage -->
<html lang="en">
<head>
<!-- Generated by javadoc (15) on Sat Nov 28 15:54:33 SGT 2020 -->
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h1 title="Class NotSubmit" class="title">Class NotSubmit</h1>
</div>
<div class="inheritance" title="Inheritance Tree">java.lang.Object
<div class="inheritance">NotSubmit</div>
</div>
<section class="description">
<hr>
<pre>public class <span class="type-name-label">NotSubmit</span>
extends java.lang.Object</pre>
<div class="block">This class will find name of students who do not submit
 It compares list of student against list</div>
</section>
<section class="summary">
<ul class="summary-list">
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<li>
<section class="constructor-summary" id="constructor.summary">
<h2>Constructor Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Constructors</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Constructor</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<th class="col-constructor-name" scope="row"><code><span class="member-name-link"><a href="#%3Cinit%3E()">NotSubmit</a></span>()</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ========== METHOD SUMMARY =========== -->
<li>
<section class="method-summary" id="method.summary">
<h2>Method Summary</h2>
<div class="member-summary" id="method-summary-table">
<div class="table-tabs" role="tablist" aria-orientation="horizontal"><button role="tab" aria-selected="true" aria-controls="method-summary-table.tabpanel" tabindex="0" onkeydown="switchTab(event)" id="t0" class="active-table-tab">All Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t1" class="table-tab" onclick="show(1);">Static Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t4" class="table-tab" onclick="show(8);">Concrete Methods</button></div>
<div id="method-summary-table.tabpanel" role="tabpanel">
<table class="summary-table" aria-labelledby="t0">
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Method</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color" id="i0">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#main(java.lang.String%5B%5D)">main</a></span>&#8203;(java.lang.String[]&nbsp;args)</code></th>
<td class="col-last">&nbsp;</td>
</tr>
<tr class="row-color" id="i1">
<td class="col-first"><code>static java.lang.String[][]</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#Return_Array(java.lang.String%5B%5D%5B%5D,java.lang.String%5B%5D%5B%5D)">Return_Array</a></span>&#8203;(java.lang.String[][]&nbsp;regStudArr,
java.lang.String[][]&nbsp;studComArr)</code></th>
<td class="col-last">
<div class="block">This method is to find students who do not submit</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="inherited-list">
<h3 id="methods.inherited.from.class.java.lang.Object">Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait</code></div>
</section>
</li>
</ul>
</section>
<section class="details">
<ul class="details-list">
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<li>
<section class="constructor-details" id="constructor.detail">
<h2>Constructor Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="&lt;init&gt;()">
<h3>NotSubmit</h3>
<div class="member-signature"><span class="modifiers">public</span>&nbsp;<span class="member-name">NotSubmit</span>()</div>
</section>
</li>
</ul>
</section>
</li>
<!-- ============ METHOD DETAIL ========== -->
<li>
<section class="method-details" id="method.detail">
<h2>Method Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="main(java.lang.String[])">
<h3>main</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">main</span>&#8203;(<span class="parameters">java.lang.String[]&nbsp;args)</span>
                 throws <span class="exceptions">java.io.IOException</span></div>
<dl class="notes">
<dt>Throws:</dt>
<dd><code>java.io.IOException</code></dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="Return_Array(java.lang.String[][],java.lang.String[][])">
<h3>Return_Array</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">java.lang.String[][]</span>&nbsp;<span class="member-name">Return_Array</span>&#8203;(<span class="parameters">java.lang.String[][]&nbsp;regStudArr,
java.lang.String[][]&nbsp;studComArr)</span></div>
<div class="block">This method is to find students who do not submit</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>regStudArr</code> - list of registered students</dd>
<dd><code>studComArr</code> - list of student who submit</dd>
<dt>Returns:</dt>
<dd>studNotSubmit list of students who do not submit</dd>
</dl>
</section>
</li>
</ul>
</section>
</li>
</ul>
</section>
<!-- ========= END OF CLASS DATA ========= -->
</main>
</body>
</html>

<!DOCTYPE HTML>
<!-- NewPage -->
<html lang="en">
<head>
<!-- Generated by javadoc (15) on Sat Nov 28 15:54:33 SGT 2020 -->
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h1 title="Class RegisteredStudent" class="title">Class RegisteredStudent</h1>
</div>
<div class="inheritance" title="Inheritance Tree">java.lang.Object
<div class="inheritance">RegisteredStudent</div>
</div>
<section class="description">
<hr>
<pre>public class <span class="type-name-label">RegisteredStudent</span>
extends java.lang.Object</pre>
<div class="block">This class will read List of Students from https://github.com/STIW3054-A201/Main-Data/wiki/List_of_Student
 It extracts matric number and name</div>
</section>
<section class="summary">
<ul class="summary-list">
<!-- =========== FIELD SUMMARY =========== -->
<li>
<section class="field-summary" id="field.summary">
<h2>Field Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Fields</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Field</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<td class="col-first"><code>static int</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#size">size</a></span></code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<li>
<section class="constructor-summary" id="constructor.summary">
<h2>Constructor Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Constructors</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Constructor</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<th class="col-constructor-name" scope="row"><code><span class="member-name-link"><a href="#%3Cinit%3E()">RegisteredStudent</a></span>()</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ========== METHOD SUMMARY =========== -->
<li>
<section class="method-summary" id="method.summary">
<h2>Method Summary</h2>
<div class="member-summary" id="method-summary-table">
<div class="table-tabs" role="tablist" aria-orientation="horizontal"><button role="tab" aria-selected="true" aria-controls="method-summary-table.tabpanel" tabindex="0" onkeydown="switchTab(event)" id="t0" class="active-table-tab">All Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t1" class="table-tab" onclick="show(1);">Static Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t4" class="table-tab" onclick="show(8);">Concrete Methods</button></div>
<div id="method-summary-table.tabpanel" role="tabpanel">
<table class="summary-table" aria-labelledby="t0">
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Method</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color" id="i0">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#main(java.lang.String%5B%5D)">main</a></span>&#8203;(java.lang.String[]&nbsp;args)</code></th>
<td class="col-last">&nbsp;</td>
</tr>
<tr class="row-color" id="i1">
<td class="col-first"><code>static java.lang.String[][]</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#Return_Array()">Return_Array</a></span>()</code></th>
<td class="col-last">
<div class="block">This method will read https://github.com/STIW3054-A201/Main-Data/wiki/List_of_Student
 Then it will extract matric number and name of registered students</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="inherited-list">
<h3 id="methods.inherited.from.class.java.lang.Object">Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait</code></div>
</section>
</li>
</ul>
</section>
<section class="details">
<ul class="details-list">
<!-- ============ FIELD DETAIL =========== -->
<li>
<section class="field-details" id="field.detail">
<h2>Field Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="size">
<h3>size</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">int</span>&nbsp;<span class="member-name">size</span></div>
</section>
</li>
</ul>
</section>
</li>
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<li>
<section class="constructor-details" id="constructor.detail">
<h2>Constructor Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="&lt;init&gt;()">
<h3>RegisteredStudent</h3>
<div class="member-signature"><span class="modifiers">public</span>&nbsp;<span class="member-name">RegisteredStudent</span>()</div>
</section>
</li>
</ul>
</section>
</li>
<!-- ============ METHOD DETAIL ========== -->
<li>
<section class="method-details" id="method.detail">
<h2>Method Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="main(java.lang.String[])">
<h3>main</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">main</span>&#8203;(<span class="parameters">java.lang.String[]&nbsp;args)</span>
                 throws <span class="exceptions">java.io.IOException</span></div>
<dl class="notes">
<dt>Throws:</dt>
<dd><code>java.io.IOException</code></dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="Return_Array()">
<h3>Return_Array</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">java.lang.String[][]</span>&nbsp;<span class="member-name">Return_Array</span>()</div>
<div class="block">This method will read https://github.com/STIW3054-A201/Main-Data/wiki/List_of_Student
 Then it will extract matric number and name of registered students</div>
<dl class="notes">
<dt>Returns:</dt>
<dd>regStud list of registered student in an array</dd>
</dl>
</section>
</li>
</ul>
</section>
</li>
</ul>
</section>
<!-- ========= END OF CLASS DATA ========= -->
</main>
</div>
</body>
</html>

<!DOCTYPE HTML>
<!-- NewPage -->
<html lang="en">
<head>
<!-- Generated by javadoc (15) on Sat Nov 28 15:54:33 SGT 2020 -->
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h1 title="Class CreateExcelFile" class="title">Class CreateExcelFile</h1>
</div>
<div class="inheritance" title="Inheritance Tree">java.lang.Object
<div class="inheritance">CreateExcelFile</div>
</div>
<section class="description">
<hr>
<pre>public class <span class="type-name-label">CreateExcelFile</span>
extends java.lang.Object</pre>
<div class="block">This class will provide the method for writing data in excel files</div>
</section>
<section class="summary">
<ul class="summary-list">
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<li>
<section class="constructor-summary" id="constructor.summary">
<h2>Constructor Summary</h2>
<div class="member-summary">
<table class="summary-table">
<caption><span>Constructors</span></caption>
<thead>
<tr>
<th class="col-first" scope="col">Constructor</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color">
<th class="col-constructor-name" scope="row"><code><span class="member-name-link"><a href="#%3Cinit%3E()">CreateExcelFile</a></span>()</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</section>
</li>
<!-- ========== METHOD SUMMARY =========== -->
<li>
<section class="method-summary" id="method.summary">
<h2>Method Summary</h2>
<div class="member-summary" id="method-summary-table">
<div class="table-tabs" role="tablist" aria-orientation="horizontal"><button role="tab" aria-selected="true" aria-controls="method-summary-table.tabpanel" tabindex="0" onkeydown="switchTab(event)" id="t0" class="active-table-tab">All Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t1" class="table-tab" onclick="show(1);">Static Methods</button><button role="tab" aria-selected="false" aria-controls="method-summary-table.tabpanel" tabindex="-1" onkeydown="switchTab(event)" id="t4" class="table-tab" onclick="show(8);">Concrete Methods</button></div>
<div id="method-summary-table.tabpanel" role="tabpanel">
<table class="summary-table" aria-labelledby="t0">
<thead>
<tr>
<th class="col-first" scope="col">Modifier and Type</th>
<th class="col-second" scope="col">Method</th>
<th class="col-last" scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr class="alt-color" id="i0">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#ExcelStudentSubmit(java.lang.String%5B%5D%5B%5D,java.lang.String%5B%5D%5B%5D)">ExcelStudentSubmit</a></span>&#8203;(java.lang.String[][]&nbsp;ListStudSubmit,
java.lang.String[][]&nbsp;ListStudNotSubmit)</code></th>
<td class="col-last">
<div class="block">This methods will write list of students who submit in a file
 and it will write list of students who did not submit in another file</div>
</td>
</tr>
<tr class="row-color" id="i1">
<td class="col-first"><code>static boolean</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#isNotNullOrEmpty(java.lang.String)">isNotNullOrEmpty</a></span>&#8203;(java.lang.String&nbsp;str)</code></th>
<td class="col-last">
<div class="block">This methods will check whether the input string empty or not empty</div>
</td>
</tr>
<tr class="alt-color" id="i2">
<td class="col-first"><code>static void</code></td>
<th class="col-second" scope="row"><code><span class="member-name-link"><a href="#main(java.lang.String%5B%5D)">main</a></span>&#8203;(java.lang.String[]&nbsp;args)</code></th>
<td class="col-last">&nbsp;</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="inherited-list">
<h3 id="methods.inherited.from.class.java.lang.Object">Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait</code></div>
</section>
</li>
</ul>
</section>
<section class="details">
<ul class="details-list">
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<li>
<section class="constructor-details" id="constructor.detail">
<h2>Constructor Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="&lt;init&gt;()">
<h3>CreateExcelFile</h3>
<div class="member-signature"><span class="modifiers">public</span>&nbsp;<span class="member-name">CreateExcelFile</span>()</div>
</section>
</li>
</ul>
</section>
</li>
<!-- ============ METHOD DETAIL ========== -->
<li>
<section class="method-details" id="method.detail">
<h2>Method Details</h2>
<ul class="member-list">
<li>
<section class="detail" id="main(java.lang.String[])">
<h3>main</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">main</span>&#8203;(<span class="parameters">java.lang.String[]&nbsp;args)</span>
                 throws <span class="exceptions">java.io.IOException</span></div>
<dl class="notes">
<dt>Throws:</dt>
<dd><code>java.io.IOException</code></dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="ExcelStudentSubmit(java.lang.String[][],java.lang.String[][])">
<h3>ExcelStudentSubmit</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">void</span>&nbsp;<span class="member-name">ExcelStudentSubmit</span>&#8203;(<span class="parameters">java.lang.String[][]&nbsp;ListStudSubmit,
java.lang.String[][]&nbsp;ListStudNotSubmit)</span></div>
<div class="block">This methods will write list of students who submit in a file
 and it will write list of students who did not submit in another file</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>ListStudSubmit</code> - it accept an array containing list of students who submit</dd>
<dd><code>ListStudNotSubmit</code> - it accept an array containing list of students who did not submit</dd>
</dl>
</section>
</li>
<li>
<section class="detail" id="isNotNullOrEmpty(java.lang.String)">
<h3>isNotNullOrEmpty</h3>
<div class="member-signature"><span class="modifiers">public static</span>&nbsp;<span class="return-type">boolean</span>&nbsp;<span class="member-name">isNotNullOrEmpty</span>&#8203;(<span class="parameters">java.lang.String&nbsp;str)</span></div>
<div class="block">This methods will check whether the input string empty or not empty</div>
<dl class="notes">
<dt>Parameters:</dt>
<dd><code>str</code> - input string</dd>
<dt>Returns:</dt>
<dd>boolean indicate empty or not empty</dd>
</dl>
</section>
</li>
</ul>
</section>
</li>
</ul>
</section>
<!-- ========= END OF CLASS DATA ========= -->
 </main>
</body>
</html>
