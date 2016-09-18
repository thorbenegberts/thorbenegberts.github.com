---
layout:     post
title:      From Blogger to Ghost (Part 3)
date:       2014-09-15 21:01:00
summary:    I've moved from Blogger to Ghost.
categories: blogging
---

Finding a suitable hosting solution for my [Ghost blogging platform](https://ghost.org/download/) could have been easier if I searched in the right place first. That's life.

My idea was to get an provider for virtual private servers. Cloud would be nice. First choice was [Amazon Web Services (AWS)](http://aws.amazon.com/) with their Amazon Elastic Compute Cloud (EC2). It seemed to be promising: Easy login (credit card needed), easy setup. Or lets say, it seemed to be easy. Shortly after creating my first _instance_ (a virtual server) I had to get into the nitty gritty details: Configuration of permission groups, public IPs and the allocation of those to the my virtual server instance. I got it all up and running. After that I logged in via SSH and started to configure Ghost using their instructions for [Linux](http://docs.ghost.org/de/installation/linux/) and [deployment](http://docs.ghost.org/de/installation/deploy/). After all I got it all right.

The next day I told my girlfriend proudly about my new blog and that I'm using AWS for it. She asked how much will it cost. I have to say ... I did not really care. AWS has a free contingent of service in the first year of use. But I started to wonder ... what will come after it? I calculated the possible costs. It would be at least about 16 USD. My girlfriend told me that I could get a private virtual server cheaper, e.g. at [Prgmr](http://prgmr.com/xen/).

After some research I found these alternatives to AWS:

* [Prgmr](http://prgmr.com/xen/)
* [Linode](https://www.linode.com/)
* [DigitalOcean](https://www.digitalocean.com/)

I aimed for the best cost-benefit ratio, so I chose [DigitalOcean](https://www.digitalocean.com/) (10 USD per month). I logged in (you need an credit card or PayPal account for that) and started to create my first virtual server, called _droplet_. I got it all up and running, logged in via SSH and started to configure everything needed for Ghost. It didn't mention it before, you need to ...

- ... install [node.js](http://nodejs.org/) and the node package manager (npm)
- ... install [nginx](http://nginx.org/)
- ... configure [Upstart](http://upstart.ubuntu.com/) if you are using Ubuntu

That's all. But this time it did not work out as easy as on the AWS' EC2 instance. I just did not manage to get it up and running. I tried everything.

Frustrated I deleted my droplet and started over. But what did I see? There is a fully configured image for Ghost using Ubuntu! Was the solution after all this easy? The answer is yes ...

Conclusion: If you want a really easy way to get your self-hosted Ghost blogging platform up and running, just visit [DigitalOcean](https://www.digitalocean.com/), create an account and create a droplet using the Ghost image. For details see [this manual](https://www.digitalocean.com/community/tutorials/how-to-use-the-digitalocean-ghost-application).

One last thing: There is also an [easy manual for importing your posts from Blogger](http://www.ghostforbeginners.com/how-to-transfer-blog-posts-from-blogger-to-ghost/). You just have to take care of your images yourself, sadly.