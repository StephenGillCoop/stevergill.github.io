---
layout: post
title: My first blog post
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
modified: 2015-01-14
tags: [intro, beginner, jekyll, tutorial]
comments: true
image:
  feature: Dollarphotoclub_60937927.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

{% highlight php startinline %}
class SteveGillsBlog
{
    public $qualityBlogMaterial;

    public function __construct(QualityBlogMaterial $qualityBlogMaterial)
    {
        $this->qualityBlogMaterial = $qualityBlogMaterial;
    }
}
{% endhighlight %}

I couldn't resist. Its my first blog post and I've been dying to try out the code formatting feature!

You might guess from above I'm a big php fan, having used it for over 10 years. However it is only in the last 3 years
I've started actively developing applications using it.

### About me
You can find out more about me [here](/about/), but in short I design and lead the development of
niche web apps. These range from very small specialist web apps with a handful of users, through to multi tenant, multi site
solutions handling terabytes of data with thousands of simultaneous connections.

### Technology
I mainly use php in the back end, using Symfony and Laravel frameworks. I also have apps using C# and even some node.js.
The front end uses AngularJS, but I also work with Twig, Blade and Razor. I exclusively use Amazon Web Services (AWS);
EC2 to host the servers, RDS for MySQL databases and DynamoDB for NoSQL. For caching, I use Redis. For queues I use SQS, which works brilliantly.

### Solution Design
All apps I create are designed to scale, and avoid a single point of failure. I like to sleep at night! Because
everything is designed to be stateless, I use Amazon's spot instances to keep costs down but availability high. For peak
demand, I can increase the number of instances running and bring it back down during quieter periods.

### Software Design
I'm a big fan of Domain-Driven Design (DDD), and even more so now apps are being developed with AngularJS in the front
end and a REST back end. Behaviour Driven Development (BDD) fits in neatly with this, and was the catalyst that got me
fully into test driven development (TDD). BDD makes it so much easier to convert the business requirements (the user
 stories) into a user acceptance test, meaning the dreaded "That's what I said but not what I wanted" happens far less
 now than it used to.

### Development Process
Describe git workflow with remote worker and also insight labs, scutinizer CI etc.

I plan to create a full blog post on my workflow shortly.

### Deskill
What do I mean by deskill? I'm talking about making it easier to maintain the apps once deployed. Trying to be a
developer and a systems administrator isn't easy and can lead to things being missed. If the systems admin part can be
outsourced, for example using pre-built EC2 instances and scripts to customise them[^1], it gives more time to focus on
 improving and growing the app.

Recently I've been looking into simplifying things even futher, and docker is at the top of my list. [Amazon's EC2 container
service](https://aws.amazon.com/blogs/aws/cloud-container-management/) looks like it will be a big help.

### Plans for this blog
I created this blog because I've been helped along the way by so many great people online, who have produced some excellent resources that
 have taught me so much over the last 3 years.

 I want to give something back, and hope that coming from the perspective
 of a serial entrepeneur who can see the gap in the market needing filled, who can define the business requirements, who has the skills to design the solution and can co-ordinate
 the development whilst also coding parts himself might be interesting, and hopefully useful for you.

[^1]: On this subject, I highly recommend the book AWS Scripted - the link to it is on the "Books I've read" page.