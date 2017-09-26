---
layout: Data Science  
title: She blinded me! with SCIECNE!
---

Hello World! This is my first blog post for my first daa science project.

# The Problem
WTWY sent us THIS vaguely worded letter

```
Vinny, Sophie & Julia -

It was great to meet with you and chat at the event where we recently met and had a nice chat. We’d love to take some next steps to see if working together is something that would make sense for both parties.

As we mentioned, we are interested in harnessing the power of data and analytics to optimize the effectiveness of our street team work, which is a significant portion of our fundraising efforts.

WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer each year. As we are new and inclusive organization, we try to do double duty with the gala both to fill our event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach.

To this end we place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to our gala.

Where we’d like to solicit your engagement is to use MTA subway data, which as I’m sure you know is available freely from the city, to help us optimize the placement of our street teams, such that we can gather the most signatures, ideally from those who will attend the gala and contribute to our cause.

The ball is in your court now—do you think this is something that would be feasible for your group? From there we can explore what kind of an engagement would make sense for all of us.

Best,

Karrine and Dahlia

WTWY International 
```

WTWY wanted our help creating a strategy for the street teams. From the letter, they were looking for a few things:
- Build Awareness
- Increase Attendance
- Fundraise

We knew that we were supposed to use MTA data, but what other data sets could we use to improve our analysis? We began by lookign for concentrations of tech employees.

I got a list of the largest tech employers from [Crains](http://www.crainsnewyork.com/article/99999999/DATA/500034828/technology-employers) and [TechCrunch](https://techcrunch.com/2017/05/21/examining-the-nyc-footprints-of-global-tech-titans/). From there I used Google Maps' API Geocode function to get locations (latitude,longitude), to used to compare to train station locations.

![Drawing](https://github.com/3rock618/Project1_Benson-5/blob/master/WTWY%20Gala_FINAL.pdf")
