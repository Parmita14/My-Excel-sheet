# My-Excel-sheet
This project performs certain operations of Excel sheet as well as detects a special fault in formula. This detection is possible with the implementation of data structures and algorithms in my project.
<hr>
View my project through this link : https://parmita14.github.io/My-Excel-sheet/ 
<hr>
<b><i>Features :</i></b>
<ul>
  <li>
    Features of Text-decoration :
    <ul><li>
      font-size
    </li>
      <li>
        Font-Family
      </li>
      <li>
       Text color
      </li>
      <li>
        Background color for cell
      </li>
      <li>
        bold
      </li>
      <li>
        Italics
      </li>
      <li>
        Underline
      </li>
      <li>
        text alignment
      </li>
    </ul>
  </li>
  <li>
    Edit the cells using :
    <ul>
      <li>
        Copy the number of cells by selecting certain range of cells(ctrl+click the two cells that will define a range).
      </li>
       <li>Cut the copied cells</li>
      <li>Paste the cells copied at any location in the sheet</li>
    </ul>
   
  </li>
  <li>
     Save and Upload options are available that will download the sheet and one can also upload & edit it again. 
  </li>
  <li>
    User can add number of sheets with the help of add feature.
  </li>
  <li>
    Formula evaluation and calculation is possible using formula bar
  </li>
</ul>
<hr>
<b><i>Additional Feature </i></b><br>
Mostly data structures and algorithms are used to optimise the time and space used by the program but here i have used DSA to solve a different problem that may occur using excel sheet.<br>
Often times we make mistake while evaluating the formula.One of the them is evaluation of formula that creates cell dependency, the calculation of one cell depends on the other and vice versa. This causes a infinte loop that crashes the code. To resolve this problem i have used <b>Cycle detection algorithm of graph data structures</b>, this will detect if any dependency is present in formula.<br>
To avoid any confusion this program will show the cells where dependency is present and points out the mistake.<hr>
