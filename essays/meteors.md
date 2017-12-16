---
layout: essay
type: essay
title: "Meteors"
date: 2017-10-26
labels:
  - Software Engineering
  - Meteor
---

<h2>Overview</h2>
<p>
	Getting accustomed to Meteor at the start has been quite tough because really the most reliable way I've found was to just copy down tutorials on how to implement things. At that point, it became tough to start doing things without a guide telling me step-by-step exactly what I needed to do. I think the biggest challenge that I still face now is that I'm still relying on "training wheels" and slowly figuring out how to overcome that.
</p>
<h2>Your application is crashing...</h2>
<p>
	Admittingly, I had brushed off Philip's warning on forgetting to import things. "I never forget things, I'm perfect at this," is what I told myself, but to my dismay, I think I've made this mistake every time I attempted the practice WODs. Adding on to my "perfection", syntax errors was the key culprit to every time my program didn't want to cooperate. Do you know how hard it is to look through your code and distinguish where you put 'contacts' instead of 'contact' where it needed to be? The IDE doesn't detect an error, and it's frustrating. Although this isn't a Meteor specific issue, I feel like using a framework with multiple files that don't really return any errors makes this task much more difficult.
</p>
<p>
	Aside from my own shortcomings, I think the other thing I need to keep in mind is where each reference to another file exists, and always remember that if I update one file, I might need to update those files in order for things to work smoothly. 
</p>
<h2>It's alright</h2>
<p>
	That's all I have to say about it. I don't particularly love or hate it, but I'll go over what I do like. This might apply to all frameworks but I like how I can tie multiple files into a single page. It never occured to me that a simple index page could be partitioned into a header.html, footer.html, and any old page, and have that page use the header and footer.
	Another thing I like is the simplicity of MongoDB. I'm not too informed on how it works exactly, but after taking the Databases class, I can say this is WAY easier to create and manage simple databases.
</p>
<p>
	The few things I particularly dislike is that when I mess up some file in the same directory as other files, those other files just start to break, even if they have no relation to eachother. I noticed this when I made the add-contact-page.html for my digits assignment and had a few errors, but none that traced back to the home-page.html. This caused my home-page.html to lose all of its CSS and I sat there trying to figure out what I did wrong with my home page when I had done nothing at all to it. Now, it may have been related in some other way that was so deeply rooted, but the whole process of figuring it out was stressful.
</p>
<h2>Summary</h2>
<p>
	My ego is inflated. I make many syntax errors and get mad at Meteor instead. But I'm learning to overcome this... stepping stone to become a better programmer. Meteor has a lot of things I don't understand but that is why I cannot love or hate this just yet as there may be a light at the end of the tunnel that makes me love the framework. Or no light and I end up hating it.
</p>
<p><a href="https://github.com/blairmuraoka/digits-1">Digits Project Repository.</a></p>
