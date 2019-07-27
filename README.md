# FF18 - FIFA 2018 World Cup

Original idea is from this [GitHub Repo](https://github.com/amanthedorkknight/fifa18-all-player-statistics). 
I did an in-depth analysis and visualization on the FIFA 2018 dataset. The end goal is to predict the best possible top 10 international squad at the upcoming World Cup. 

## Data Source

The data is scraped from the website (SOFIFA)[https://sofifa.com] by extracting the Player personal data and Player Ids and then the playing and style statistics.

## Data Features and Labels

<table>
  <thead>
    <tr style=\text-align: right;\>
      <th></th>
      <th>0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Unnamed: 0</th>
      <td>0</td>
    </tr>
    <tr>
      <th>Unnamed: 0_x</th>
      <td>0</td>
    </tr>
    <tr>
      <th>ID_x</th>
      <td>158023</td>
    </tr>
    <tr>
      <th>Name</th>
      <td>L. Messi</td>
    </tr>
    <tr>
      <th>Age</th>
      <td>30</td>
    </tr>
    <tr>
      <th>Photo</th>
      <td>https://cdn.sofifa.org/sm/18/players/158023.png</td>
    </tr>
    <tr>
      <th>Nationality</th>
      <td>Argentina</td>
    </tr>
    <tr>
      <th>Flag</th>
      <td>https://cdn.sofifa.org/flags/52.png</td>
    </tr>
    <tr>
      <th>Overall</th>
      <td>94</td>
    </tr>
    <tr>
      <th>Potential</th>
      <td>94</td>
    </tr>
    <tr>
      <th>Club</th>
      <td>FC Barcelona</td>
    </tr>
    <tr>
      <th>Club Logo</th>
      <td>https://cdn.sofifa.org/xs/18/teams/241.png</td>
    </tr>
    <tr>
      <th>Value</th>
      <td>€118.5M</td>
    </tr>
    <tr>
      <th>Wage</th>
      <td>€565K</td>
    </tr>
    <tr>
      <th>Special</th>
      <td>2161</td>
    </tr>
    <tr>
      <th>Position</th>
      <td>CF|ST|RW</td>
    </tr>
    <tr>
      <th>Unnamed: 0_y</th>
      <td>0</td>
    </tr>
    <tr>
      <th>Acceleration</th>
      <td>92</td>
    </tr>
    <tr>
      <th>Aggression</th>
      <td>48</td>
    </tr>
    <tr>
      <th>Agility</th>
      <td>90</td>
    </tr>
    <tr>
      <th>Balance</th>
      <td>95</td>
    </tr>
    <tr>
      <th>Ball Control</th>
      <td>96</td>
    </tr>
    <tr>
      <th>Composure</th>
      <td>97</td>
    </tr>
    <tr>
      <th>Crossing</th>
      <td>77</td>
    </tr>
    <tr>
      <th>Curve</th>
      <td>90</td>
    </tr>
    <tr>
      <th>Dribbling</th>
      <td>97</td>
    </tr>
    <tr>
      <th>FK Accuracy</th>
      <td>92</td>
    </tr>
    <tr>
      <th>Finishing</th>
      <td>95</td>
    </tr>
    <tr>
      <th>GK Diving</th>
      <td>6</td>
    </tr>
    <tr>
      <th>GK Handling</th>
      <td>11</td>
    </tr>
    <tr>
      <th>GK Kicking</th>
      <td>15</td>
    </tr>
    <tr>
      <th>GK Positioning</th>
      <td>14</td>
    </tr>
    <tr>
      <th>GK Reflexes</th>
      <td>8</td>
    </tr>
    <tr>
      <th>Heading Accuracy</th>
      <td>71</td>
    </tr>
    <tr>
      <th>ID_y</th>
      <td>158023</td>
    </tr>
    <tr>
      <th>Interceptions</th>
      <td>22</td>
    </tr>
    <tr>
      <th>Jumping</th>
      <td>67</td>
    </tr>
    <tr>
      <th>Long Passing</th>
      <td>87</td>
    </tr>
    <tr>
      <th>Long Shots</th>
      <td>88</td>
    </tr>
    <tr>
      <th>Marking</th>
      <td>13</td>
    </tr>
    <tr>
      <th>Penalties</th>
      <td>75</td>
    </tr>
    <tr>
      <th>Positioning</th>
      <td>93</td>
    </tr>
    <tr>
      <th>Reactions</th>
      <td>95</td>
    </tr>
    <tr>
      <th>Short Passing</th>
      <td>88</td>
    </tr>
    <tr>
      <th>Shot Power</th>
      <td>85</td>
    </tr>
    <tr>
      <th>Sliding Tackle</th>
      <td>26</td>
    </tr>
    <tr>
      <th>Sprint Speed</th>
      <td>87</td>
    </tr>
    <tr>
      <th>Stamina</th>
      <td>73</td>
    </tr>
    <tr>
      <th>Standing Tackle</th>
      <td>28</td>
    </tr>
    <tr>
      <th>Strength</th>
      <td>59</td>
    </tr>
    <tr>
      <th>Vision</th>
      <td>92</td>
    </tr>
    <tr>
      <th>Volleys</th>
      <td>86</td>
    </tr>
  </tbody>
</table>
