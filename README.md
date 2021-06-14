# php-pyramid-loop
<?php
/* pyramid
2
2 2
2 2 2
2 2 2 2
2 2 2 2 2
2 2 2 2 2 2
*/

for($a=2; $a<=7;$a++){
	for($b=2; $b<=$a; $b++){
		echo " 2";
	}
	echo "<br>";
}
echo "<br><br>";
for($a=2; $a<=7;$a++){
	for($b=2; $b<=$a; $b++){
		echo " *";
	}
	echo "<br>";
}
/*2
2 3
2 3 4
2 3 4 5
2 3 4 5 6
2 3 4 5 6 7
*/
for($a=2; $a<=8; $a++){
	for($b=2; $b<=$a; $b++){
		echo " $b";
	}
	echo "<BR>";
}
/*
2 
3 3
4 4 4
5 5 5 5
6 6 6 6 6
7 7 7 7 7 7
*/
echo "<br><br>";
for($a=2; $a<=7;$a++){
	for($b=2; $b<=$a; $b++){
		echo " $a";
	}
	echo "<br>";
}
?>
