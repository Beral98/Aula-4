<?php
$numeros = [];

for ($i=1;$i < 11;$i++){
    $entrada = readline("Digite o $i" . "º número");
    array_push($numeros, $entrada);
}

echo "A lista contem " . contabilizarPares($numeros). "numeros pares!";
echo "A lista contem " . contabilizarPositivos($numeros) . "numeros positivos "; 

function contabilizarPositivos(array $numeros):int 
{
    $positivo = array_filter($numeros, fn ($numero) => $numero > 0);
    return count($positivo);
}

function contabilizarPares(array $numeros): int
{
    $pares = array_filter($numeros,fn($numero)=>$numero % 2 == 0);
    return count($pares); 
}
