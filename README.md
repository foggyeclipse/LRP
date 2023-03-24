# Random number generator
Представленный генератор случайных чисел выполнен на основе побайтовой **линейной рекурентной последовательности (ЛРП)**.
**Линейной рекуррентной последовательностью (линейной рекуррентой)** называется всякая числовая последовательность $x_0,x_1, ...,$
задаваемая линейным рекуррентным соотношением:  

$x_n = a_1 * x_{n-1} + ... + a_d * x_{n-d}$ для всех $n>=d$   

c заданными начальными членами $x_0, ..., x_{d-1},$ где  

$d$ — фиксированное натуральное число,    
$a_1, ..., a_d$ — заданные числовые коэффициенты,  $a_d ≠ 0$

При этом число $d$ называется порядком последовательности.

>Линейные рекуррентные последовательности иногда называют также **возвратными последовательностями.**

Пользователю, который собирается запустить данную программу, необходимо задать:

$a_0...a_{k-1},$ — набор коэффициентов  
$x_0 ... x_{k-1},$ — начальные значения для ЛРП 
$c$ — свободный член 

Все числа $a_i, x_i$ и $с$ и операции — это элементы конечного поля $F_{256}$ и соответствующие операции, проивзодимые над ними.
