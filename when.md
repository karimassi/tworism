---
layout: default
title: When?
permalink: /when/
---

# When do people travel?

There are a lot of decisions to make when planning a trip. The most pressing one, besides which socks to bring, is to fit it into your schedule. When is the most convenient time for people to travel? Is it during the school breaks? Holidays? To answer these questions, we take a look at check-in information from a location-based social network spanning two years. 

Let's first explore the check-ins made by users outside of their home country during each month of the year. 

<div style="display: flex; justify-content: center;">
    {% include abroad_checkins_monthly.html %}
</div>


The most popular time of the year to go abroad is during the summer. As you can see, there is an abundance of check-ins made out-of-country during the months of June, July, August and September. This result is expected: this period of the year coincides with warmer and nicer weather in most regions of the world.  
  
---

Throughout most of the year, people engage in a consistent routine including commuting, working and other regular weekly activities. This results in a low variability of their movement. When traveling, this routine is broken and movement variability increases. This deviation can be measured by *entropy*: the lower the entropy, the more people are adhering to their routines. It follows that we can expect a higher entropy when people's movements are less predictable, when they're on vacation for example. To explore that, we compute the monthly average entropy of users. 


<div style="display: flex; justify-content: center;">
    {% include entropy.html %}
</div>

We notice that the location entopy during the week-ends is always higher, as it was pointed out by the authors of the original paper. This trend is further accentuated during the summer (e.g. July and August). This means that the people's movement patterns vary more and are less predictable. For other seasons, notably the spring and autumn, people seem to be more set in their routines, hence the slightly lower entropy. 

[Let's go!](national.md)