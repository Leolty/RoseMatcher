# RoseMatcher

**RoseMatcher** is an approach an approach to automatically match colloquially-written user reviews with technically-written release notes, and identify the relevant matching pairs, which can not only address the language gap between the two natural languages, but also greatly improve the hit ratio of the matching pairs.

This repository provides the public access to the raw data of *RoseMatcher*.

## Data Source

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-ncd7{background-color:#ffffc7;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-tqgz{background-color:#ffffc7;border-color:#000000;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">App</th>
    <th class="tg-0pky">Category</th>
    <th class="tg-0pky">App Release Time</th>
    <th class="tg-0pky">First Update Time</th>
    <th class="tg-0pky">Ranking Within Category</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ncd7">Reddit</td>
    <td class="tg-ncd7">News</td>
    <td class="tg-ncd7">2016/04/07</td>
    <td class="tg-ncd7">2016/04/20</td>
    <td class="tg-ncd7">2</td>
  </tr>
  <tr>
    <td class="tg-ncd7">Spotify</td>
    <td class="tg-ncd7">Music</td>
    <td class="tg-ncd7">2011/07/04</td>
    <td class="tg-ncd7">2015/05/20</td>
    <td class="tg-ncd7">1</td>
  </tr>
  <tr>
    <td class="tg-ncd7">Pandora</td>
    <td class="tg-ncd7">Music</td>
    <td class="tg-ncd7">2013/09/18</td>
    <td class="tg-ncd7">2014/06/12</td>
    <td class="tg-ncd7">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">ZOOM</td>
    <td class="tg-0pky">Bussiness</td>
    <td class="tg-0pky">2012/08/15</td>
    <td class="tg-0pky">2013/12/18</td>
    <td class="tg-0pky">1</td>
  </tr>
  <tr>
    <td class="tg-0pky">Microsoft Teams</td>
    <td class="tg-0pky">Bussiness</td>
    <td class="tg-0pky">2016/11/02</td>
    <td class="tg-0pky">2016/11/08</td>
    <td class="tg-0pky">2</td>
  </tr>
  <tr>
    <td class="tg-tqgz">SHEIN</td>
    <td class="tg-tqgz">Shopping</td>
    <td class="tg-tqgz">2014/5/20</td>
    <td class="tg-tqgz">2014/7/21</td>
    <td class="tg-tqgz">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">Google Chrome</td>
    <td class="tg-0pky">Utilities</td>
    <td class="tg-0pky">2012/06/28</td>
    <td class="tg-0pky">2014/10/27</td>
    <td class="tg-0pky">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">TestFlight</td>
    <td class="tg-0pky">Developer Tools</td>
    <td class="tg-0pky">2014/7/23</td>
    <td class="tg-0pky">2014/07/26</td>
    <td class="tg-0pky">1</td>
  </tr>
  <tr>
    <td class="tg-0pky">Github</td>
    <td class="tg-0pky">Developer Tools</td>
    <td class="tg-0pky">2020/3/17</td>
    <td class="tg-0pky">2020/03/20</td>
    <td class="tg-0pky">2</td>
  </tr>
  <tr>
    <td class="tg-ncd7">Instagram</td>
    <td class="tg-ncd7">Photo &amp; Video</td>
    <td class="tg-ncd7">2010/10/06</td>
    <td class="tg-ncd7">2015/09/15</td>
    <td class="tg-ncd7">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">Gmail</td>
    <td class="tg-0pky">Productivity</td>
    <td class="tg-0pky">2011/11/02</td>
    <td class="tg-0pky">2012/07/31</td>
    <td class="tg-0pky">1</td>
  </tr>
  <tr>
    <td class="tg-0pky">Google Drive</td>
    <td class="tg-0pky">Productivity</td>
    <td class="tg-0pky">2012/6/28</td>
    <td class="tg-0pky">2014/01/28</td>
    <td class="tg-0pky">2</td>
  </tr>
</tbody>
</table>

\* All the data information is sourced from Apple App Store.

\* Rows with yellow background are evaluation data we use in our paper. (same below)

## Collection Method

* Data collection was performed in February 2022.
* All user reviews and release notes of the apps for the 5-year period from January 1st, 2017 to January 1st, 2022 are crawled. 

## Dataset Composation

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-5hcb{background-color:#F9EDA6;border-color:inherit;color:#494949;text-align:left;vertical-align:top}
.tg .tg-z38j{background-color:#F9EDA6;border-color:#000000;color:#494949;text-align:left;vertical-align:top}
.tg .tg-frbo{color:#494949;text-align:left;vertical-align:top}
.tg .tg-mg27{border-color:inherit;color:#494949;text-align:left;vertical-align:top}
.tg .tg-jqjf{color:#494949;font-style:italic;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-mg27">App Name</th>
    <th class="tg-mg27">Release Num</th>
    <th class="tg-mg27">Sentence Num</th>
    <th class="tg-mg27">Review Num</th>
    <th class="tg-mg27">Sentence Num</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">Reddit</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">233</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">450</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">62,598</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">129,545</span></td>
  </tr>
  <tr>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">Spotify</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">182</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">506</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">368,243</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">808,441</span></td>
  </tr>
  <tr>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">Pandora</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">115</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">235</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">107,241</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">241,497</span></td>
  </tr>
  <tr>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">ZOOM</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">104</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">878</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">47,799</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">95,528</span></td>
  </tr>
  <tr>
    <td class="tg-mg27">Microsoft Teams</td>
    <td class="tg-mg27">154</td>
    <td class="tg-mg27">379</td>
    <td class="tg-mg27">9,233</td>
    <td class="tg-mg27">21,567</td>
  </tr>
  <tr>
    <td class="tg-z38j"><span style="background-color:#F9EDA6">SHEIN</span></td>
    <td class="tg-z38j"><span style="background-color:#F9EDA6">161</span></td>
    <td class="tg-z38j"><span style="background-color:#F9EDA6">361</span></td>
    <td class="tg-z38j"><span style="background-color:#F9EDA6">45,516</span></td>
    <td class="tg-z38j"><span style="background-color:#F9EDA6">117,529</span></td>
  </tr>
  <tr>
    <td class="tg-mg27">Google Chrome</td>
    <td class="tg-mg27">77</td>
    <td class="tg-mg27">359</td>
    <td class="tg-mg27">12,677</td>
    <td class="tg-mg27">32,735</td>
  </tr>
  <tr>
    <td class="tg-mg27">TestFlight</td>
    <td class="tg-mg27">22</td>
    <td class="tg-mg27">37</td>
    <td class="tg-mg27">5,566</td>
    <td class="tg-mg27">8,683</td>
  </tr>
  <tr>
    <td class="tg-mg27">Github</td>
    <td class="tg-mg27">68</td>
    <td class="tg-mg27">373</td>
    <td class="tg-mg27">668</td>
    <td class="tg-mg27">1,458</td>
  </tr>
  <tr>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">Instagram</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">253</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">380</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">461,264</span></td>
    <td class="tg-5hcb"><span style="background-color:#F9EDA6">918,729</span></td>
  </tr>
  <tr>
    <td class="tg-mg27">Gmail</td>
    <td class="tg-mg27">119</td>
    <td class="tg-mg27">175</td>
    <td class="tg-mg27">33,985</td>
    <td class="tg-mg27">93,748</td>
  </tr>
  <tr>
    <td class="tg-mg27">Google Drive</td>
    <td class="tg-mg27">127</td>
    <td class="tg-mg27">167</td>
    <td class="tg-mg27">26,139</td>
    <td class="tg-mg27">56,823</td>
  </tr>
  <tr>
    <td class="tg-jqjf">Total</td>
    <td class="tg-frbo">1,615</td>
    <td class="tg-frbo">4,300</td>
    <td class="tg-frbo">1,180,929</td>
    <td class="tg-frbo">2,526,283</td>
  </tr>
</tbody>
</table>