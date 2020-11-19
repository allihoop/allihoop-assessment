# Allihoop Technical Assessment

Hello! We are excited that you are taking this technical assessment and look forward to reviewing your solutions to each of the challenges.

Please follow the instructions in this readme carefully, we ask that you work on the solution by yourself and submit only your own code for each of the tasks.

Good luck and have fun!

---

## Table of contents

- [1. Getting started](#1-getting-started)
- [2. Technical tasks](#2-technical-tasks)
- [3. Submission](#3-submission)

---

## 1. Getting started

### 1.1 Create a new private git repo

Login to your Github/Bitbucket/Gitlab account and create a new **private** repo named `allihoop-technical-assessment`.

_❗️**Important**: Please keep this repo private._

## 2. Technical tasks

We expect you to have two branches `master` and `develop`. For each task we ask that create a branch from your `master` with the task name. E.g:

```
$ git branch <task-1-login-form>
```

Please try to spend spent no more than 3 hours in total.

_❗️**Important**: Raise one PR for each task. Include a brief summary so we can understand your approach and thinking. If you are not able to complete a task to production quality, we will be expecting the PR description to highlight what is missing, and what should have been added or changed with more time. You are allowed to merge your feature branches to develop but please refrain from merging any branches to master._

---

### Task 2.1 - Login form

⏱: 15-30 minutes

As a customer, I want to be able to login or sign up.

**Acceptance Criteria**

On the initial landing page:

- Show a form to login/signup.
- Register/Validate the user using auth service. Can use any 3rd party authentication service(Firebase/Auth0/Okta/OpenID etc)
- Form validations and smooth transitions.
- Create at least one user with admin privileges

### Task 2.2 - Creating Facilities

⏱: 45-60 minutes

There is a community where there are multiple facilities. For e.g. a community in Stockholm has multiple facilities like Laundry room, Recreational centre, Prayer room, Ping pong table etc for residents.

Only admin user can create multiple facilities for a community.

**Acceptance Criteria**

- Show a form to create/edit a new facility.
- Persist the information about the facilities in SQLite or any other state management library.

### Task 2.3 - Booking Facilities

⏱: 60 minutes

Residents should be able to view facilities with its availability and book them based on their requirements.

**Acceptance Criteria**

- Users can view and book facilities for a certain date.
- Available time slots for the date can be in an hour interval.
- Disable the unavailable time slots.
- Persist the information about the bookings.

### UI Designs

Please watch the video in assets folder for more details. It shows the exisiting functionality and hopefully helps you understand the problem statement better.
![Video](./assets/facilities.mp4)

---

💡 Bonus task

### Task 2.4 - Accessibility

⏱: 60 minutes
As a disabled customer, I want the app to be accessible.

**Acceptance Criteria**

- The acceptance criteria is open to your interpretation for this task.
- Based on your knowledge (and limited time) think about what you'd consider a priority for accessibility and implement some improvements.

_💡**Tip**: Do want you can within the time frame, add additional tasks you'd like to have completed to your PR as a comment._

---

## 4. Submission

When you have completed your tasks, build and send us the APK and please add us as contributors to your private repo:

- `ajaswal`
- `samuel5774`

Now let us know you have finished the assessment. We will communicate the next steps to you.

If you have any feedback or questions on the assessment we'd love to hear your thoughts!

Thank you,

From the Allihoop team.
