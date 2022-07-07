<h1> Veri Yapıları ve Algoritmalar Dosyasının içindeki odev-1  </h1>

<h3> Project 1: Insertion Sort </h3>
<p>
  A small task, given by Patika.dev to understand basic principles of sorts.
</p>
<pre>
  [22,27,16,2,18,6] -> Insertion Sort
<ol>
    <li>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</li>
    <li>Big-O gösterimini yazınız.</li>
    <li>Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: 
    Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.</li>
    <li>Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</li>
</ol>

<h4>
  Question 1:
  </h4>

<ol>
  <li>[16,22,27,2,18,6]</li>
  <li>[2,16,22,27,18,6]</li>
  <li>[2,8,16,22,27,18]</li>
  <li>[2,8,16,18,22,27]</li>
</ol>

<h4>
  Question 2:
</h4>
  <ul>
  <li> Best case    : O(n)</li>
  <li> Average case : O(n^2)</li>
  <li> Worst case   : O(n^2)</li>
</ul>

<h4>
  Question 3:
</h4>

  <ul>
  <li> Best case    : If the array is already in order. [2,8,16,18,22,27 </li>
  <li> Average case : Array elements are mixed up. [22,27,16,2,18,6] </li>
  <li> Worst case   : Array elemets are descending. [27,22,18,16,8,2]</li>
</ul>

<h4>
  Question 4:
</h4>
  It's the best case since the array is in-ordered and linearly searching accrues.

<h4>
  Extra Question:
</h4>
  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  <ol>
  <li>[3,7,5,8,2,9,4,15,16]</li>
  <li>[3,5,7,8,2,9,4,15,16]</li>
  <li>[2,3,5,7,8,9,4,15,16]</li>
  <li>[2,3,4,5,7,8,9,15,16]</li>
</ol>
</pre>

<h3> Project 2: Merge Sort </h3>
<pre>
<p>[16,21,11,8,12,22] -> Merge Sort</p>
<ol>
<li>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.</li>
<li>Big-O gösterimini yazınız.</li>
</ol>
<h4>
  Question 1:
  </h4>
  <pre>
               [16,21,11] --- [8,12,22]
            [16]--[21,11] --- [8]--[12,22]
           [16]-[21]-[11] --- [8]-[12]-[22]
               [11,16,21] --- [8,12,22]
                  [8,12,11,16,21,22]
  </pre>
  <h4>
  Question 2:
  </h4>
  All cases are the same so the Big-O notation is : O(nlogn).
</pre>
