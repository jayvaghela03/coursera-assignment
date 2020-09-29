<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Pseudo Class Selectors</title>
<style>
/* Styles go here. */
header li {
  list-style: none;
}
a:link, a:visited {
  text-decoration: none;
  background-color: green;
  border: 1px solid blue;
  color: black;
  display: block;
  width: 200px;
  text-align: center;
  margin-bottom: 1px;
}

a:hover, a:active {
  background-color: red;
  color: purple;
}

header li:nth-child(3) {
  font-size: 24px;
}

section div:nth-child(odd) {
  background-color: gray;
}

section div:nth-child(4):hover {
  background-color: green;
  cursor: pointer;
}

</style>
</head>
<body>
<h1>Pseudo Class Selectors</h1>

<header>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="http://goo.gl/V0Wl6s" target="_blank">AngularJS Course</a></li>
    <li><a href="http://www.facebook.com/CourseraWebDev" target="_blank">Facebook Fan Page</a></li>
  </ul>
</header>

<section>
  <div>DIV 1</div>
  <div>DIV 2</div>
  <div>DIV 3</div>
  <div>DIV 4</div>
  <div>DIV 5</div>
  <div>DIV 6</div>
  <div>DIV 7</div>
  <div>DIV 8</div>
  <div>DIV 9</div>
  <div>DIV 10</div>
  <div>DIV 11</div>
  <div>DIV 12</div>
  <div>DIV 13</div>
  <div>DIV 14</div>
  <div>DIV 15</div>
  <div>DIV 16</div>
  <div>DIV 17</div>
  <div>DIV 18</div>
  <div>DIV 19</div>
  <div>DIV 20</div>
</section>

</body>
</html>
