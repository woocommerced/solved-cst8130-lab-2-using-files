Download Link: https://assignmentchef.com/product/solved-cst8130-lab-2-using-files
<br>
Use your solution for Lab 1 and add a menu option to fill the array with values from a file.  The first entry in the file will be the number of values that follow (ie the size of the array).   Be sure to handle every possible error condition.  Test your code through the Lab 2 test plan below and the Lab 2 Sample Files (although not all error conditions are in the sample files – so you may need to make more files – use Notepad).

<strong><em><u>Lab 2 Test Plan:  </u></em></strong>

<strong>Menu Testing</strong>

<table width="624">

 <tbody>

  <tr>

   <td width="120">Condition</td>

   <td width="180">Input</td>

   <td width="324">Result</td>

  </tr>

  <tr>

   <td width="120">Menu input of 6 first</td>

   <td width="180">6, then Prompt for name of file</td>

   <td width="324">File should be processed per testing below</td>

  </tr>

  <tr>

   <td width="120">Menu input of 2</td>

   <td width="180">2 (then enter 3 for size of new array)</td>

   <td width="324">Input accepted, back to menu</td>

  </tr>

  <tr>

   <td width="120">Menu input of 4</td>

   <td width="180">4</td>

   <td width="324">Values should print 0.0 0.0 0.0</td>

  </tr>

  <tr>

   <td width="120">Menu input of 3</td>

   <td width="180">3 (then values -1 -2 -3)</td>

   <td width="324">User should be prompted to enter 3 numbers</td>

  </tr>

  <tr>

   <td width="120">Menu input of 5</td>

   <td width="180">5</td>

   <td width="324">Average of -2.0 should be displayed</td>

  </tr>

  <tr>

   <td width="120">Menu input of 6</td>

   <td width="180">6, then Prompt for name of file</td>

   <td width="324">File should be processed per testing below</td>

  </tr>

  <tr>

   <td width="120">Menu input of 7</td>

   <td width="180">7</td>

   <td width="324">Program ends</td>

  </tr>

 </tbody>

</table>




<strong>File Testing</strong>

<table width="624">

 <tbody>

  <tr>

   <td width="138">Condition</td>

   <td width="150">Input</td>

   <td width="336">Result</td>

  </tr>

  <tr>

   <td width="138">Bad file name</td>

   <td width="150">lab2</td>

   <td width="336">Error Message –“ file does not exist”. (Back to menu)</td>

  </tr>

  <tr>

   <td width="138">Good file</td>

   <td width="150">lab2.txt – contains4 1 2 3 4</td>

   <td width="336">Input accepted, data read, back to menu</td>

  </tr>

  <tr>

   <td width="138">Menu input of 4</td>

   <td width="150"> </td>

   <td width="336">Values 1 2 3 4  should display</td>

  </tr>

  <tr>

   <td width="138">Menu input of 5</td>

   <td width="150"> </td>

   <td width="336">Average 2.5 should display</td>

  </tr>

  <tr>

   <td width="138">Bad file – wrong number of entries</td>

   <td width="150">Lab2bad1.txt – contains4 1 2 3</td>

   <td width="336">Error Message –  “missing values in file – did not process file” (Back to menu)</td>

  </tr>

  <tr>

   <td width="138">Bad file – invalid value for number of entries</td>

   <td width="150">Lab2bad2.txt – containsA 1 2 3</td>

   <td width="336">Error Message – “Invalid data in file – did not process”</td>

  </tr>

  <tr>

   <td width="138">Bad file – invalid value for an entry</td>

   <td width="150">Lab2bad3.txt – contains 4 1 2 a 3</td>

   <td width="336">Error Message – “Invalid data in file – did not process”</td>

  </tr>

  <tr>

   <td width="138">Bad file – contains more values than number of entries</td>

   <td width="150"> </td>

   <td width="336">Program processes number of entries and ignore rest of file</td>

  </tr>

 </tbody>

</table>

<strong><em> </em></strong>





