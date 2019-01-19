---
permalink: /nfl
author_profile: false
---

<b>Years currently supported:</b> 2017-2018

<details><summary><b>teamName</b> map</summary>
  <table>
  <tr><th>teamName</th><th>Value</th></tr>
    <tr><td>atl</td><td>Atlanta Falcons</td></tr>
    <tr><td>buf</td><td>Buffalo Bills</td></tr>
    <tr><td>car</td><td>Carolina Panthers</td></tr>
    <tr><td>chi</td><td>Chicago Bears</td></tr>
    <tr><td>cin</td><td>Cincinnati Bengals</td></tr>
    <tr><td>cle</td><td>Cleveland Browns</td></tr>
    <tr><td>clt</td><td>Indianapolis Colts</td></tr>
    <tr><td>crd</td><td>Arizona Cardinals</td></tr>
    <tr><td>dal</td><td>Dallas Cowboys</td></tr>
    <tr><td>den</td><td>Denver Broncos</td></tr>
    <tr><td>det</td><td>Detroit Lions</td></tr>
    <tr><td>gnb</td><td>Green Bay Packers</td></tr>
    <tr><td>htx</td><td>Houston Texans</td></tr>
    <tr><td>jax</td><td>Jacksonville Jaguars</td></tr>
    <tr><td>kan</td><td>Kansas City Chiefs</td></tr>
    <tr><td>mia</td><td>Miami Dolphins/td></tr>
    <tr><td>min</td><td>Minnesota Vikings</td></tr>
    <tr><td>nor</td><td>New Orleans Saints</td></tr>
    <tr><td>nwe</td><td>New England Patriots</td></tr>
    <tr><td>nyg</td><td>New York Giants</td></tr>
    <tr><td>nyj</td><td>New York Jets</td></tr>
    <tr><td>oti</td><td>Tennessee Titans</td></tr>
    <tr><td>phi</td><td>Philadelphia Eagles</td></tr>
    <tr><td>pit</td><td>Pittsbugh Steelers</td></tr>
    <tr><td>rai</td><td>Oakland Raiders</td></tr>
    <tr><td>ram</td><td>Los Angeles Rams</td></tr>
    <tr><td>rav</td><td>Baltimore Ravens</td></tr>
    <tr><td>sdg</td><td>San Diego Chargers</td></tr>
    <tr><td>sea</td><td>Seattle Seahawks</td></tr>
    <tr><td>sfo</td><td>San Francisco 49ers</td></tr>
    <tr><td>tam</td><td>Tampa Bay Buccaneers</td></tr>
    <tr><td>was</td><td>Washington Redskins</td></tr>
  </table>
</details>

<br>
<details><summary><b>Quarterback Attributes</b></summary>
  <table>
  <tr><th>attribute</th><th>Value</th><th>Data Type</th><th>Supported (Y\N)</th></tr>
    <tr><td>gamesPlayed</td><td>Games Played</td><td>Integer</td><td>Y</td></tr>
    <tr><td>gameStarted</td><td>Games Started</td><td>Integer</td><td>Y</td></tr>
    <tr><td>position</td><td>Position</td><td>final String (QB)</td><td>Y</td></tr> 
    <tr><td>record</td><td>Record</td><td>String</td><td>Y</td></tr>
    <tr><td>completions</td><td>Completions</td><td>Integer</td><td>Y</td></tr>
    <tr><td>attempts</td><td>Attempts</td><td>Integer</td><td>Y</td></tr>
    <tr><td>completionPerc</td><td>Completion %</td><td>Double</td><td>Y</td></tr>
    <tr><td>yards</td><td>Passing Yards</td><td>Integer</td><td>Y</td></tr>
    <tr><td>touchdowns</td><td>Passing Touchdowns</td><td>Integer</td><td>Y</td></tr>
    <tr><td>tdPerc</td><td>Touchdown %</td><td>Double</td><td>Y</td></tr>
    <tr><td>interceptions</td><td>Interceptions</td><td>Integer</td><td>Y</td></tr>
    <tr><td>intPerc</td><td>Interception %</td><td>Double</td><td>Y</td></tr>
    <tr><td>longest</td><td>Longest Throw</td><td>Double</td><td>Y</td></tr>
    <tr><td>ydsAttempt</td><td>Yards per Attempt</td><td>Double</td><td>Y</td></tr>
    <tr><td>airYdsAtt</td><td>Air Yards per Attempt</td><td>Double</td><td>Y</td></tr>
    <tr><td>ydsCompletion</td><td>Yards per Completion</td><td>Double</td><td>Y</td></tr>
    <tr><td>ydsGame</td><td>Passing Yards per Game</td><td>Double</td><td>Y</td></tr>
    <tr><td>qbRating</td><td>QB Rating</td><td>Double</td><td>Y</td></tr>
    <tr><td>qbR</td><td>QBR</td><td>Double</td><td>Y</td></tr>
    <tr><td>sacks</td><td>Sacks</td><td>Integer</td><td>Y</td></tr>
    <tr><td>sackYds</td><td>Sack Yards</td><td>Integer</td><td>Y</td></tr>
    <tr><td>netYdsAtt</td><td>Net Passing Yards per Attempt</td><td>Double</td><td>Y</td></tr>
    <tr><td>adjNetYdsAtt</td><td>Adjusted Net Passing Yards per Attempt</td><td>Double</td><td>Y</td></tr>
    <tr><td>sackPerc</td><td>Sack %</td><td>Double</td><td>Y</td></tr>
    <tr><td>fourthQC</td><td>Fourth Quarter Comebacks</td><td>Integer</td><td>Y</td></tr>
    <tr><td>gameWinDri</td><td>Game Winning Drives</td><td>Integer</td><td>Y</td></tr>
  </table>
</details>

<br>
<details><summary><b>Skill Player Attributes</b> (RB/WR/TE)</summary>
  <table>
    <tr><th>attribute</th><th>Value</th><th>Data Type</th><th>Supported (Y\N)</th></tr>
    <tr><td>gamesPlayed</td><td>Games Played</td><td>Integer</td><td>Y</td></tr>
    <tr><td>gameStarted</td><td>Games Started</td><td>Integer</td><td>Y</td></tr>
    <tr><td>position</td><td>Position</td><td>String</td><td>Y</td></tr> 
    <tr><td>rushingAtt</td><td>Rushing Attempts</td><td>Integer</td><td>Y</td></tr>
    <tr><td>rushingYds</td><td>Rushing Yards</td><td>Integer</td><td>Y</td></tr>
    <tr><td>rushingTds</td><td>Rushing Touchdowns</td><td>Integer</td><td>Y</td></tr>
    <tr><td>rushingLng</td><td>Longest run </td><td>Integer</td><td>Y</td></tr>
    <tr><td>ydsPerCarry</td><td>Yards per Carry</td><td>Double</td><td>Y</td></tr>
    <tr><td>rushingYdsGame</td><td>Running Yards per Game</td><td>Double</td><td>Y</td></tr>
    <tr><td>rushingAttGame</td><td>Running Attempts per Game</td><td>Double</td><td>Y</td></tr>
    <tr><td>recTgts</td><td>Receiving Targets per Game</td><td>Integer</td><td>Y</td></tr>
    <tr><td>recYds</td><td>Receiving Yards per Game</td><td>Integer</td><td>Y</td></tr>
    <tr><td>ydsPerCatch</td><td>Yards per Catch</td><td>Double</td><td>Y</td></tr>
    <tr><td>recTds</td><td>Receiving Touchdowns</td><td>Integer</td><td>Y</td></tr>
    <tr><td>receptions</td><td>Receptions</td><td>Integer</td><td>Y</td></tr>
    <tr><td>recLng</td><td>Longest Catch/Reception</td><td>Integer</td><td>Y</td></tr>
    <tr><td>recPerGame</td><td>Receptions/Catches per Game</td><td>Double</td><td>Y</td></tr>
    <tr><td>recYdsGame</td><td>Receiving Yards per Game</td><td>Double</td><td>Y</td></tr>
    <tr><td>catchPerc</td><td>Catch %</td><td>String</td><td>Y</td></tr>
    <tr><td>touches</td><td>Total Touches per Game</td><td>Integer</td><td>Y</td></tr>
    <tr><td>ydsPerTch</td><td>Yards per Touch</td><td>Double</td><td>Y</td></tr>
    <tr><td>ydsFrmScrim</td><td>Yards From Scrimmage</td><td>Double</td><td>Y</td></tr>
    <tr><td>totalTds</td><td>Total Yards</td><td>Integer</td><td>Y</td></tr>
    <tr><td>fumbles</td><td>Fumbles</td><td>Integer</td><td>Y</td></tr>
  </table>
</details>