---
title: 'Zombie Code—One More Reason for a Slow Shopify Store'
date: 2019-03-25 15:12 +0200
cover-image: zombie-nathan-wright-669713-unsplash.jpg
---

Brian was concerned with the speed of his fishing gear Shopify store. After all, most of his customers are accessing it on their phones, hurrying to prepare for a relaxing weekend of angling.
Even those staring at water for hours on end couldn’t bear the boring 12 second load. So he reached out for help.

I started with updating the store theme to its latest version. But the theme updater app couldn’t deal with it on its own. Fixing the errors by hand I’ve discovered a bunch of suspicious files. I couldn’t attribute them to any of the apps Brian got already installed. Or he was using services that weren’t on the Shopify App Store, hence no trace of them in his store’s Apps section. I had to check.

To be sure, I asked the Brian for confirmation of my suspicions:

— Brian, are you using this app?—I asked, pointing at a marketing website promoting a Shopify app I traced the code back to.

— No. We just tested that 3 months ago. It didn’t work as expected so I uninstalled it.

— Ok, and what about that app?

— This got replaced by another I was telling you about last time we talked. I uninstalled it too, as I read I should uninstall the apps I’m not using.

— Well, you did the right thing, but sadly that didn’t solve your problem completely. That leftover zombie code is now responsible for over 2s of slowdown… 


This was another case of poorly designed apps slowing down the store of a client. I guess this had happened to you, too—you removed some apps in the hopes of speeding up your site, but to no avail—the store got no faster…

## A ~~Star~~ Zombie is Born
So how did Brian still get code from apps he had already uninstalled? Shouldn’t it be all gone?

Well, in theory, yes. Shopify advises developers to restrict the code to their own server and not touch your store’s theme files. This way an app uninstall is guaranteed to be clean.

But in practice, the situation is different. **The easiest and most straight-forward way for apps to be implemented is through direct modifications to the theme code**. Making an app work without touching the original theme code proves to be an advanced skill not all app creators care to practice. And when you remove the app from your store you end up with zombie code in your theme that still loads and slows down your website.

## Divorcing an App isn’t Always Smooth For Merchants on the Shopify Platform

Judging by the amount of leftover code I’ve found in Shopify stores during the past 3 years, the following is quite common: most app developers are just concerned with developing the functionality you need and enabling you to use it—that is the installation and operation of the app. After all that’s when they can charge you money—by delivering the value you expect.

But what happens when an app is no longer valuable to you? Should you lose money (by having a slower store) even after you’ve already uninstalled it?

---- 
During the third year of Industrial Design school they taught us that designing the process of “getting rid of a product” is as important as designing the product itself. Sooner or later people will have to part ways with it and if the process is complicated, humiliating or harmful—they just won’t do it. And they’ll suffer because of that. The negative implications will then fall on the brand that produced it.

---- 

### Rarely Considered Important
Apps that didn’t pass through the first development stage of “straight-forward implementation” leave code that still loads after they go away. But they don’t have to be mature to take proper care of removing themselves from your store. It is just that this is rarely considered important—“Well, our app is so good no one would want to uninstall it!” thinks every project manager while prioritizing new features over the improvement of their uninstall procedure. 

And this isn’t just limited to apps from small dev shops—big famous app developers are guilty of it too. 

That’s why, if your store’s been running for a while and you’ve been trying apps on and off, there is a high chance you have zombie code in your theme. That dead, leftover code is still loading and hungry for your visitors’ resources, slowing your page load time but giving you no benefit. 