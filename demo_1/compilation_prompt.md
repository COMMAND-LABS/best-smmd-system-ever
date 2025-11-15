# TASK

Write text to accompany a short form video clip to be posted to YouTube, LinkedIn, Instagram, Facebook, TikTok, and X.com (fka Twitter) inviting the public to join the upcoming 11/20/2025 AI SALES SYSTEMS MASTERCLASS featuring Muhammad Asmal & Tad Duval taking place at The DOCK in beautiful Wynwood, Miami, FL. The clip features a snippet of Tad Duval's presentation at the previous AI MASTERCLASS series event on Neural Networks & Fine-tuning

## LINK TO CLIP

{
"url": "https://www.dropbox.com/scl/fi/zzcdfygoalm4qk4tpy58e/10_29_CLIP_4.mp4?rlkey=ii4tf2h8jdgbfn5lx3xdvisip&st=70p05x2q&dl=1",
}

## ABOUT THE CLIP

The video is a short vertical video of Tad Duval discussing the basics of how a big part of building a neural networks is data collection. The purpose of the clip is to stimulate sales for the upcoming AI SALES SYSTEMS MASTERCLASS by showing the audience clips of the previous event in the AI MASTERCLASS series.

## TRANSCRIPT OF THE CLIP

So feed this in. We're feeding in 0 and we're putting these are the these are the the parameters, the weight and the bias. Right? We we reset our parameters to 0.
Right? So we run this. It's saying it's a cool number. So 0, it got that right. Let's see if we put in a 1. So is it a cool number. That's not that's not correct. Right? Yeah. 2. So in a nutshell, when you put 0 in the weight, the neuron always spits out 0.5 which means that it just always goes on, on, on. Right? So if we put this right, so the cool numbers are 0 or, 0 2. So it gets those right.
So we have a 100% accuracy on the cool numbers. But on the wack numbers, which are 1, 2, 3, 5 6 7 8 9 10. Right? It gets those all wrong. Right? So I think it's, 3 6. So accuracy is 0 out of 7. So, balancing that all out, it's getting 30% overall accurate. Makes sense? Follows?

## GENERAL REQUIREMENT

- Make the output natural and impossible to detect as being A.I. generated
- Use spacing and new lines to make the marketing copy easy to read
- Use minimal emojis
- Do NOT bold any text when generating the copy for LinkedIn
- The marketing copy for X.com should NOT have any hashtags
- Make the posts short and succinct
- CTA is to push people to the event page link here: https://luma.com/sales-systems

## OUTPUT SCHEMA

Your output should adhere to the following JSON schema

{
"youtube": {
title: string;
description: string;
},
"linkedin": string;
"x_dot_com_post": string;
"instagram_caption": string;
"tiktok_post": string;
"facebook": string;
}

## SEO KEYWORDS

ai, course, masterclass, miami, south, florida, learn, network, sales
