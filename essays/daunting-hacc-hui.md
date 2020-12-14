---
layout: essay
type: essay
title: Daunting HACC-Hui 
# All dates must be YYYY-MM-DD format!
date: 2020-12-13
labels:
  - Software Engineering II
  - Meteor application
  - Slackbot
  - Group Management
  - ICS 414
--- 

<img class="ui centered big rounded image" src="../images/essay ss7.png">

## What is HACC-Hui?
[HACC-Hui](https://hacc.hawaii.gov/) is an easy-to-use system that provides simpler team formation processes for participants of the Hawaii Annual Code Challenge. In the past, the team formation process at HACC has been ad-hoc and informal, which leads to high failure rates for good team formations. HACC-Hui is capable of creating teams and customizing a lot of options such as making a team “open” or “closed,” specify skills, tools, and challenges, and more. HACC-Hui also provides users with a personal profile, which displays details about one’s skills, tools, and challenge interests, and demographic level. It can also indicate if the person is searching for a team or not. These HACC-Hui features help users easily create their desired teams and find team members without effort.

<img class="ui medium right rounded floated image" src="../images/essay ss6.png">

## Creating HACC-Hui
In the process of creating our HACC-Hui, I was placed in a team of four with three other developers: our team name being [MIJJ](https://github.com/MIJJ-HACC/HACC-Hui), representing each of our first name initials. The project was broken into 3 main milestones, 2 of which were worked on with the group and the final milestone with the entire class. In milestone 1, I created a delete function for users that allows them to delete their HACC-Hui account. For HACC-Hui, it was not simply creating a button that asks if they want to delete their account and deleting it if they answer yes. I had to make sure that when a participant decides to delete their account, we redirect them to a page that records why they are leaving (in order to improve the HACC experience for the next year) and storing that data in a collection. In addition to allowing participants to delete their accounts, I helped create the team creation page. This was done using a schema made specifically for this page in order to create a team in the database, along with the related collections. Uniforms makes the fields for the team creator, which includes the team name, availability, description, and more. I helped with creating the submit function which takes the submitted data and creates a team with it.
<div class="ui medium images">
  <img src="../images/essay ss1.png">
  <img src="../images/essay ss2.png">
</div>

For milestone 2 I was assigned to creating the update team page. This page allows team owners to update their team if they would like to. To create this page, I used uniforms in order to create fields that are prefilled with data of the team before changes. When the team owner changes a field, that is updated in the database when submitted. Because of the fact that users can create multiple teams if they would like to, I had to make the Update Teams button on the NavBar a dropdown menu that displays the teams this user owns, which allows them to choose which team they would like to update.
<img class="ui large centered image" src="../images/essay ss3.png">

<img class="ui medium right rounded floated image" src="../images/essay ss4.png">
For the last milestone, the students in the 414 class worked together to finish up the HACC-Hui project. What I worked on in this final push was first adding a view invitations page that is specific for the admins in which they are able to see all invitations sent out to participants of HACC. This was done by taking the team invitations collection and displaying each invitation made through a list. Another issue I took on was to make sure when a participant deletes their account, I clean up the team memberships. Because of how the collection class hierarchy works for HACC-Hui, I had to delete team memberships for a participant through different collections in the database. I also made it so that if a participant is an owner of a team and they decide to delete their account, ownership is transferred to another team member of that team, or if there is not anyone else on the team left, the team is deleted. Other simple issues I worked on was to not allow duplicate team members for teams and to update the view teams page to show GitHub repo and Devpost links.
<img class="ui medium right rounded floated image" src="../images/essay ss5.png">

<img class="ui small left circular floated image" src="../images/essay ss8.png">
## Working with team MIJJ
My team, team MIJJ, consisted of developers Joshua Hartmann, Isaac Lee, Joel Sikkink, and myself. The team process consisted of using GitHub to organize milestones and issue assignments. Most milestones consisted of at least four issues, which helped distribute work evenly among everyone. Every milestone, we posted issues through GitHub and team members chose what issue they wanted to tackle. Whenever a team member wanted to discuss issues they had on the project, or if they wanted help with their particular issue, they would message the other team members through discord. Most of the time, things were resolved through the text channels, but other times voice channels were used too. 

A lot of the time, each team member did their own thing and we rarely checked up on other team members before the deadline. We simply worked on our issues and pushed the changes to master when we finished them. Some things that might have been problematic with this style of teamwork, is that it wasn’t really “team” oriented since we all did our issues by ourselves and rarely communicated with each other throughout the weeks. The responsibilities I had in the team includes deleting HACC-Hui accounts, creating teams, and updating team functions. 

## A crazy new experience
Coming into ICS 414 after 314, I thought I would be able to breeze through this class since I did well in ICS 314. That was a grave misunderstanding. I was met with a lot of unknown problems that I have not tackled before. The tasks we were assigned, and the course road map were very intimidating, and quite honestly made me very anxious. I think I have a hard time diving into things that look intimidating when they are not, and this is a prime example of that. Things that went well during this class was that I was able to properly experience what it is like being a developer for an application. It was really difficult for me because unlike ICS 314, there were not “correct” ways to solve an issue, and a lot of the problems I faced were new to me. Because a lot of the things in this class are new, many things were done on the fly, which did not go so well for me because I like to have set problems that have set solutions. But overall, I think this was a really good experience for me because, in the real world outside of classes, things do not work out like that. There will be many unknown obstacles, and you simply have to overcome them yourself through research and repetition. I learned how to individually work on code to solve an issue, and also work as a team on an actual project that will have actual customers.
