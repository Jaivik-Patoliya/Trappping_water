# Trappping_water
Trapping  water is  frequently asked question in interview in company like google, microsoft, tesla, apple, amazon and etc.

Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining.

![image](https://github.com/Jaivik-Patoliya/Trappping_water/assets/130566442/6e937b68-beb2-48b9-a671-847430ae14d8)

Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6

Explanation :- black section : height of bar
blue section : trapped water

First we need to find when water is trapped. For each bar waterlevel is equal to minimum of leftboundry and rightboundry. Where leftboundry is maximum of leftside and right boundry is maximmum of right side.
Trappped water is equal to diffrence between waterlevel and height of bar.
And for total  Trappedwater is sum of all trappedwater.
