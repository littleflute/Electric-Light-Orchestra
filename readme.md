[v0.0.4](https://github.com/littleflute/Electric-Light-Orchestra/edit/master/readme.md)
[show this page](https://littleflute.github.io/Yani1/)

[cd-E](cd-E)

[cd-L](cd-L)

[cd-O](cd-O)

<audio controls id="player"> 
  <source src="https://littleflute.github.io/Electric-Light-Orchestra/Afterglow/cd-E/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn(1);
html += fNewBtn(2);
html += fNewBtn(3);
html += fNewBtn(4);
html += fNewBtn(5);
html += fNewBtn(6);
html += fNewBtn(7);
 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/Electric-Light-Orchestra/Afterglow/cd-E/0";
    s += i;
    s += "_曲目 ";
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>



