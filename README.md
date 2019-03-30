# Baseball Players Data Visualization with Tableau

The final version：https://public.tableau.com/shared/5W8Q6GCGR?:display_count=yes

## Summary
The dataset (baseball.csv) consists of 1157 players' following attributes:
+ name:the name of Baseball Players
+ Handedness: left, right or both
+ Height: in inches
+ Weight: in pounds
+ Avg: batting average
+ HR: number of home runs
+ BMI: BMI value

I'm interested in finding what features contribute to high batting average, successful home runs, and the relationship between batting average and home runs.

The percentage of left-handed people are much higher than in ordinary population (widely considered 10%). Are lefties doing greater job than righties on baseball fields?

### Design
1. The distribution of height, weight and BMI values of athletes is represented by bar chart, which summarizes the basic physical fitness of athletes in this data set.

2. The bar graph distribution of baseball player's two sports abilities, Average hit rate and home run number, can intuitively see the difference of sports abilities between different players.

3. Top players are displayed in bar charts to present a straightforward view and the comparable differences between each person. In the fianl version, the axis and titles are refined to provide a more enunciating visualization. Two bar charts are laid out side by side instead of up and down, so readers can compare the names more easily.

4. Combining the linear chart and scatter plot, this paper studies the correlation between the three athletes'physical fitness and the two sports abilities, and adds the hand-used factor of the athletes.

### Feedback
Questions are gathered from readers with no data analysis background against the first sketch.

#### Plot 1
1. Most players are between 70 and 76 inches tall, in metric terms, between 1.78 and 1.93 meters.
1. The overwhelming majority of baseball players weigh between 159.6 and 197.6.
1. BMI is a standard to measure the body's weight and fitness. Normal values range from 18.5 to 23.9. Baseball, as a competitive sport, has stringent requirements for body shape. It can be found from the chart that the BMI index of most players is in the range of 23.0 to 25.5.

#### Plot 2
1. The group with the highest average hit rate ranges from 0.2236 to 0.258, i.e. from 22.36% to 25.8%. This shows that successful hit is a difficult skill for every player. Even baseball players with a batting rate of 0 show the importance of the average batting rate in measuring a player's comprehensive sports ability.
1. From the distribution chart of the number of home run hits, the long tail phenomenon shows that home run is a very difficult skill for a qualified baseball player to achieve, besides the hit rate, and may not even be able to hit a home run for a baseball player's career. In this data set, 709 athletes have never hit home runs.
1. Used hands have a far-reaching impact on baseball players, and their swing and standing are affected to varying degrees by used hands. In a game, the coach will deploy according to what kind of handedness athletes use. In this data set, the vast majority of athletes are right-handed, and 104 players with both hands are used.

#### Plot 3
1. Top players are displayed in bar charts to present a straightforward view and the comparable differences between each person. In the fianl version, the axis and titles are refined to provide a more enunciating visualization. Two bar charts are laid out side by side instead of up and down, so readers can compare the names more easily.

#### Plot 4
1. The figure shows that the average hit rate is negatively correlated with height, and the right-handed baseball player is the most obvious (P value) among them, while the correlation between home run and height is not particularly obvious.
1. The Average hit rate is negatively correlated with body weight. Home run was positively correlated with body weight in varying degrees, with two-handed baseball players being the most obvious and right-handed players being the least significant. It can also be found from the chart that the number of home runs of athletes weighing between 170 and 190 is the most obvious.
1. Firstly, both average hit rate and home run are positively correlated with BMI; among them, left-handed baseball player's hit rate and BMI are most significantly correlated; for home run, right-handed baseball player is the most obvious.

#### Plot 5
1. The vast majority of baseball players concentrate on home runs of less than 100, with an average hit rate of 20%-28%; when home runs of more than 300 and hits of more than 30%, the number of baseball players becomes sparse, and it can be concluded that the line between good baseball players and ordinary baseball players is here; in the field of sports, everyone has their own skills, such as the number of home runs of some players in the picture. The number of left-handed players is zero, but the average batting rate can be maintained at a relatively high level, and the baseball player with the largest home run is a left-handed player named Reggie Jackson, while the highest average batting rate is a left-handed player named Rod Carew, which can be sure that the left-handed players are very popular in the field of baseball.

### Resources
https://github.com/udacity/new-dand-advanced-china/blob/master/Tableau%20%E5%8F%AF%E8%A7%86%E5%8C%96/%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AA%20Tableau%20%E5%8F%AF%E8%A7%86%E5%8C%96%E6%95%85%E4%BA%8B.md
