# Gestion-des-dates-de-excel-R

THIS is my original data:



<table>
  <thead>
    <tr>
      <th>##</th>
      <th>Column1</th>
      <th>Column2</th>
      <th>Column3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>01/08/1992</td>
      <td>&lt;NA&gt;</td>
      <td>45135</td>
    </tr>
    <tr>
      <td>2</td>
      <td>30/01/1987</td>
      <td>01/08/2021</td>
      <td>45243</td>
    </tr>
    <tr>
      <td>3</td>
      <td>08/09/2000</td>
      <td>&lt;NA&gt;</td>
      <td>45349</td>
    </tr>
    <tr>
      <td>4</td>
      <td>16/12/2004</td>
      <td>45227</td>
      <td>45343</td>
    </tr>
    <tr>
      <td>5</td>
      <td>04/10/2016</td>
      <td>17/02/2022</td>
      <td>45320</td>
    </tr>
    <tr>
      <td>6</td>
      <td>25/01/2021</td>
      <td>09/08/2020</td>
      <td>45342</td>
    </tr>
    <tr>
      <td>7</td>
      <td>28/03/2023</td>
      <td>30/09/2022</td>
      <td>45327</td>
    </tr>
    <tr>
      <td>8</td>
      <td>26/04/2009</td>
      <td>45307</td>
      <td>45329</td>
    </tr>
    <tr>
      <td>9</td>
      <td>22/11/1995</td>
      <td>20/11/2020</td>
      <td>45349</td>
    </tr>
    <tr>
      <td>10</td>
      <td>27/02/1987</td>
      <td>&lt;NA&gt;</td>
      <td>45281</td>
    </tr>
  </tbody>
</table>


After correction the data i have : 

<table>
  <thead>
    <tr>
      <th>Column1<br><small>&lt;date&gt;</small></th>
      <th>Column2<br><small>&lt;date&gt;</small></th>
      <th>Column3<br><small>&lt;date&gt;</small></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1992-08-01</td>
      <td>&lt;NA&gt;</td>
      <td>2023-07-28</td>
    </tr>
    <tr>
      <td>1987-01-30</td>
      <td>2021-08-01</td>
      <td>2023-11-13</td>
    </tr>
    <tr>
      <td>2000-09-08</td>
      <td>&lt;NA&gt;</td>
      <td>2024-02-27</td>
    </tr>
    <tr>
      <td>2004-12-16</td>
      <td>2023-10-28</td>
      <td>2024-02-21</td>
    </tr>
    <tr>
      <td>2016-10-04</td>
      <td>2022-02-17</td>
      <td>2024-01-29</td>
    </tr>
    <tr>
      <td>2021-01-25</td>
      <td>2020-08-09</td>
      <td>2024-02-20</td>
    </tr>
    <tr>
      <td>2023-03-28</td>
      <td>2022-09-30</td>
      <td>2024-02-05</td>
    </tr>
    <tr>
      <td>2009-04-26</td>
      <td>2024-01-16</td>
      <td>2024-02-07</td>
    </tr>
    <tr>
      <td>1995-11-22</td>
      <td>2020-11-20</td>
      <td>2024-02-27</td>
    </tr>
    <tr>
      <td>1987-02-27</td>
      <td>&lt;NA&gt;</td>
      <td>2023-12-21</td>
    </tr>
  </tbody>
</table>



I've out the functioin  "The function.Rmd"



