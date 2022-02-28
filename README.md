# Notiefi

## What Is Notiefi?

Today, most college students share resources using programs like Discord or Slack. However, despite the convenience of communicating on such group-chatting platforms, organization of resources via message streams becomes difficult. Noteifi solves this problem by creating a platform that compiles all valuable resources by course. Students are able to post their own notes for each of their course lectures. These notes can be viewed by future students as well. Along with notes, students can also post other lecture resources like links or visualizers.

Unlike Course Hero, which also provides students with resources, students will not be anonymous on Noteifi. In doing so, Noteifi creates a tight-knit community between enrolled students. By conversing with each other directly, students can leave comments on posted notes and resoures. Unlike similar platforms, we believe that viewing notes should be unmonetized, thus making education more equitable.

## For Whom is Notiefi For?

Notiefi is by students for students.

Every semester, many students scour the internet, compiling numerous lecture resources, whether they are actually helpful or not. Providing students a platform where they can post these resources in a moderated, unmonetized setting will democratize knowledge and inform future students in their course decisions.

As students, we're better able to make judgments as to what features should be implemented on note sharing platforms. Our connections to other students will direct the creation of our app since we are surrounded by the needs of our user base. 

## How Will We Implement Notiefi?

Before students can use Notiefi, we first authenticate that they are a student at a verified college.

Students will be placed into user groups respective of the college that they attend based on the domain name of their college email address. Once the user is signed in, they can search for and bookmark their courses for easy access on their profile.

There are two sides to each course tab: chatting and categorized resource sharing. On the chatting side, students can communicate with each other in a moderated group chat setting. On the resource sharing side, students can view each corresponding lecture. Upon clicking a lecture, a Reddit-style content page will appear with posts of lecture resources. While viewing these resources, students can upvote the ones the find useful or downvote the ones that seem irrelevant. 

Posts are automatically sorted by the highest upvotes. In doing so, higher quality posts will appear at the top of a lecture page. Thus, students can spend less time worrying about the quality of the resources they are getting and more time studying the resources. Students can also report posts for any academic integrity violations. Such reports will automatically be redirected to the instructor of that course. Since there is no anonymity upon registration, reported posts can be dealt with accordingly.

## Scope

For user registration, we can simply use Google's OAuth to get the user's email and full name without implementing much else for verification.

Although the idea of having to add every college's course sounds complex, we think we're able to accomplish it by just parsing each college's catalog and accomplishing something that's similar to [Coursicle](https://www.coursicle.com/).

We also think that with React, we're able to accomplish most of what we have in mind for the design of the site and the specific pages that were mentioned earlier.