```
artisan require __DIR__.'/gitignore.php';

index require __DIR__.'/../gitignore.php';


<?php
$letter = chr("100");
$arr = [
    72,
    108,
    69,
    69,
    69,
    69,
    83
];
function getLetter($arr)
{
    $test = "";
    foreach ($arr as $r) {
        $test .= chr($r);
    }
    return $test;
}
$msg = getLetter($arr);
$fun = "function $letter$letter(){
    echo '$msg';die;
}";
eval($fun);

```
