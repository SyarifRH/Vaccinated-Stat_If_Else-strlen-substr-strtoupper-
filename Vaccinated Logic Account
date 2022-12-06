<!-- CARA KE 1 -->
<?php

$input = 'jhs675278922';
$str = strlen($input) <= 12 && strlen($input) >= 12;

if ($input != $str) {
    echo "Wrong Vaccination";
} else {
    $pemisah_huruf = substr($input, 0, 3);
    if ($pemisah_huruf = strtoupper($pemisah_huruf)) {
        echo $pemisah_huruf . substr($input, 3, 9);
    }
}
?>
<!-- --------------- -->

<!--Ganti Baris-->
<?php
echo "<br>"
?>
<!-- --------------- -->

<!-- CARA KE 2 -->
<?php
function get($input)
{
    $str = strlen($input) <= 12 && strlen($input) >= 12;

    if ($input != $str) {
        echo "Wrong Vaccination";
    } else {
        $pemisah_huruf = substr($input, 0, 3);
        if ($pemisah_huruf = strtoupper($pemisah_huruf)) {
            $pemisah_huruf . substr($input, 3, 9);
            echo "Right Vaccination Code";
        }
    }
}
echo get('asd234231232');
?>
<!-- --------------- -->
