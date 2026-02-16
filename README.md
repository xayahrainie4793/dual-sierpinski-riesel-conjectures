* Original Sierpinski conjecture base *b*: Finding and proving the smallest *k* such that *k*×*b*<sup>*n*</sup>+1 is composite for all *n* ≥ 1
* Original Riesel conjecture base *b*: Finding and proving the smallest *k* such that *k*×*b*<sup>*n*</sup>−1 is composite for all *n* ≥ 1
* Dual Sierpinski conjecture base *b*: Finding and proving the smallest *k* such that *b*<sup>*n*</sup>+*k* is composite for all *n* ≥ 1
* Dual Riesel conjecture base *b*: Finding and proving the smallest *k* such that *b*<sup>*n*</sup>−*k* is composite for all *n* ≥ 1 such that *b*<sup>*n*</sup> > *k*+1

(for more information of "dual", see: http://www.kurims.kyoto-u.ac.jp/EMIS/journals/INTEGERS/papers/i61/i61.pdf (cached copy at https://github.com/xayahrainie4793/pdf-files-cached-copy/blob/main/pdf_1.pdf), https://www.rechenkraft.net/wiki/Five_or_Bust, https://oeis.org/A076336/a076336c.html, http://www.mit.edu/~kenta/three/prime/dual-sierpinski/ezgxggdm/dualsierp-excerpt.txt, http://web.mit.edu/kenta/www/three/prime/dual-sierpinski/ezgxggdm/dualsierp.txt.gz, https://www.primegrid.com/download/5ob_all.html, http://www.bitman.name/math/article/1126 (in Italian), http://www.bitman.name/math/article/1125 (in Italian), https://www.mersenneforum.org/showpost.php?p=144991&postcount=1, https://www.mersenneforum.org/showthread.php?t=10761, https://www.mersenneforum.org/showthread.php?t=6545)

Requirements and inclusions:

1. Conjectures must have a finite covering set
2. Primes must be *n* ≥ 1
3. *k*-values that are a multiple of base (*b*) are included in the conjectures (for original Sierpinski/Riesel conjectures) but some may be excluded. See exclusion 4 below

*k*-values with any of the following conditions are excluded from the conjectures:

1. All *n*-values are covered by one trivial factor (i.e. *gcd*(*k*,*b*) > 1 (for dual Sierpinski/Riesel conjectures) or *gcd*(*k*+1,*b*−1) > 1 (for original/dual Sierpinski conjectures) or *gcd*(*k*−1,*b*−1) > 1 (for original/dual Riesel conjectures)
2. All *n*-values are covered by algebraic factors or a combination of algebraic and trivial factor(s)
3. Make generalized Fermat numbers, i.e. *q*<sup>*m*</sup>×*b*<sup>*n*</sup>+1 where *m* ≥ 0 and *q* is a root of the base *b* (for original Sierpinski conjectures) or *b*<sup>*n*</sup>+1 (for dual Sierpinski conjectures)
4. *k* is a multiple of base (*b*) and *k*+1 (for Sierpinski) or *k*−1 (for Riesel) is not prime. They will have the same prime as *k*/*b* (for original Sierpinski/Riesel conjectures)

|*b*|conjectured smallest original Sierpinski *k*|covering set of this original Sierpinski *k*|conjectured smallest original Riesel *k*|covering set of this original Riesel *k*|conjectured smallest dual Sierpinski *k*|covering set of this dual Sierpinski *k*|conjectured smallest dual Riesel *k*|covering set of this dual Riesel *k*|
|---|---|---|---|---|---|---|---|---|
|2|78557|3, 5, 7, 13, 19, 37, 73|509203|3, 5, 7, 13, 17, 241|78557|3, 5, 7, 13, 19, 37, 73|509203|3, 5, 7, 13, 17, 241|
|3|125050976086|5, 7, 13, 17, 19, 37, 41, 193, 757|63064644938|5, 7, 13, 17, 19, 37, 41, 193, 757|125050976086|5, 7, 13, 17, 19, 37, 41, 193, 757|63064644938|5, 7, 13, 17, 19, 37, 41, 193, 757|
|4|66741|5, 7, 13, 17, 241|39939|5, 7, 13, 19, 73, 109|66741|5, 7, 13, 17, 241|39939|5, 7, 13, 19, 73, 109|
|5|159986|3, 7, 13, 31, 601|346802|3, 7, 13, 31, 601|159986|3, 7, 13, 31, 601|346802|3, 7, 13, 31, 601|
|6|174308|7, 13, 31, 37, 97|84687|7, 13, 31, 37, 97|282001|7, 13, 31, 43, 97|333845|7, 13, 31, 37, 43|
|7|1112646039348|5, 13, 19, 43, 73, 181, 193, 1201|408034255082|5, 13, 19, 43, 73, 181, 193, 1201|1112646039348|5, 13, 19, 43, 73, 181, 193, 1201|408034255082|5, 13, 19, 43, 73, 181, 193, 1201|
|8|47|3, 5, 13|14|3, 5, 13|47|3, 5, 13|209|3, 5, 13|
|9|2344|5, 7, 13, 73|74|5, 7, 13, 73|2344|5, 7, 13, 73|18404<br>(although *k* = 74 also has covering set {5, 7, 13, 73}, but 9<sup>2</sup>−74 is indeed 7, thus *k* = 74 is not dual Riesel)|5, 7, 13, 73|
|10|9175|7, 11, 13, 37|10176|7, 11, 13, 37|9351|7, 11, 13, 37|17601|7, 11, 13, 37|
|11|1490|3, 7, 19, 37|862|3, 7, 19, 37|1490|3, 7, 19, 37|862|3, 7, 19, 37|
|12|521|5, 13, 29|376|5, 13, 29|521|5, 13, 29|2261|5, 13, 29|
|13|132|5, 7, 17|302|5, 7, 17|132|5, 7, 17|302|5, 7, 17|
|14|4|3, 5|4|3, 5|11|3, 5|19<br>(although *k* = 11 also has covering set {3, 5}, but 14<sup>1</sup>−11 is indeed 3, thus *k* = 11 is not dual Riesel)|3, 5|
|15|91218919470156|13, 17, 113, 211, 241, 1489, 3877|36370321851498|13, 17, 113, 211, 241, 1489, 3877|243887293392172|13, 17, 113, 211, 241, 1489, 3877|101821439769424|13, 17, 113, 211, 241, 1489, 3877|
|16|66741|7, 13, 17, 241|33965|7, 13, 17, 241|66741|7, 13, 17, 241|33965|7, 13, 17, 241|
|17|278|3, 5, 29|86|3, 5, 29|278|3, 5, 29|86|3, 5, 29|
|18|398|5, 13, 19|246|5, 13, 19|571|5, 13, 19|1481|5, 13, 19|
|19|765174|5, 7, 13, 127, 769|1119866|5, 7, 13, 127, 181|765174|5, 7, 13, 127, 769|1119866|5, 7, 13, 127, 181|
|20|8|3, 7|8|3, 7|13|3, 7|29<br>(although *k* = 13 also has covering set {3, 7}, but 20<sup>1</sup>−13 is indeed 7, thus *k* = 13 is not dual Riesel)|3, 7|
|21|1002|11, 13, 17|560|11, 13, 17|7688|11, 13, 17|3268|11, 13, 17|
|22|6694|5, 23, 97|4461|5, 23, 97|16101|5, 23, 97|4461|5, 23, 97|
|23|182|3, 5, 53|476|3, 5, 53|182|3, 5, 53|712<br>(although *k* = 476 also has covering set {3, 5, 53}, but 23<sup>2</sup>−476 is indeed 53, thus *k* = 476 is not dual Riesel)|3, 5, 53|
|24|30651|5, 7, 13, 73, 79|32336|5, 7, 13, 73, 577|176011|5, 7, 13, 73, 79|124031|5, 7, 13, 349, 577|
|25|262638|7, 13, 31, 601|346802|7, 13, 31, 601|262638|7, 13, 31, 601|346802|7, 13, 31, 601|
|26|221|3, 7, 19, 37|149|3, 7, 31, 37|1627|3, 7, 19, 37|149|3, 7, 31, 37|
|27|538|5, 7, 73|804|5, 7, 73|538|5, 7, 73|1268|5, 7, 73|
|28|4554|5, 29, 157|9078|5, 29, 157|8293|5, 29, 157|49299|5, 29, 157|
|29|4|3, 5|4|3, 5|4|3, 5|4|3, 5|
|30|867|7, 13, 19, 31|4928|13, 19, 31, 67|18973|17, 31, 53|11471|17, 31, 53|
|31|6360528|7, 13, 19, 37, 331|134718|7, 13, 19, 37, 331|6360528|7, 13, 19, 37, 331|134718|7, 13, 19, 37, 331|
|32|10|3, 11|10|3, 11|23|3, 11|23|3, 11|
|33|1854|5, 17, 109|764|5, 17, 109|11848|5, 17, 109|764|5, 17, 109|
|34|6|5, 7|6|5, 7|99|5, 7|41<br>(although *k* = 29 also has covering set {5, 7}, but 34<sup>1</sup>−29 is indeed 5, thus *k* = 29 is not dual Riesel)|5, 7|
|35|214018|3, 13, 97, 397|287860|3, 13, 97, 397|292226|3, 13, 97, 397|828538|3, 13, 97, 397|
|36|1886|13, 31, 37, 43|116364|13, 37, 43, 97|11093|13, 31, 43, 97|162503|13, 31, 37, 43|
|37|2604|5, 19, 137|7772|5, 19, 137|2604|5, 19, 137|7772|5, 19, 137|
|38|14|3, 13|13|3, 5, 17|25|3, 13|13|3, 5, 17|
|39|166134|5, 7, 223, 1483|1352534|5, 7, 223, 1483|3112856|5, 7, 223, 1483|1352534|5, 7, 223, 1483|
|40|826477|7, 41, 223, 547|3386517|7, 41, 223, 547|826477|7, 41, 223, 547|3386517|7, 41, 223, 547|
|41|8|3, 7|8|3, 7|8|3, 7|8|3, 7|
|42|13372|5, 43, 353|15137|5, 43, 353|89267|5, 43, 353|15137|5, 43, 353|
|43|2256|5, 11, 37|672|5, 11, 37|2256|5, 11, 37|672|5, 11, 37|
|44|4|3, 5|4|3, 5|19|3, 5|19|3, 5|
|45|53474|7, 19, 23, 109|22564|7, 19, 23, 109|53474|7, 19, 23, 109|22564|7, 19, 23, 109|
|46|14992|7, 19, 47, 103|8177|29, 47, 73|51511|7, 13, 47, 73, 109|8177|29, 47, 73|
|47|8|3, 5, 13|14|3, 5, 13|8|3, 5, 13|14|3, 5, 13|
|48|1219|7, 13, 61, 181|3226|5, 7, 461|1219|7, 13, 61, 181|8807|5, 7, 461|
|49|2944|5, 19, 73, 181, 193|2414|5, 13, 19, 43|2944|5, 19, 73, 181, 193|2414|5, 13, 19, 43|
|50|16|3, 17|16|3, 17|67|3, 17|67|3, 17|
|51|5183582|7, 13, 379, 2551|8632534|7, 13, 379, 2551|5183582|7, 13, 379, 2551|8632534|7, 13, 379, 2551|
|52|28674|5, 53, 541|85967|5, 53, 541|200763|5, 53, 541|85967|5, 53, 541|
|53|1966|3, 5, 281|5392|3, 5, 281|1966|3, 5, 281|5392|3, 5, 281|
|54|21|5, 11|21|5, 11|89|5, 11|89|5, 11|
|55|4416|7, 17, 89|6852|7, 17, 89|4416|7, 17, 89|6852|7, 17, 89|
|56|20|3, 19|20|3, 19|37|3, 19|305<br>(although *k* = 37 also has covering set {3, 19}, but 56<sup>1</sup>−37 is indeed 19, thus *k* = 37 is not dual Riesel)|3, 19|
|57|1188|5, 13, 29|144|5, 13, 29|3626|5, 13, 29|376|5, 13, 29|
|58|43071|5, 59, 673|105788|5, 7, 13, 59, 163|43071|5, 59, 673|119063|5, 59, 673|
|59|4|3, 5|4|3, 5|4|3, 5|4|3, 5|
|60|16957|13, 61, 277|20558|13, 61, 277|16957|13, 61, 277|310003|13, 17, 61, 281|
|61|15168|7, 13, 97, 523|13484|7, 13, 31, 97|15168|7, 13, 97, 523|13484|7, 13, 31, 97|
|62|8|3, 7|8|3, 7|13|3, 7|13|3, 7|
|63|37565868|5, 13, 37, 109, 3907|187258666|5, 13, 37, 109, 3907|(> 37565868, need to be searched, 37565868 is divisible by 3)|?|(> 187258666, need to be searched, 187258666 is divisible by 7)|?|
|64|51|5, 13|14|5, 13|51|5, 13|51|5, 13|
|65|10|3, 11|10|3, 11|56|3, 11|56|3, 11|
|66|21314443|7, 17, 37, 67, 73, 4357|101954772|7, 17, 37, 67, 73, 613|21314443|7, 17, 37, 67, 73, 4357|(> 101954772, need to be searched, 101954772 is divisible by 6)|?|
|67|18342|5, 17, 449|3144|5, 17, 449|18342|5, 17, 449|3144|5, 17, 449|
|68|22|3, 23|22|3, 23|47|3, 23|43|3, 5, 37|
|69|6|5, 7|6|5, 7|64|5, 7|76<br>(although *k* = 64 also has covering set {5, 7}, but 69<sup>1</sup>−64 is indeed 5, thus *k* = 64 is not dual Riesel)|5, 7|
|70|11077|13, 29, 71|6176|13, 29, 71|11077|13, 29, 71|32943|13, 29, 71|
|71|5917678826|3, 19, 37, 73, 1657, 5113|1132052528|3, 13, 37, 73, 109, 1657, 2521|5917678826|3, 19, 37, 73, 1657, 5113|1132052528|3, 13, 37, 73, 109, 1657, 2521|
|72|731|5, 61, 73|293|5, 17, 73|731|5, 61, 73|293|5, 17, 73|
|73|1444|5, 13, 37|408|5, 13, 37|1444|5, 13, 37|408|5, 13, 37|
|74|4|3, 5|4|3, 5|11|3, 5|11|3, 5|
|75|4086|7, 13, 19, 61|4086|7, 13, 19, 61|8492|7, 13, 19, 61|8492|7, 13, 19, 61|
|76|43|7, 11|120|7, 11|43|7, 11|197|7, 11|
|77|14|3, 13|14|3, 13|64|3, 13|92<br>(although *k* = 64 also has covering set {3, 13}, but 77<sup>1</sup>−64 is indeed 13, thus *k* = 64 is not dual Riesel)|3, 13|
|78|186123|5, 79, 1217|90059|5, 79, 1217|576859|5, 79, 1217|90059|5, 79, 1217|
|79|2212516|5, 7, 43, 6163|1965996|5, 7, 43, 6163|2212516|5, 7, 43, 6163|1965996|5, 7, 43, 6163|
|80|1039|3, 7, 13, 43, 173|253|3, 37, 173|1039|3, 7, 13, 43, 173|253|3, 37, 173|
|81|6068|7, 13, 73|74|7, 13, 73|6068|7, 13, 73|2692<br>(although *k* = 74 also has covering set {7, 13, 73}, but 81<sup>1</sup>−74 is indeed 7, thus *k* = 74 is not dual Riesel)|7, 13, 73|
|82|19587|5, 7, 13, 37, 83|22326|5, 83, 269|19587|5, 7, 13, 37, 83|64905|7, 13, 73, 83|
|83|8|3, 7|8|3, 7|8|3, 7|8|3, 7|
|84|16|5, 17|16|5, 17|101|5, 17|101|5, 17|
|85|346334170|37, 43, 193, 2437|398534880|37, 43, 193, 2437|(> 346334170, need to be searched, 346334170 is divisible by 5)|?|(> 398534880, need to be searched, 398534880 is divisible by 5)|?|
|86|28|3, 29|28|3, 29|115|3, 29|59|3, 29|
|87|274|7, 11, 19, 31|1660|7, 11, 13, 19|274|7, 11, 19, 31|1660|7, 11, 13, 19|
|88|4093|5, 7, 31, 37, 89|9702|13, 19, 31, 89|4093|5, 7, 31, 37, 89|28835|7, 13, 31, 89|
|89|4|3, 5|4|3, 5|4|3, 5|4|3, 5|
|90|27|7, 13|27|7, 13|209|7, 13|209|7, 13|
|91|89586|23, 41, 101|229058|23, 41, 101|109182|23, 41, 101|229058|23, 41, 101|
|92|32|3, 31|32|3, 31|61|3, 31|125<br>(although *k* = 61 also has covering set {3, 31}, but 92<sup>1</sup>−61 is indeed 31, thus *k* = 61 is not dual Riesel)|3, 31|
|93|24394|5, 47, 173|612|5, 47, 173|24394|5, 47, 173|8038|5, 47, 173|
|94|39|5, 19|39|5, 19|39|5, 19|39|5, 19|
|95|41354|3, 7, 13, 229|2510|3, 7, 13, 1303|41354|3, 7, 13, 229|31966|3, 7, 13, 229|
|96|353081|13, 97, 709|38995|7, 67, 97, 1303|353081|13, 97, 709|38995|7, 67, 97, 1303|
|97|15996|5, 7, 941|26354|5, 7, 13, 37, 73|15996|5, 7, 941|26354|5, 7, 13, 37, 73|
|98|10|3, 11|10|3, 11|23|3, 11|23|3, 11|
|99|684|5, 13, 29|144|5, 13, 29|824|5, 13, 29|3086|5, 13, 29|
|100|2469|7, 13, 37|750|7, 13, 37|2469|7, 13, 37|1691|7, 13, 37|
|101|16|3, 17|118|3, 17|16|3, 17|118|3, 17|
|102|293|7, 19, 79|1635|7, 19, 79|293|7, 19, 79|1793|7, 19, 79|
|103|13794|5, 13, 1061|1158|5, 7, 13, 19, 97|13794|5, 13, 1061|1158|5, 7, 13, 19, 97|
|104|4|3, 5|4|3, 5|11|3, 5|11|3, 5|
|105|181632|37, 53, 149|170606|37, 53, 149|202088|37, 53, 149|170606|37, 53, 149|
|106|495090|17, 107, 661|1626615|17, 107, 661|1920865|17, 107, 661|1626615|17, 107, 661|
|107|122|3, 5, 229|686|3, 5, 229|362<br>(although *k* = 122 also has covering set {3, 5, 229}, but 107<sup>1</sup>+122 is indeed 229, thus *k* = 122 is not dual Sierpinski)|3, 7, 19, 127|686|3, 5, 229|
|108|26270|7, 13, 109, 127|13406|7, 13, 61, 109|102677|7, 13, 61, 109|43601|7, 13, 61, 109|
|109|34|5, 11|144|5, 11|34|5, 11|144|5, 11|
|110|38|3, 37|38|3, 37|73|3, 37|73|3, 37|
|111|24340|7, 61, 101|12018|7, 61, 101|24340|7, 61, 101|58388|7, 61, 101|
|112|3502|5, 13, 113|3843|5, 13, 113|13333|5, 13, 113|11751|5, 13, 113|
|113|94|3, 19|20|3, 19|94|3, 19|20|3, 19|
|114|24|5, 23|24|5, 23|91|5, 23|91|5, 23|
|115|49794|7, 13, 17, 29, 433|78966|17, 29, 389|49794|7, 13, 17, 29, 433|78966|17, 29, 389|
|116|25|3, 13|14|3, 13|25|3, 13|25|3, 13|
|117|2184|5, 37, 59|6432|5, 37, 59|11506|5, 37, 59|7258|5, 37, 59|
|118|69|7, 17|50|7, 17|69|7, 17|69|7, 17|
|119|4|3, 5|4|3, 5|4|3, 5|4|3, 5|
|120|374876369|11, 13, 1117, 14281|166616308|11, 13, 1117, 14281|374876369|11, 13, 1117, 14281|(> 166616308, need to be searched, 166616308 is divisible by 4)|?|
|121|360|7, 19, 37|3294|7, 19, 37|360|7, 19, 37|3294|7, 19, 37|
|122|40|3, 41|14|3, 5, 13|47|3, 5, 13|83|3, 41|
|123|2138|5, 17, 31|154|5, 17, 31|2138|5, 17, 31|154|5, 17, 31|
|124|173559406|5, 7, 2179, 5167|3730449|5, 7, 2179, 5167|(> 173559406, need to be searched, 173559406 is divisible by 2)|?|3730449|5, 7, 2179, 5167|
|125|8|3, 7|8|3, 7|8|3, 7|8|3, 7|

*OEIS* sequences for special *k*-values:

|*k*|original Sierpinski|original Riesel|dual Sierpinski|dual Riesel|
|---|---|---|---|---|
|2|https://oeis.org/A119624, https://oeis.org/A253178 (only bases *b* which have possible primes), https://oeis.org/A098872 (*b* divisible by 6)|https://oeis.org/A119591, https://oeis.org/A098873 (*b* divisible by 6), https://oeis.org/A279095 (*b* of the form 2<sup>*r*</sup>)|https://oeis.org/A138066, https://oeis.org/A084713 (corresponding primes), https://oeis.org/A138067 (*n* = 1 not allowed)|https://oeis.org/A250200, https://oeis.org/A255707 (*n* = 1 allowed), https://oeis.org/A084714 (*n* = 1 allowed, corresponding primes), https://oeis.org/A292201 (prime *b*, *n* = 1 allowed)|
|3|https://oeis.org/A098877 (*b* divisible by 6)|https://oeis.org/A098876 (*b* divisible by 6)|||
|*b*−1|https://oeis.org/A305531, https://oeis.org/A087139 (prime *b*, *n* replaced by *n*+1)|https://oeis.org/A122396 (prime *b*, *n* replaced by *n*+1)|https://oeis.org/A076845, https://oeis.org/A076846 (corresponding primes), https://oeis.org/A078178 (*n* = 1 not allowed), https://oeis.org/A078179 (*n* = 1 not allowed, corresponding primes)|https://oeis.org/A113516, https://oeis.org/A343589 (corresponding primes)|
|*b*+1|||https://oeis.org/A178250|https://oeis.org/A346149 (*n* = 1 not allowed), https://oeis.org/A346154 (*n* = 1 not allowed, corresponding primes)|

For the original Sierpinski/Riesel conjectures, there is already a project http://www.noprimeleftbehind.net/crus/, the subpages are:

* http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm (Sierpinski conjectures, non-power-of-2 bases *b*)
* http://www.noprimeleftbehind.net/crus/Sierp-conjectures-powers2.htm (Sierpinski conjectures, power-of-2 bases *b*)
* http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm (Riesel conjectures, non-power-of-2 bases *b*)
* http://www.noprimeleftbehind.net/crus/Riesel-conjectures-powers2.htm (Riesel conjectures, power-of-2 bases *b*)

and there is "all-ks" text files in these pages, also, for these text files for the original Sierpinski/Riesel conjectures and for the text files of the dual Sierpinski/Riesel conjectures in this page (not list the *k* with trivial factor 2, i.e. for the original Sierpinski/Riesel conjectures, not list odd *k* for odd *b*, and for the dual Sierpinski/Riesel conjectures, only list the *k* which have opposite parity as *b*, i.e. odd *k* for even *b*, or even *k* for odd *b*):

* "TRIV": All *n*-values are covered by one trivial factor (must be >2, since *k* and *b* have opposite parity) (i.e. *gcd*(*k*,*b*) > 1 (for dual Sierpinski/Riesel conjectures) or *gcd*(*k*+1,*b*−1) > 1 (for original/dual Sierpinski conjectures) or *gcd*(*k*−1,*b*−1) > 1 (for original/dual Riesel conjectures)
* "ALG": All *n*-values are covered by algebraic factors or a combination of algebraic and trivial factor(s)
* "GFN": Make generalized Fermat numbers, i.e. *q*<sup>*m*</sup>×*b*<sup>*n*</sup>+1 where *m* ≥ 0 and *q* is a root of the base *b* (for original Sierpinski conjectures) or *b*<sup>*n*</sup>+1 (for dual Sierpinski conjectures)
* "MOB": *k* is a multiple of base (*b*) and *k*+1 (for Sierpinski) or *k*−1 (for Riesel) is not prime (for original Sierpinski/Riesel conjectures)
* "REM": No (probable) primes found for this *k* (search limit: 10000)
