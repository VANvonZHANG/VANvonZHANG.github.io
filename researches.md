---
layout: page
permalink: /projects/index.html
title: Projects

---

# My Research Projects

### Undergoing

- ##### Effect of policy intervention on emission reduction of fine particulate matter: a case study of the Asian Games in Hangzhou

In this study, we used a Geographically weighted regression (GWR) model to investigate the driving effect of socioeconomic indicators on PM2.5 concentrations in different cities. Then we use the K-means algorithm to classify different cities into four types according to the coefficient of the driving factors, so that the driving effect of socio-economic indicators on PM2.5 concentration of different types of cities has significant differences. The purpose of the above steps is to obtain cities that are more similar to Hangzhou, so that we can select them as suitable control groups to synthesize the virtual control group in the following synthetic control method (SCM). We use the cities in the same category as Hangzhou in the K means algorithm as the control group for the SCM.

Due to the dry and wet deposition effect and the cross-regional transport effect of PM2.5, if we want to consider the effect of emission reduction on the PM2.5 concentration in a region, we have to consider the meteorological conditions on the PM2.5 concentration in that region. Using the Random Forest algorithm, we can remove the effect of meteorological conditions on the PM2.5 concentration in a region to obtain the PM2.5 source emission concentration.

We use the Random Forest algorithm for Hangzhou and the cities in the control group at the same time in our study period to obtain the time series of PM2.5 source emission concentrations in these areas, and use this concentration as the variable in the SCM. Through the synthetic control method, we can synthesize a virtual Hangzhou. By comparing the PM2.5 source concentrations in this virtual Hangzhou with those in the real Hangzhou, we can derive the impact on PM2.5 concentrations due to the policy intervention (chosen in this study as Hangzhou Asian Games 2023).

<details>
<summary>Flow chart</summary>
<img src="file//publications//posters//2023-1.png" >

<details>
<summary>Chinese abstract</summary>
在这个研究当中，我们使用了地理空间加权模型（GWR）模型来研究不同城市的社会经济指标对于PM2.5浓度的驱动作用。紧接着我们利用K means算法根据驱动因子的系数大小将不同城市分为4种类型，不同类型的城市的社会经济指标对于PM2.5浓度的驱动作用有着显著的差别。以上步骤的目的是为了获得和杭州较为类似的城市，以便于在接下来的合成控制法（SCM）中选取合适的对照组来合成虚拟的控制组。我们将K means算法中和杭州同一类的城市作为SCM的对照组。
<br>
由于PM2.5的干湿沉降作用以及跨区域传输作用，如果我们要考虑一个地区的减排对于该地区PM2.5浓度的影响，我们就不得不考虑气象条件，对于该地区PM2.5浓度的作用。利用随机森林算法，我们可以排除一个地区气象条件对于该地区PM2.5浓度的影响，从而得到PM2.5源排放浓度。
<br>
我们对杭州以及对照组中的城市同时在我们的研究时段中使用随机森林算法从而获得这些地区PM2.5源排放浓度的时间序列，并将这个浓度作为SCM的变量。通过合成控制法，我们可以合成出一个虚拟的杭州。通过对比该虚拟的杭州和真实杭州的PM2.5源排放浓度，我们就可以得出由于政策干预（在本研究中选为杭州亚运会2023）对于PM2.5浓度的影响。
<style>
    summary {
  padding: 10px;
  background-color: #f2f2f2;
  border: 1px solid #ccc;
  border-radius: 5px;
  cursor: pointer;
}
    summary:hover {
  background-color: #e6e6e6;
<style>






---

# Open-source Projects

<br>



<!DOCTYPE html>
<html>


