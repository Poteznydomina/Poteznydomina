- 👋 Hi, I’m @Poteznydomina
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Poteznydomina/Poteznydomina is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<form action-"przetworzzamowien le php" method=post

<table border-0

<tr bacolor #cccccc>

<td width- 150">Produkt</td>

</tr> stre

<td>Opony</td>

<td align="center"><input type="text" name="iloscopon" size="3" maxlength="3"></td>

</tr>

<td>Olej</td> <td align="center"><input type="text" name="iloscoleju" size="3" maxlength="3"></td>

</tr>

str

<td>Swince Zapłonowe</td>

<td align="center"><input type="text" name="iloscswiec" size="3" maxlength="3"></td>

</tr>

stre

<td colspan="2" align="center"><input type="submit" value="2162 zamówienie?></td>

</tr>

</table>

</form









<html>

<head>

<title>Części samochodowe Janka</title>

</head>

<body>

<h1>Części samochodowe Janka</h1>

<h2>Formularz zamówienia</h2>

<form action="przetworzzamowienie.php" method=post>

<table border=0>

Extr bgcolor=#cccccc>

<td width=150>Produkt</td>

<td width=15>Ilość</td>

</tr>

□<tr>

<td>Opony</td>

<td align=left><input type="text" name="iloscopon" size=3 maxlength=3></td>

</tr>

<tr>

<td>olej</td>

<td align=left><input type="text" name="iloscoleju" size=3 maxlength=3></td>

</tr>

<tr>

<td>Świece Zapłonowe</td>

<td align=left><input type="text" name="iloscswiec" size=3 maxlength=3></td>

</tr> <tr>

<td>Adres</td>

<td align=left><input type="text" name="adres" size=40 maxlength=40></td>

</tr>

<tr>

<td colspan=2 align=center><input type=submit value="złóż zamówienie"></td

>

</tr> </table>

L</form>

</body>

</html>












$data-date('Hi, is y

echo powienie przyjęte n':

echo $data echo pr

echo Zamwionis Panntwa wygląda nantega001 </p>

if Silose #01

echo przedniej stronie nie zato złożone żadne zawione! <br />

else


if ($iloscopon>0

)

39

echo $iloscopon.

opon<br />';

40

if($iloscoleju>0

echo $iloscoleju. butelek oleju<br />';

42

if($iloscswiec>0) echo $iloscswiec. świec zapłonowych<br />':

43

44

45

46 47

$wartosc 0.00;

48 49

define (CENAOPON, 100)/ define('CENAOLEJU, 10):

define('CENASWIEC, 4);

Swartosc -$iloscopon CENAOPON+ $iloscoleju CENAOLEJU Siloscawiec CENASWIEC:

50

51

52

53

54

55

56

Swartosc number_format($wartosc, 2, ., 9

echo '<P>Wartość zamówienia wynosi .Swartosc.'</p>'

;

57

58

59

echo '<P>Adres wysylki to '.$adres. '</p>';

60

61

Sciagwyjsciowy $data."\t".$iloscopon." opon \t".Siloscoleju." butelek oleju\t"

Siloscswiec," swiec zapłonowych\t".Swartosc "PLN/t". $adres. "

// otwarcie pliku w celu dopisywania

@ $wp fopen("$DOCUMENT_ROOT/../zamowienia/zamowienia.txt", 'ab');

66

67

68

69

if (!$wp)

t

echo '<p><strong> Zamówienie Państwa nie może zostać przyjęte w tej .'Proszę spróbować później.</strong></p></body></html>';

chwili.

exit;

formularzht

fwrite ($wp, $ciagwyjsciowy, strlen($ciagwyjsciowy)); fclose($wp);

echo '<p>Zamówienie zapisane.</p>';

-?>

</body>

</html>
