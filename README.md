# Chess_vs_Sleep
A mini-experiment you can do on your own to see how often you win chess games, depending on whether you get an adequate amount of sleep. 

<img width="552" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/2d15b7a5-d082-4fde-8987-1747ea87c6d8">


Here is an example of my percent of games won versus on days when I had an adequate amount of sleep the day before versus when I did not. 

## You will need: 

* Data from Fitbit.com (You have to request your own data)
* data from chess.com (You can download your username or another's)
* This code, written in R

## Background

I love chess as it's all completely logical. There's no luck, it's all strategy. A thought occurred to me: does the amount of sleep you get affect how well you play this tough mental challenge? 

## Setup

I downloaded some data from Fitbit to see how often I win compared to how much sleep I got. This looks at 613 days where I played 7,590 games. I didn't always have data from my fitbit though for days when I'm charging it overnight. Also I took out days where I played only one game. So here we're looking at 389 days.

## Analysis

I came up with this graph: 

<img width="552" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/e2f0b2c6-faee-4c31-8f73-f51c5d13ad09">

That is a big old nothing burger. Same for deep sleep, restlessness, etc. Very low R value of correlation. This surprised me but I'm always happy to be proven wrong by data. 

Sometime later though I came back to this project as I realized sleep really isn't a continuous variable so much as a categorical one. Getting 30% more sleep doesn't mean you get a 30% increase in mental acuity, in the same way that 30% more sun might make a spot 30% hotter. 

So I went back and looked at dates where I had definitely gotten enough sleep versus times when I definitely had too little. 

I found there was a difference when you get enough sleep!

<img width="440" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/ad4dcc19-57aa-4081-813a-4337fdd04a0e">

Overall I usually win about half of my games and lose half. Which is roughly how it should be: <img width="486" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/dcadea4d-053a-485a-a5cb-16e0f5fd70c5">

So to have a 2.5% increase is huge. Though keep in mind this is a very small section of my data. I defined "too little" sleep as less than 6 hours and enough as more than 8 hours.  
<img width="323" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/5781a3ef-b57b-4136-bded-c97e88e3544c">

But definitely a very different distribution: 
<img width="555" alt="image" src="https://github.com/walinchus/Chess_vs_Sleep/assets/25959269/4ef85a4e-fb7d-4707-a856-4b72f4b2ec3f">
