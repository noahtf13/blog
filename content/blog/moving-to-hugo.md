+++
title = "Why I Moved My Blog from Hashnode to Hugo and Why Hashnode is Better"
date = "2022-06-12"
description = "Switching from Hashnode to Hugo"
tags = [
    "Musings"
]
+++
I recently moved [my _one_ post](https://noah-ford.com/cracker-barrel-whole-foods-presidential-2020/) to a blog that was more custom and managed by me using [Hugo](https://gohugo.io/) + the [Bear Blog theme](https://github.com/janraasch/hugo-bearblog), instead of the very awesome and easy-to-use platform [Hashnode](https://hashnode.com/).  This isn't a tutorial of how I moved from Hashnode, but more of my thoughts on why I did it for a few bad reasons. 

# What are Hashnode, Bear Blog, and Hugo?
Each is a different blogging platform that is popular with tech/HN types, but excels at something different. I originally hosted my blog on Hashnode but decided to switch and explored Bear Blog along the way before landing on Hugo + the Bear Blog template.
## Hashnode
![Hashnode Example](/images/hashnode_example.png "Previous look and feel of my blog on Hashnode")[Hashnode](https://hashnode.com/) is a "blogging platform for developers" that is very similar to the likes of Medium and Substack but is catered more towards devs. The community is much more dev-focused as well as the product where it is easy to use custom CSS and JS snippets in your blog. I loved the combo of easy-to-start while still having plenty of customization available. 

I found the feed to be lacking posts of length and effort, with topics ranging from SSH keys on GitHub, building your first GUI on python, and list comprehensions. I don't mean to say there is anything wrong with these types of posts, and throughout my journey as a data scientist, I've found these types of tutorials helpful but I often find lengthy posts filled with effort satisfying to read. 

This tangent had nothing to do with why I started or stopped using Hashnode, but something interesting I noticed when comparing the content on Hashnode to Substack and Hacker News. 
## Bear Blog
![Bear Blog Example](/images/bear_blog_example.png "Home Page of bearblog.dev")

As you can see [Bear Blog](bearblog.dev) has the exact look and feel of this blog, and that is exactly what I'm going for. I kept seeing these [clean](https://www.sdgluck.com/i-dont-like-medium/) [looking](https://tarunreddy.bearblog.dev/addict/) [blogs](https://herman.bearblog.dev/running-a-blogging-platform/) on Hacker News and noticed they were all from Bear Blog. It also takes about 60 seconds to set up a blog, and the pages are a few kilobytes. 

Bear Blog also has a [discovery feed](https://bearblog.dev/discover/) that feels a little more [Web 1.0](https://en.wikipedia.org/wiki/Web_2.0#Web_1.0) with simpler sites, but also content that feels more genuine and fewer tutorials with click-bait when compared to Hashnode.

![Bear Blog Post Example](/images/bear_blog_new_post_example.png "All that needs to be filled out for a new post on Bear Blog")

Everything from the finished product of my blog to the signup process would have been lightweight, but I was craving some more customization and autonomy. 
## Hugo 
Hugo is a static site generator written in Go. It is praised for its performance and features,[^1] but can be justly criticized for being not worth it for setting up a simple blog [^2]. 

Hugo was another blogging method I saw recommended and [discussed](https://news.ycombinator.com/item?id=30527884) [on](https://news.ycombinator.com/item?id=30396935) [Hacker News](https://news.ycombinator.com/item?id=12672394) often, but it was daunting since I saw a lot of config files and scary Go syntax that I wouldn't have to encounter with Hashnode and Bear Blog. 

# Why Move Off Hashnode? Why Hugo? Why Not Bear Blog?
I gave a decent amount of thought when searching for a platform before writing [my first blog](https://noah-ford.com/cracker-barrel-whole-foods-presidential-2020/), but my motivations were different then, as I was looking for a job. I wanted a place to quickly create a blog that rendered markdown, brought attention to myself, and that looked good to a potential future employer. Hashnode is still one of the best places I know of to satisfy these motivations for tech blogs. 

I currently love my job ([we're hiring](https://jobs.lever.co/onaroll), [let's chat](https://calendly.com/noah_ford/30-minute-meeting)) and thus don't have the same motivations as before, now they are the following:
## 1. I am Addicted to Finding the Next Best Tool

I now will have had 2 posts across 2 methods of blogging. I cannot recommend this less, and those in the space that I respect have made it clear that you should write often before worrying about where your writing lives. 

I agree with this advice but avoided it. I hadn't engaged with a completely new tool in a while, either at work or outside it, and was yearning for the aha moment of hitting deploy and watching something _I_ built working in a production setting. Data Scientists like myself get the opportunity to encounter production successes less than most people think, since "only 13% said their models are always deployed" in a survey from Rexer Analytics[^3]

## 2. Improve Web Dev Experience
Hashnode and Bear Blog are too easy, you can have a blog in a couple of minutes, and it looks good out of the box. Your blog also gets posted to each platform's feed for easy discovery. It was too easy on me and thus didn't teach me anything. 

For most people, the goal of starting a blog is not to have to learn more about web development, but it is a goal of mine to improve my non-DS programming skills. My day-to-day work is as a Data Scientist, and I have gotten over the imposter syndrome in that profession, but not in the somewhat-adjacent field of web development. Even as I write Python and/or SQL every weekday, I don't see myself as a programmer, especially not a front-end one. I feel that this is a common trait among many Data Scientists that I've worked with, and I've always wanted to get to the point of considering myself a somewhat employable software engineer.

{{< tweet user="josh_wills" id="198093512149958656" >}}

To be clear, I don't think that getting a simple static site up and running will make me a better Data Scientist directly, but there is an indirect benefit of teaching me that entering the space of the unknown can be gratifying. Hugo isn't hard to set up, but it was the perfect middle between hosting my site on a Raspberry Pi (I'm using Netlify) and Hashnode. 

## 3. I Want My Blog to Be Just a Blog but Still Look Good
With the [Bear Blog Hugo template](https://github.com/janraasch/hugo-bearblog), I can have the flexibility and customization of Hugo while not having to start from square one in terms of the looks and feel of my blog. The lightweight template echoes the philosophy laid out [here](https://motherfuckingwebsite.com/), while still looking great. 

## 4. I "Need" to Have My Blog Be Powered by a Git Repo

The  above is the weirdest of the four reasons. Due to the insecurity that oozes when my Web Developer hat is on, I felt that for my blog to be legit it needs to be powered by a repository. It is nice that this keeps my git skills fresh since I don't/can't always use git in my day-to-day work. I could have a repo that houses all the queries I've written at work, but it isn't _necessary_ for the queries to run, as opposed to someone who creates production software in a collaborative environment.

# Parting Thoughts
If it isn't clear from the post, I think Hashnode and Bear Blog are better dev-blog platforms for most cases due to their easy-to-setup and good-looking blogs. 

I think my case was unique since this was more or less an adventure to reassure myself that it can be worthwhile to do things without a solid reason. Recently, I had ten days off work, and this fulfilled my craving to get back to something that was somewhat challenging, very rewarding, and unnecessary! 

I hope you enjoyed reading this,  and if so, you can add this blog's [RSS feed](http://noah-ford.com/index.xml) to the reader of your choice.

[^1]: https://en.wikipedia.org/wiki/Hugo_(software)
[^2]: https://news.ycombinator.com/item?id=21978306
[^3]: https://www.kdnuggets.com/2022/01/models-rarely-deployed-industrywide-failure-machine-learning-leadership.html
