---
layout: post
title:  "Setting Up This Website"
date:   2023-01-05 12:10:26 -0600
categories: tech
---
I figured what sort of tech worker would I be if I didn’t have my own personal website?

It’s been years since I last messed with hosting / making a website. I had a site I experimented with hosted with Bluehost back in 2009, my email receipt and account confirmation from back then had the domain name, username, and password all together in plain text! How things have changed.

I was originally thinking I would try and host with AWS, but after making an account and checking out some of their services it seemed like a lot to link together and maintain. In search of a more simple setup I went to YouTube and found a talk by AWS’s very own tech evangelist Robert Zhu where he starts the talk demoing Github Pages which seemed more like what I was looking for, and I made a Github account and started messing with it. Seemed super easy to get started with and the fact that it’s free to use was a nice bonus so I went and got started looking for a domain name. 

Of the TLDs .site’s were the cheapest and not wanting to overthink it I went with slynch.site for a very reasonable $1.20 to get started with from Namecheap. Configuring DNS was a little trial-and-error but once I found the right support page I figured out the automatic domain redirect from slynch.site to www.slynch.site was causing issues with the CNAME referral to the Github Pages link. I had everything else set up correctly and from then on everything started working as I had hoped.

I also had some temporary confusion because when I first was messing around with Github Pages I made an index.html test page. After I had properly setup Jekyll it was clear none of the default theme had applied to the site as configured. I pulled up another guide and realized right away that Github was prioritizing my test index.html over the index.md page Jekyll uses as the root of the project, and after removing that was really able to start customizing things and making this post.

I’ll be using this blog to post some of my experiments and adventures with tech, and occasionally I might share some thoughts on interesting articles that I come across. I passed my A+ 1101 exam yesterday so I’ll be focusing on studying for the 1102 for the next couple weeks before it’s on to the next thing.