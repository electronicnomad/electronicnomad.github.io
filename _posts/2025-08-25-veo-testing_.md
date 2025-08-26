---
layout: post
title: Veo demo, comparing results by model (version) with the same prompt
author: landlord
tags:
- veo
- GenAI
- AI
- testing
- generative
- gemini
- demo
---

Veo demo, comparing results by model (version) with the same prompt.  

# Purpose of testing Veo 

I suggested using Veo to an entertainment industry client 
to create a music video in the "Official Visualization" category. 
Veo seemed like a very suitable solution, and I judged that 
it was sufficient to provide the results the label wanted 
in a short time at a significantly lower price compared 
to professional production companies.

I created a demo using the following five prompts 
and presented it to top-level decision-makers, 
production teams, and clients from the IT pillar.

The initial results were produced with the Veo 0815 model. 
Afterwards, as Veo evolved into Veo 2 and Veo 3, 
I'd like to share my experience and discuss the differences 
in the outputs when the same prompts were used.

# Demo videos by Veo 

### Prompts used

- A wide shot of a lone person riding a classic motorbike across a vast, sun-drenched prairie, with a dramatic sky filled with fluffy clouds in the background. The person is silhouetted against the setting sun, creating a sense of epic scale and adventure.

- A low-angle shot of a person stepping into a room, with the doors closing behind them, creating a sense of anticipation and mystery. The focus is on the person's silhouette against the bright light from the hallway, emphasizing the contrast between the enclosed space and the open world beyond. 

- A hand runs through the soft dirt, before reaching over with a spade and digging. The hands place a small flowering plant in the hole and cover it up. They pat the soil around the plant until it is firm.

- Two young men sit on a bench in a lively marketplace, each holding a cup of coffee in take-out type and engaged in a conversation. One man, with dark skin, a strong jawline and a serious expression, wears a green shirt, while the other man, with light skin, a friendly smile and stylish hair, wears a white polo. Intimate close-up shots, lit with soft, natural light, alternate between the men's faces, their expressions revealing the delicious conversation about chocolate. Award winning advertisement, cinematic style, in focus, both are in screen.

- a member of a \{ girl \| k-pop \} group looks at the camera, speaking with a serious expression on her face.

## Motorbike 

*Prompt: A wide shot of a lone person riding a classic motorbike across a vast, sun-drenched prairie, with a dramatic sky filled with fluffy clouds in the background. The person is silhouetted against the setting sun, creating a sense of epic scale and adventure.* 

<hr />
- Veo-Preview-0815
{% include youtube.html id="QLgVPWDGoj4" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="mYU53MRt3z0" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="iJmLHMRJFp8" %}
<hr />

The prompt that yielded the best results with Veo 1 (a name I'm using for distinction, though it's not official) was also the most dramatic, which I was very pleased with.

Veo 2 felt like it used a higher-magnification lens compared to Veo 1. If Veo 1 was a 24mm wide-angle lens, Veo 2 felt like a 50mm standard lens.

It was surprising that with Veo 3, I was able to get very satisfying results on most of the first attempts.

## A person stepping into a room 

*Prompt: A low-angle shot of a person stepping into a room, with the doors closing behind them, creating a sense of anticipation and mystery. The focus is on the person's silhouette against the bright light from the hallway, emphasizing the contrast between the enclosed space and the open world beyond.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="VkevA9MpbrE" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="ZWet7XY1iKY" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="pxcFdJ9ppb4" %}
<hr />

I thought this would be a great example of cinematic direction and decided to give it a try. But, it required an incalculable number of attempts with Veo 1.

However, as I moved to Veo 2 and Veo 3, the probability of getting what I wanted increased significantly. With Veo 3, I got the video I wanted on the very first prompt.

I recall that with most of my Veo 1 attempts, I had to try at least 30 times. With Veo 2, it was around 10 tries, and with Veo 3, I was able to get what I wanted within 1 to 3 tries. This is where I can see the progress of the model.

However, the number of attempts can vary greatly depending on each person's goals. What I want to emphasize is that the number of retries can be seen as an indicator of how many attempts it took to get a relatively consistent result.

## A hand runs through the soft dirt 

*Prompt: A hand runs through the soft dirt, before reaching over with a spade and digging. The hands place a small flowering plant in the hole and cover it up. They pat the soil around the plant until it is firm.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="KBDTzHZI_b8" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="EENGerYMiWw" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="61VtEBSdGGQ" %}
<hr />

When Veo 1 was first introduced, I really wanted to create a demo that included human hands. At the time, generative AI (for both video and images) had a tough time accurately depicting human fingers.

My goal in making this video was to show how precisely the AI could represent human fingers.

## Two young men 

*Prompt: Two young men sit on a bench in a lively marketplace, each holding a cup of coffee in take-out type and engaged in a conversation. One man, with dark skin, a strong jawline and a serious expression, wears a green shirt, while the other man, with light skin, a friendly smile and stylish hair, wears a white polo. Intimate close-up shots, lit with soft, natural light, alternate between the men's faces, their expressions revealing the delicious conversation about chocolate. Award winning advertisement, cinematic style, in focus.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="PXr4pHAmP68" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="k11X7gXefLU" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="V_RvGufnxx0" %}
<hr />

Of the challenges presented by Veo 2, one was the ability to create various camera angles (though in a short amount of time). I was impressed by how natural the transitions were and that there was no awkwardness compared to the shots before the angle changed.

One of the most significant developments with Veo 3 was the addition of audio support. As you can see in the video above, it was astonishing how naturally the dialogue was matched to the on-screen generated subjects.

## A member of a k-pop group 

*Prompt: a member of a girl group looks at the camera, speaking with a serious expression on her face.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="i8-rFj6sdJc" %}
<hr />

- veo-2.0-gnerate-002

  Using the prompt, I couldn't create a video with Veo 2. So, I generated an image with Imagen using the prompt and then used that image as input for Veo 2 to create the video.

{% include youtube.html id="YCI8c8gVzBM" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="LQRGDAe_vRU" %}
<hr />

When I was testing video generation with Veo 1, I was most satisfied with the results I got. It took an incredible number of tries, but I was impressed with how it even expressed the facial muscles of the person in the video, how it produced very faithful results from a short prompt, and how it understood the term 'girl group.'

However, the term 'girl group' was not allowed in Veo 2 and was not accepted by the system. While Veo 3 recognized the term 'k-pop group,' Veo 2 also treated 'k-pop group' as inappropriate.

Veo 2 was very unique in many ways. It felt less like an evolution of Veo 1 and more like an entirely different project that just inherited the name. Furthermore, this model seemed to have a strong intention to express 'diversity,' which led to many input and output restrictions. It also always produced one result that was different from the intended output.

Veo 3 was very satisfying, even with the voice output. It was interesting that the output dialogue was the same even after multiple retries. I also liked that it interpreted the prompt as a moment of interviewing an artist.

# Overall review 

- Veo 1 was a more impressive model than you remember.
- Veo 2 focused on generating results that were free of social issues.
- Veo 3 made me wonder what comes next. It was amazing.

In Veo 1, it took a very long time to refine the prompts or find an appropriate way to communicate with it. I remember trying one of the videos above more than 100 times, including prompt revisions, in the hope of getting a new candidate. The quality of the videos I got after learning how to "talk" to Veo 1 was better than I expected.

Veo 2 felt like it was struggling to not deviate from diversity and political correctness. I also don't know if it was to get "safe" results, but the restrictions on certain words in the prompts were relatively strong. However, for cinematic direction, Veo 2 was the best.

With Veo 3, I could see that even prompts that seemed impossible to produce with Veo 1 were generated closer to the user's intent. Among the many dazzling advancements of Veo 3, this was the most satisfying part.

If I were to choose one of the best improvements a user could feel as the Veo model versions up, I would say it's the ability to get closer to the intended result with fewer attempts.

### And so on ... 

Individual videos for each model have been uploaded to YouTube in separate playlists. The playlists are as follows.

- [Veo Demo (Preview 0815)](https://youtube.com/playlist?list=PLErlU15VorUhIAtp6WSgCg-6PxkWSmJpI&feature=shared) - Veo-Preview-0815
- [Veo 2 Demo](https://youtube.com/playlist?list=PLErlU15VorUgeA5miJR7rc5iE1MeRxVyI&feature=shared)  veo-2.0-generate-002 
- [Veo 3 Demo](https://youtube.com/playlist?list=PLErlU15VorUi_0LeCtQzp_Db87Zh3IYwz&feature=shared)  veo-3.0-generate-preview
