## Introduction to Pandas Python
<strong>Welcome!</strong> This notebook will teach you about using <code>Pandas</code> in the Python Programming Language. 
By the end of this lab, you'll know how to use <code>Pandas</code> package to view and access data.
<h2>Table of Contents</h2>
   <li>About the Dataset</li>       
   <li>Introduction of <code>Pandas</code></li>         
   <li>Viewing Data and Accessing Data</li>       
   <li>Quiz on DataFrame</li>
  </ul>   <br>  Estimated time needed: <strong>15 min</strong><hr>
       <h2>About the Dataset</h2>
        The table has one row for each album and several columns
        <ul>
          <li><b>artist</b>: Name of the artist</li>
          <li><b>album</b>: Name of the album</li>
          <li><b>released_year</b>: Year the album was released</li>
          <li><b>length_min_sec</b>: Length of the album (hours,minutes,seconds)</li>
          <li><b>genre</b>: Genre of the album</li>
          <li><b>music_recording_sales_millions</b>: Music recording sales (millions in USD) on [SONG://DATABASE]</li>
          <li><b>claimed_sales_millions</b>: Album's claimed sales (millions in USD) on [SONG://DATABASE]</li>
          <li><b>date_released</b>: Date on which the album was released</li>
          <li><b>soundtrack</b>: Indicates if the album is the movie soundtrack (Y) or (N)</li>
          <li><b>rating_of_friends</b>: Indicates the rating from your friends from 1 to 10</li></ul>
          You can see the dataset here:  <font size=\"1\"><table font-size:xx-small style=\"width:25%\">   <tr>     <th>Artist</th>     <th>Album</th>      <th>Released</th>     <th>Length</th>     <th>Genre</th>      <th>Music recording sales (millions)</th>     <th>Claimed sales (millions)</th>     <th>Released</th>     <th>Soundtrack</th>     <th>Rating (friends)</th>   </tr>   <tr>     <td>Michael Jackson</td>     <td>Thriller</td>      <td>1982</td>     <td>00:42:19</td>     <td>Pop, rock, R&B</td>     <td>46</td>     <td>65</td>     <td>30-Nov-82</td>     <td></td>     <td>10.0</td>   </tr>   <tr>     <td>AC/DC</td>     <td>Back in Black</td>      <td>1980</td>     <td>00:42:11</td>     <td>Hard rock</td>     <td>26.1</td>     <td>50</td>     <td>25-Jul-80</td>     <td></td>     <td>8.5</td>   </tr>     <tr>     <td>Pink Floyd</td>     <td>The Dark Side of the Moon</td>      <td>1973</td>     <td>00:42:49</td>     <td>Progressive rock</td>     <td>24.2</td>     <td>45</td>     <td>01-Mar-73</td>     <td></td>     <td>9.5</td>   </tr>     <tr>     <td>Whitney Houston</td>     <td>The Bodyguard</td>      <td>1992</td>     <td>00:57:44</td>     <td>Soundtrack/R&B, soul, pop</td>     <td>26.1</td>     <td>50</td>     <td>25-Jul-80</td>     <td>Y</td>     <td>7.0</td>   </tr>     <tr>     <td>Meat Loaf</td>     <td>Bat Out of Hell</td>      <td>1977</td>     <td>00:46:33</td>     <td>Hard rock, progressive rock</td>     <td>20.6</td>     <td>43</td>     <td>21-Oct-77</td>     <td></td>     <td>7.0</td>   </tr>     <tr>     <td>Eagles</td>     <td>Their Greatest Hits (1971-1975)</td>      <td>1976</td>     <td>00:43:08</td>     <td>Rock, soft rock, folk rock</td>     <td>32.2</td>     <td>42</td>     <td>17-Feb-76</td>     <td></td>     <td>9.5</td>   </tr>     <tr>     <td>Bee Gees</td>     <td>Saturday Night Fever</td>      <td>1977</td>     <td>1:15:54</td>     <td>Disco</td>     <td>20.6</td>     <td>40</td>     <td>15-Nov-77</td>     <td>Y</td>     <td>9.0</td>   </tr>     <tr>     <td>Fleetwood Mac</td>     <td>Rumours</td>      <td>1977</td>     <td>00:40:01</td>     <td>Soft rock</td>     <td>27.9</td>     <td>40</td>     <td>04-Feb-77</td>     <td></td>     <td>9.5</td>   </tr> </table></font>
        
        
