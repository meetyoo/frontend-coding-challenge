# Frontend Coding Challenge - Video Player

## Challenge Overview

* Develop a web video player using Vue.js 3 (preferably with TypeScript), Composition API, Vite, and SCSS. 
* The goal is to create a functional and visually appealing video player.
* You can use AI for research or coding. But we will read the code and you should be able to understand it, because you will explain it to us.

## Challenge

The challenge comes in tiers which are kind of milestones for the application. Progress along the tiers, the higher you get the better in the evaluation. But keep the code maintainable.

### Tier 1: Basic Video Player
* Create a functional video player capable of playing the provided webm video.

#### Resources
* the .webm to play https://meetyoo-code-challenge.s3.eu-central-1.amazonaws.com/live/S14JJ9Z6PKoO/bf1d4883-5305-4d65-a299-cbb654ef1ed9/video.webm opening this url should play the video directly in chrome. Now you just need to integrate it into a video element.

### Tier 2: Custom Control/Seek Bar
Implement a unique control bar including:
* Play/Pause button
* Seek bar
* Volume control
* Be creative and add other things if you want

### Tier 3: Chapter Display
* Use the DASH file to retrieve the chapters and display them in the control bar.
* Inside the Full.xml (see Resources) there is an element which looks like this `<EventStream schemeIdUri="urn:mpeg:dash:event:2012" value="chapters">` inside this element are the chapters with the timestamps. Use these information to visualize in the ui.
* How you visualize the chapters is up to you, be creative and show us the coolest UI you can think of.
* Clicking on a chapter should seek the video to the chapter

#### Resources
* Dashfile full.xml (starting point for dash) --> https://meetyoo-code-challenge.s3.eu-central-1.amazonaws.com/live/S14JJ9Z6PKoO/bf1d4883-5305-4d65-a299-cbb654ef1ed9/full.xml

### Tier 4: Transcript Visualization
* There is also a transcript file available
* use it to put subtitles in the video (with a toggle to de-/activate)
* Also you could visualize the transcript somewhere else other than the subtitles.

#### Resources
* https://meetyoo-code-challenge.s3.eu-central-1.amazonaws.com/live/S14JJ9Z6PKoO/bf1d4883-5305-4d65-a299-cbb654ef1ed9/transcript.vtt

## Tech Stack
* Vue.js 3
* TypeScript (preferred)
* Composition API
* Vite
* SCSS

## Expectations
* Application should not use any extra library which is not really neccessary.
* Design Expecation: Video players are quite common in the web, it should look and feel like a common video player. Mayby you integrate some cool aspects as well, up to you.
* Branding: if you need some branding inspiration check out our website: https://www.meetyoo.com/en and grab some colors from there.
* All files should be retrieved from the locations indicated here, they should not be part of your project. Vite should not bundle them. make requests to retrieve them.
* The result will be tested in Chrome, and we will also check how the mobile version looks like.
* Unit tests are not neccessary.

## Evaluation Criteria
* Functionality of the video Player
* Visual appeal and user experience
* Basically how far you've come in the tiered challenge list
* Code quality, organization and maintainability
* Utilization of provided technologies (Vue.js 3, TypeScript, etc.)
* Accessibility
* Responsiveness (will be checked on Chrome, including mobile viewports).
* Usage of browser APIs.
* Error handling
* 

## Additional Information
* The challenge allows for showcasing various skills and experience in frontend development.
* Applicants are encouraged to add features and improvements beyond the basic requirements.
* If at any point in time you need, the used codecs. We use vp8 (video codec) with opus (audio codec).

## Submission
* The Deadline for the submission is the 27th of April 2025. 
* Create a github repo and share the link with us via email
* If you have questions throughout the challenge, **do not hesistate** to contact us
