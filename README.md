# Foreach-
# Esse laço é parecido com o for, possuindo uma sintaxe mais simples e sendo muito propício para realizar interações em arrays. Veja o exemplo:


<?php
 $carros = Array("Fusca", "Monza", "Passat");

 foreach($carros as $carro){
	echo $carro;
	echo "\n";
 }

 for ($i = 0; $i < count($carros); $i++) {
	echo $carros[$i];
	echo "\n";
 }
