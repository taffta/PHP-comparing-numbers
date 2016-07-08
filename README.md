# PHP-comparing-numbers
<?php
function date_format($date)

    $year = substr ($date, 0, 4);
    $month = substr ($date, 4, 2};
    $day = substr ($date, 6, 2};
switch ($month)
{
    case 01:
        $month = "Января";
        break;
    case 02:
        $month = "Февраля";
        break;
    case 03:
        $month = "Марта";
        break;
    case 04:
        $month = "Апреля";
        break;
    case 05:
        $month = "Мая";
        break;
    case 06:
        $month = "Июня";
        break;
    case 07:
        $month = "Июля";
        break;
    case 08:
        $month = "Августа";
        break;
    case 09:
        $month = "Сентября";
        break;
    case 10:
        $month = "Октября";
        break;
    case 11:
        $month = "Ноября";
        break;
    case 12:
        $month = "Декабря";
        break;
}
$date = "$day $month $year г.";
echo $date;
}

$date = date("Ymd");
date_format ($date);
?>
