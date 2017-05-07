---
layout: post
title: CocoaPods and Git
author: Hunter Stanton
---

# CocoaPods and Git
So recently while working on an app, I started to think about how I should deal with committing when I'm using CocoaPods. Committing the compiled pods themselves seems unclean - it bloats a repo and means cloning that repo takes a bit more time. This can be a problem when using a slow or data-capped connection, as some repos can grow pretty large if you're using many different pods.

On the other hand, it can cause problems with branches if you don't commit your Pods directory. Dependency management can become a headache if you're working with a repository that has a lot of branches, as you'll need to run pod install whenever you switch to a new branch. This, as you can imagine, wastes a lot of time that could otherwise be spent on actually developing.

I usually just commit the pods directory, but when I'm working on Nexus Heights apps, I am usually the only one working on the code, so it doesn't really matter. In a team scenario, however, I definitely think that committing the pods directory is preferable. I guess it's just up to what the team agrees on.




