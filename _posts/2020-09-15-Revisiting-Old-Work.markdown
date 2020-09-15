---
layout: post
title:  "Revisiting Old Work"
date:   2020-09-15 14:00:00 -0500
categories: Disco Tray Studios
---

My most recent task for [Disco Tray Studios](https://discotraystudios.github.io/) was going through my old Hendrix Assessment Survey project, and adapting the previous site's SQL table to not only hold the previous survey data, but also data from a different format of survey. This week, I'll try to break down exactly how that whole process went.

The first thing to do was to review what had already been done. Unfortunately, the SQL table as it existed during the project was hosted primarily on a server, so I would have to reconstruct the original database architecture myself. It was simple enough, with the only real challenge being getting the software required to actually make the SQL database.

Step 2 was, at Dr. Goadrich's suggestion, cleaning up the old SqL table. This primarily consisted of two things: renaming previously misleading tables to more accurate names, and seeing if there was anything that could be done to the structure that would make it work better. Luckily for me, Dr. Goadrich had given some really good advice on exactly that. The splitting of some of the tables into multiple many to many connective tables made the flow of deta much clearer.

I went into this under the impression that the final step, adding the new requirements that this version of the project would require, would be the most difficult. To my surprise, it was the easiest. The previous restructuring made additions far easier than expected, and I got the additional features implemented far below my estimates. It seems that (and here's the main takeaway if you want to find one) when attempting to make additions to previous work I've done, it saves time in the long run if my first step is reviewing and fixing mistakes before any additions are actually made.