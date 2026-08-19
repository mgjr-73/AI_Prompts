# Overview

As Cybersecurity enthusiasts, we need to make an effort to stay up-to-date with current industry events, especially news about security breaches.  Knowing what's happening can help you start looking at your own organization to see whether there is any potential impact. There are several ways to do this. I particularly like Simply Cyber's Daily Threat Brief. Gerald Auger, Ph.D., makes it entertaining while adding professional insights that you don't get from simply reading the news.

With that  in mind, I still like to have my own custom briefing. With AI, aggregating the day's top news is pretty easy. I use Claude's Scheduled feature to collect my daily top 10. It gives me a TL;DR of the day's Top 10 Cybersecurity News.

Then set the frequency. Mine gathers the information daily at 4 A.M.

<kbd><img width="712" height="802" alt="image" src="https://github.com/user-attachments/assets/ae179967-9603-4a5a-882d-18c6d7b3dc1f" /></kbd>

Does this mean you need to have your computer on 24/7? No. It will send the news to your inbox as soon as you open your Claude desktop after the computer is turned on. If you don't want this limitation, you can move the schedule to the cloud.

<kbd><img width="265" height="147" alt="image" src="https://github.com/user-attachments/assets/e870d86d-7586-451b-a256-1f656ab84afb" /></kbd>

Here is a sample output on my inbox:

<kbd><img width="1175" height="820" alt="image" src="https://github.com/user-attachments/assets/ec18e8c2-13f1-4d73-aa65-345b51100bd8" /></kbd>

# The Prompt

>Visit cisoseries.com, darkreading.com, cybersecuritynews.com, securityweek.com, thehackernews.com, and cybersecuritydive.com. 
>
>From darkreading.com, cybersecuritynews.com, securityweek.com, thehackernews.com, and cybersecuritydive.com, pull only the top 2 stories from each (most recent/most prominent on the homepage). Also check [cisoseries.com](https://cisoseries.com/) for anything notable from the past 24 hours.
>
>Combine everything into a single flat list of up to 10 items, ranked by importance, not grouped by source. If two sources cover the same story, keep only one (pick the version with more detail) and drop the duplicate.
>
>For each item, write one to two sentences summarizing what happened, why it matters, and a link. Cite the source name at the end of the brief, like this:
>
>[One to two sentence summary]. [Link] — Source: Dark Reading
>
>Keep it scannable and TLDR style, no headers or source groupings. Email the list to <insert your email here> with the subject line "Cybersecurity Daily Briefing – [today's date]."



