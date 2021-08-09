# Australian State & Territory COVID press conferences
An analysis of each state's daily covid press conference

In this repository you will find
- code for how I transcribed the daily press conferences
- links to the data (so you can play around and/or verify my work ;)
- any adhoc analyses I do

So far the data is only for NSW, but I hope to get all states and territories there soon.

## The data/transcripts
- a giant .json file can be found here: https://covid19-au-press-conferences.s3.amazonaws.com/nsw/json/nswtranscriptions.json
- or each day's can be found but substituting the desired DATE into this link (for now, its set to 20210729: https://covid19-au-press-conferences.s3.amazonaws.com/nsw/text/20210729_nsw_press_conference.txt

### Why am I doing this?
Firstly, I'm in lockdown and have been for 6+ weeks. 
Secondly, I'm a data scientist and so, like everyone, obsessed with the numbers and graphs. I wanted to start tracking how many ICU patients had been vaccinated yet but unfortunately the government only provides this information in the weekly (...now tri-weekly...) epidemiology report and is aggregated at a weekly level. The health office often state these numbers at press conferences but to date they are published anywhere. So rather than go back and watch 40+ hours of youtube videos, i wrote a program which gets the data for me :)


## Notes
For now, I have started the NSW data at 17/6/2021 as this was the first press conference of the Sydney/NSW outbreak.

## References:
- @jdepoix who wrote the youtube_transcriber library. Such a good library and made this all possible: https://github.com/jdepoix/youtube-transcript-api

## Shameless Self-promo
**Linkedin:** www.linkedin.com/in/LiamPearson
**Twitter:** www.twitter.com/liampearson
**Youtube:** https://youtube.com/channel/UC00mJZYeIKqLDgxZ9napBag

