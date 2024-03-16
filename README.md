# 📊 **Reece Calvin - Baseball Data Analyst**

## 🏢 **Past Position**: 
### Data Analyst at Hiroshima Carp    (Jul. 2023 - Dec. 2023)

•Introduced a data-driven approach to optimizing player performance and strategic decision-making

•Implemented innovative Sabermetric approaches, resulting in improved team performance

•Played a pivotal role in elevating the team's overall performance and achieving notable on-field success

•Helped in on-field strategy such as bunt and lineup decisions and created an NPB Stuff+ model

### Team Manager and Analyst at Northeastern Huskies Baseball    (Sept. 2021 - Present)

•Assisted coaches and athletics staff with practice and game day operations

•Used expected value to find optimize bunting and stolen base strategies

•Created a college Stuff+ model

## PROJECTS

### MLB Pitch Grader (Python/Jupyter Notebook)    (Dec. 2022 – Jun. 2023)

•Created expected run value by calculating average run value of pitch result, independent of count

•Handled balls in play by using regression model to predict run value•Fit models with Bayesian Optimization

•Split train and test sets by separating individual pitchers

•Resulted in a positive R2


### [Lineup Simulator (Python/PyCharm)    (Sep. 2021 – Apr. 2024)](https://github.com/Reece236/MLB_Sim)

•Created a classification model to predict ball in play outcomes

•Classified outcomes by result and hard hit type, e.g. Single-1, Single-4

•Created outcome distributions for each batter and pitcher•Used brier score minimization to find best pitcher and batter weights

•Used a Markov Chain to predict transitions between states

•O/U accuracy of 56% and correlation of 17% to real scores


### Statcast Based Hitter Tools (Python/Jupyter Notebook)    (Nov. 2023 – Nov. 2023)

#### Plate DisciplineoMethodology:

    Pitch Score = (Swing Prob.) * (Swing RV) + (Strike Prob.) * (Strike RV) + (Ball Prob.) * (Ball RV)
  
    Take Score = (Strike Prob) * (Strike RV) + (Ball Prob.) * (Ball RV)
  
  If the player takes pitch:
  
      Swing Score = Take Score — Pitch Score
      
  If the player swings:
  
      Swing Score = Swing RV — Pitch Score
#### Power

    Predicted bat speed using exit velocity over expected

#### Contact

    Contact over expected
    
  Only evaluated swings
  
  Binary contact or no contact

#### Speed

    Home to first time

#### Tool Based wOBA

    Linear regression using tools, 2022 grade had .18 R2 to true 2023 wOBA
  
  Outperformed xwOBA and wOBA at predicting fututre wOBA
