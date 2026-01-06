---
title: Home
layout: default
---

<html>
<body>
<h1 style="text-align:center;">Introduction</h1>
</body>
</html>

```c++
{
  string name = "Arnas Puidokas";
  string uni = "University of Staffordshire";
  string major = "Computer Games Programming";
  string favouriteSubject = "Graphics";
  int year = Third year;
}
```

<html>
<body>
<h1 style="text-align:center;">Personal Favourite Project (University Project)</h1>
<div style="text-align: center;"> 
  <a href="{{ '/2000/01/01/witchforest.html' | relative_url }"> 
    <img src="{{ '/assets/WitchForest.png' | relative_url }}" alt="Witch Forest" style="width:315px;height:315px;"> 
  </a> 
</div>
</body>
</html>

<html>
<body>
<h1 style="text-align:center;">Personal Project</h1>
<div style="text-align: center;"> 
  <a href="{{ '/2001/01/01/arcade.html' | relative_url }}"> 
    <img src="{{ '/assets/WitchForest.png' | relative_url }}" alt="Witch Forest" style="width:315px;height:315px;"> 
  </a> 
</div>
</body>
</html>

## University Projects
<html> 
<body> 
<h1 style="text-align:center;">University Projects</h1>
<div style="display:flex; flex-direction:column; align-items:center; gap:20px;"> 

  <div style="display:flex; justify-content:center; gap:20px;"> 
    <a href="{{ '/2003/01/01/unity.html' | relative_url }}"> 
      <img src="{{ '/assets/WitchForest.png' | relative_url }}" alt="Witch Forest" style="width:315px;height:315px;"> 
    </a>   
    <a href="{{ '/2026/01/06/another.html' | relative_url }}"> 
      <img src="{{ '/assets/AnotherImage.png' | relative_url }}" alt="Another Image" style="width:315px;height:315px;"> </a> 
  </div>
  
  <div style="display:flex; justify-content:center; gap:20px;"> 
   <a href="{{ '/2026/01/06/third.html' | relative_url }}"> 
      <img src="{{ '/assets/ThirdImage.png' | relative_url }}" alt="Third Image" style="width:315px;height:315px;">
    </a> 
    <a href="{{ '/2026/01/06/fourth.html' | relative_url }}"> 
      <img src="{{ '/assets/FourthImage.png' | relative_url }}" alt="Fourth Image" style="width:315px;height:315px;"> 
   </a> 
  </div> 
</div> 
</body> 
</html>