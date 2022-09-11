# Problem Statement

Commenting systems, also called commenting platforms, add commenting functionality to websites (such as blogs and news sites) that post content. 
Commenting capabilities engage an audience, making content more memorable and more likely to be shared. 
Comments are also an easy metric by which content creators can measure the performance of their work and how well it is received.

A staple of any commenting system is a text comment box where users can generate their own comments and leave them on a specific piece of content. 
However, some comment platforms also feature "reaction" functionality.


# Requirements
As part of this question, we will implement a Commenting System with the following capabilities:
- Users can add 1 or more comments to a post/blog
- Each comment can have a reply option. Assume reply to a reply is in the same thread and not nested.
- While replying, automatically tag the user you are replying to.
- Each comment/reply may have reaction counts and users associated with it. Reactions include:
    * Like
    * Laugh
    * Sad
    * Support
    * Interesting
