# MyStudyGroup
CMPT 276 Project

## Installation Steps

1. create local db "mystudygroup_development"
2. bundle install
3. rails db:migrate
4. rails db:seed
5. rails s

*admin seed  -  email: a@a.com, password: 123456
*user seed   - email: b@b.com, password: 123456 

## Project Abstract

MyStudyGroup provides a platform for students who want to find a study partner or group nearby. The application will provide a user’s own profile and features including: creating groups, finding people with the same course near you, pinning "study spots" for locations to study at, private chatting with group members and document sharing amongst groups.

The target users are mainly university students (age 18-23) who have the need for seeking for study partners or groups in school.

Currently, the problem for some students is that sometimes it is hard to find someone to study or discuss the assignments with. People in study rooms tend to wearing their earphones and study alone. By allowing students to find study groups, it will enhance their studying and they will be able to cover more content in depth. It is stressful enough as it is to be stuck on a problem or a theory that you can't wrap your head around. We believe the social aspect of MyStudyGroup can reduce barriers between students, save them trouble from finding classmates around them after lectures, and bring out the full benefits of study groups.

## Project Scope

The main feature of MyStudyGroup is that it provides a platform for students who are enrolled in the same course to find a study group or partner at a nearby location. It utilizes the Google Maps API as users will be able to pin a location on the map to form a “study spot” for a particular course. Other users that are enrolled in that course will be able view and join this study spot. When signing up, a user will be able to sign in with their Facebook profiles and that sets up their user profile. MyStudyGroup also provides an instant messaging component where users in the same course can communicate in. These features will allow a user to create a profile, find/create/join a course, message anyone in that course, share documents, and be able to find a study group.

## User Stories

User story - A new user will be able to login with their facebook  or create a new profile. Then, the user will be prompted with a list of courses that they can join. Once they have picked their courses, they will see nearby students or study spots pertaining to their course list.  Users can contact other students via the application’s messaging app or they can join a study spot.

Admin story - An admin has the ability to view any user’s profile and edit them (including destroy). They can remove a user from a course for any reason.

## Competitive Analysis
There are apps on mobile that are similar to MyStudyGroup. In particular, GroupIt on iOS has features like finding nearby students in a particular course. What our app would allow for is the ability to meet new people with similar goals and have the ability to use our app as a platform to work efficiently amongst them.
