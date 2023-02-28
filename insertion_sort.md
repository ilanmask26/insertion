# Question
1) [22,27,16,2,18,6]  dizisinin insertion short türüne göre aşamalarını yazınız.
<br>
* [2,27,16,22,18,6] // 2 ile 22 nin yerini değiştirdik
</br>
* [2,6,16,22,18,27] // 6 ile 27 nin değerini değiştirdik
<br>
* [2,6,16,18,22,27]// 18 ile 22 nin yerini değiştirdik
<br>

* big o  gösterimi ise ilk  aramada n kadar arama yapmaktayız, ikincisinde ise (n-1) kadar. Bu aramalar 1 e kadar azalır buradan da n*(n+1)/2 ifadesini elde ederiz. buradan da en dominant ifade olan o(n^2) ifadesi bizim big o değerimizi gösterir.
* Dizi sıralandıktan sonra 18 sayısının aranması average case durumuna girer

2) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız
* [2,3,5,8,7,9,4,15,6] // 7 ile 2 nin yerini değiştirdik
* [2,3,4,8,7,9,5,15,6] // 5 ile 4 ün yerini değiştirdik
* [2,3,4,5,7,9,8,15,6] // 5 ile 8 in yerini değiştirdik
* [2,3,4,5,6,9,8,15,7] // 6 ile 7 nin yerini değiştirdik
