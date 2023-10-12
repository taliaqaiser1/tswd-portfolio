| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Critique by Design

## Step One: Finding a Visualization

The Cricket World Cup 2023 is going on these days and it made me wonder about the players and the cities they belonged to. There are so many visualizations on predictions of the World Cup and which country has the best players but I wanted to see which city produces the best players and further dive deep into the reason why. 

For this, I searched for an article that compared the cities with the best batting and bowling averages. But the visualizations I found didn't seem very intuitive. 

**Link:** https://www.espncricinfo.com/story/which-top-cricket-city-would-win-the-world-cup-1196522

**Visualizations:**

<img width="605" alt="Screenshot 2023-09-19 at 9 08 27 PM" src="https://github.com/taliaqaiser1/tswd-portfolio/assets/123123984/392a8583-00bc-4266-b949-6a166badf7ae">

<img width="603" alt="Screenshot 2023-09-19 at 9 08 35 PM" src="https://github.com/taliaqaiser1/tswd-portfolio/assets/123123984/820510bd-ce9a-4df2-bc1a-3e9f4099e5d2">

## Step Two: Critique the Visualization

The purpose of visualizations is to compare the cities with the 'Best Batting/Bowling'. In this context, the visualization has a lot of text on it which makes it distracting to understand when you first look at it. It is not very intuitive. Secondly, the color scheme has a good contrast but the popping red if looked at for a long time, starts irritating the eyes. Thirdly, the monuments of the cities as their icons give information about the city they are talking about but it also seems like they are comparing the sizes of the monuments according to the data presented but in actuality, they are not doing that, hence, it is a bit misleading. It takes a while to see what is actually happening in the visualization. 

The primary audience for this tool is cricket enthusiasts and spectators who would like an analysis of why would a city win the Cricket World Cup. The visualization grabs the attention of its intended audience through the city monuments as they can easily spot which city the visual is talking about. Apart from that it has the necessary data that is needed to compare them so completeness can be seen. But one thing that isn’t working is how it gives a sense that the size of the icons of monuments may play a part in the visual. 

## Step Three: Wireframe a Solution

I started wireframing the solution with the given data in the visualizations and came up with a dual-axis bar chart. One side showed the full scale for runs and wickets the other side displayed the average. I chose the original colors but a white background so that it is not too distracting. 

![IMG_0002](https://github.com/taliaqaiser1/tswd-portfolio/assets/123123984/a490c241-9036-4074-84a2-6783f991d547)

This visualization depicted the intended data in a format that is easily understandable and readable by the audience. 

**Solution Draft 1 and Limitations:**

After this, I designed a solution for the two graphs. However, I could not figure out the dual scale in Flourish so I had to use a different approach, where I used a line and bar chart combined to show the data. 

<div class="flourish-embed flourish-chart" data-src="visualisation/15066974"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-chart" data-src="visualisation/15066945"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


Then, I got feedback on both, the wireframes and the solution.

## Step Four: Test the Solution

I asked three people for feedback on my sketches with the following profiles:
1. Student, early 20's
2. Student, mid 20's
3. Student, late 20's

The synthesized feedback from their interviews was as follows:
1. The bar charts work well
2. The dual scale is a good idea
3. Try combining the charts
4. Try adding more cities to the visualizations
5. The line charts imply that it is time-series data so maybe try something else.

## Step Five: Build your Solution

After taking into account the feedback I got from my critiques, I searched for more data and found the original dataset. I then subsetted the dataset to display the top 8 cities in terms of all Bowling, Batting, and the number of wickets taken by the players from that city. 

**Original Dataset:** https://data.world/raghav333/cricket-players-espn

The visualization then gave a robust idea as to how the cities can be seen on different dimensions and can be compared. No one city pops up as the best one but we can see interesting patterns across the cities for comparison. 


<div class="flourish-embed flourish-chart" data-src="visualisation/15077785"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
