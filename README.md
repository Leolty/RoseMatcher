# RoseMatcher

**RoseMatcher** is an approach an approach to automatically match colloquially-written user reviews with technically-written release notes, and identify the relevant matching pairs, which can not only address the language gap between the two natural languages, but also greatly improve the hit ratio of the matching pairs.

This repository provides the public access to the raw data of *RoseMatcher*.

## Data Source

<table>
<thead>
  <tr>
    <th>App</th>
    <th>Category</th>
    <th>App Release Time</th>
    <th>First Update Time</th>
    <th>Ranking Within Category</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td bgcolor="fafabe"><mark>Reddit</td>
    <td bgcolor="fafabe">>News</td>
    <td bgcolor="fafabe">2016/04/07</td>
    <td bgcolor="fafabe">2016/04/20</td>
    <td bgcolor="fafabe">2</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Spotify</td>
    <td bgcolor="fafabe">Music</td>
    <td bgcolor="fafabe">2011/07/04</td>
    <td bgcolor="fafabe">2015/05/20</td>
    <td bgcolor="fafabe">1</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Pandora</td>
    <td bgcolor="fafabe">Music</td>
    <td bgcolor="fafabe">2013/09/18</td>
    <td bgcolor="fafabe">2014/06/12</td>
    <td bgcolor="fafabe">2</td>
  </tr>
  <tr>
    <td>ZOOM</td>
    <td>Bussiness</td>
    <td>2012/08/15</td>
    <td>2013/12/18</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Microsoft Teams</td>
    <td>Bussiness</td>
    <td>2016/11/02</td>
    <td>2016/11/08</td>
    <td>2</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>SHEIN</td>
    <td bgcolor="fafabe">Shopping</td>
    <td bgcolor="fafabe">2014/5/20</td>
    <td bgcolor="fafabe">2014/7/21</td>
    <td bgcolor="fafabe">2</td>
  </tr>
  <tr>
    <td>Google Chrome</td>
    <td>Utilities</td>
    <td>2012/06/28</td>
    <td>2014/10/27</td>
    <td>2</td>
  </tr>
  <tr>
    <td>TestFlight</td>
    <td>Developer Tools</td>
    <td>2014/7/23</td>
    <td>2014/07/26</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Github</td>
    <td>Developer Tools</td>
    <td>2020/3/17</td>
    <td>2020/03/20</td>
    <td>2</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Instagram</td>
    <td bgcolor="fafabe">Photo &amp; Video</td>
    <td bgcolor="fafabe">2010/10/06</td>
    <td bgcolor="fafabe">2015/09/15</td>
    <td bgcolor="fafabe">2</td>
  </tr>
  <tr>
    <td>Gmail</td>
    <td>Productivity</td>
    <td>2011/11/02</td>
    <td>2012/07/31</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Google Drive</td>
    <td>Productivity</td>
    <td>2012/6/28</td>
    <td>2014/01/28</td>
    <td>2</td>
  </tr>
</tbody>
</table>

\* All the data information is sourced from Apple App Store.

\* Apps that *App Name* are marked are evaluation data we use in our paper (same below).

## Collection Method

* Data collection was performed in February 2022.
* All user reviews and release notes of the apps for the 5-year period from January 1st, 2017 to January 1st, 2022 are crawled. 

## Dataset Composation

<table>
<thead>
  <tr>
    <th>App Name</th>
    <th>Release Num</th>
    <th>Sentence Num</th>
    <th>Review Num</th>
    <th>Sentence Num</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td bgcolor="fafabe"><mark>Reddit</td>
    <td bgcolor="fafabe">233</td>
    <td bgcolor="fafabe">450</td>
    <td bgcolor="fafabe">62,598</td>
    <td bgcolor="fafabe">129,545</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Spotify</td>
    <td bgcolor="fafabe">182</td>
    <td bgcolor="fafabe">506</td>
    <td bgcolor="fafabe">368,243</td>
    <td bgcolor="fafabe">808,441</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Pandora</td>
    <td bgcolor="fafabe">115</td>
    <td bgcolor="fafabe">235</td>
    <td bgcolor="fafabe">107,241</td>
    <td bgcolor="fafabe">241,497</td>
  </tr>
  <tr>
    <td>ZOOM</td>
    <td>104</td>
    <td>878</td>
    <td>47,799</td>
    <td>95,528</td>
  </tr>
  <tr>
    <td>Microsoft Teams</td>
    <td>154</td>
    <td>379</td>
    <td>9,233</td>
    <td>21,567</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>SHEIN</td>
    <td bgcolor="fafabe">161</td>
    <td bgcolor="fafabe">361</td>
    <td bgcolor="fafabe">45,516</td>
    <td bgcolor="fafabe">117,529</td>
  </tr>
  <tr>
    <td>Google Chrome</td>
    <td>77</td>
    <td>359</td>
    <td>12,677</td>
    <td>32,735</td>
  </tr>
  <tr>
    <td>TestFlight</td>
    <td>22</td>
    <td>37</td>
    <td>5,566</td>
    <td>8,683</td>
  </tr>
  <tr>
    <td>Github</td>
    <td>68</td>
    <td>373</td>
    <td>668</td>
    <td>1,458</td>
  </tr>
  <tr>
    <td bgcolor="fafabe"><mark>Instagram</td>
    <td bgcolor="fafabe">253</td>
    <td bgcolor="fafabe">380</td>
    <td bgcolor="fafabe">461,264</td>
    <td bgcolor="fafabe">918,729</td>
  </tr>
  <tr>
    <td>Gmail</td>
    <td>119</td>
    <td>175</td>
    <td>33,985</td>
    <td>93,748</td>
  </tr>
  <tr>
    <td>Google Drive</td>
    <td>127</td>
    <td>167</td>
    <td>26,139</td>
    <td>56,823</td>
  </tr>
  <tr>
    <td><i>Total</i></td>
    <td><i>1,615</td>
    <td><i>4,300</td>
    <td><i>1,180,929</td>
    <td><i>2,526,283</td>
  </tr>
</tbody>
</table>