---
layout: post
title:  "Sus Tracker"
display_title: "Sus Tracker"
description: "We built the first voice real-time assistant for Among Us. Help us test it!"
date:   2021-02-11 00:00:00 -0700
last_modified_at: 2021-02-11 00:00:00 -0700
tags: [Among-Us, Video-Games, Alexa]
image: /assets/img/sus.png
image_svg: /assets/img/sus2.svg
sitemap: false
display_excerpt: "We built the first voice real-time assistant for Among Us. Help us test it!"
---
### What is this?

Sus Tracker is the first real-time voice assistant for [Among Us](https://store.steampowered.com/app/945360/Among_Us/). Right now, you can use it to help you keep track of "sus" (AKA suspicion) of other players.

&nbsp;
### Requirements

You'll need the following to help us test Sus Tracker:

- An Amazon account
- A Windows PC
- An Alexa device OR the Alexa app installed on your smartphone (associated with your Amazon account)
- Among Us for Windows ([Steam version](https://store.steampowered.com/app/945360/Among_Us/))
- [Sus Tracker for Windows](https://www.microsoft.com/en-us/p/sus-tracker/9pk9lvfx1rt9)

&nbsp;
### Instructions

1. Make sure you have all the requirements in place. Then install [Sus Tracker for Windows](https://www.microsoft.com/en-us/p/sus-tracker/9pk9lvfx1rt9) on your Windows PC and run it -- you will be asked for a six-digit code.

2. With your Alexa device in listening distance, say "Alexa, open Sus Tracker." -- you will then hear a brief explanation and a six-digit code. Enter that six-digit code in the Sus Tracker Windows app -- if you missed it, you can get your code again by saying, "Alexa, get my code with Sus Tracker."

3. Run Among Us and start or join a game.

4. As you become suspicious of a player, assign sus to them by saying "Alexa, add sus to {color of the player} with Sus Tracker." You can add sus to a player multiple times with the same command, and you can clear sus from a player by saying "Alexa, clear sus from {color of the player} with Sus Tracker." You can clear sus from all players by saying "Alexa, clear all sus with Sus Tracker."

5. When it's time to vote, you can get a sus summary by saying "Alexa, get sus with Sus Tracker." All sus resets at the end of the round automatically.

6. Have fun!

&nbsp;
### All possible commands

Preface every command with "Alexa ..."

- "Get my code with Sus Tracker." -- provides your login code.
- "Get sus with Sus Tracker." -- provides a summary of sus.
- "Add sus to {color of the player} with Sus Tracker." -- self-explanatory. Example: "Add sus to cyan with Sus Tracker."
- "Clear sus for {color of the player} with Sus Tracker." -- self-explanatory.
- "Clear all sus with Sus Tracker." -- clears sus for all players.

&nbsp;
### Playtest survey

We know you love Among Us, but we want to know how we can make Sus Tracker better.

<form action="https://formspree.io/f/mknpawjd" method="POST">
  <input type="hidden" name="_subject" value="New submission!" />
  <label for="skill"><b>How would you best describe your Among Us skill level?</b></label>
  <br><br>
  <select id="skill" name="skill">
    <option value="beginner">Beginner (played less than 3 times)</option>
    <option value="intermediate">Intermediate</option>
    <option value="advanced">Advanced (played more than 10 times)</option>
  </select>
  <br><br>
  <label for="frustrating"><b>What was the most frustrating moment or aspect of what you just experienced?</b></label>
  <p></p>
  <textarea name="frustrating" placeholder="Frustations here"></textarea>
  <br><br>
  <label for="favorite"><b>What was your favorite moment or aspect of what you just experienced?</b></label>
  <p></p>
  <textarea name="favorite" placeholder="Favorites here"></textarea>
  <br><br>
  <label for="wanted"><b>Was there anything you wanted to do that you couldn’t?</b></label>
  <p></p>
  <textarea name="wanted" placeholder="Desires here"></textarea>
  <br><br>
  <label for="magic-wand"><b>If you had a magic wand to wave, and you could change, add, or remove anything from the experience, what would it be?</b></label>
  <p></p>
  <textarea name="magic-wand" placeholder="Magic wand ideas here"></textarea>
  <br><br>
  <label for="description"><b>How would you describe this game to your friends and family?</b></label>
  <p></p>
  <textarea name="description" placeholder="Description here"></textarea>
  <br><br>
  <label for="info"><b>What information would you find most useful while playing Among Us? Pick your top 5.</b></label>
  <p></p>
  <input type="checkbox" id="crewmate-session" name="crewmate-session" value="crewmate-session">
  <label for="vehicle3"> How many times you have been a crewmate this session</label><br><br>
  <input type="checkbox" id="impostor-session" name="impostor-session" value="impostor-session">
  <label for="vehicle3"> How many times you have been an impostor this session</label><br><br>
  <input type="checkbox" id="crewmate-lifetime" name="crewmate-lifetime" value="crewmate-lifetime">
  <label for="vehicle3"> How many times/percentage you have been a crewmate lifetime</label><br><br>
  <input type="checkbox" id="impostor-lifetime" name="impostor-lifetime" value="impostor-lifetime">
  <label for="vehicle3"> How many times/percentage you have been an impostor lifetime</label><br><br>
  <input type="checkbox" id="impostor-current" name="impostor-current" value="impostor-current">
  <label for="vehicle3"> How many impostors there are in the current game</label><br><br>
  <input type="checkbox" id="other-impostors" name="other-impostors" value="other-impostors">
  <label for="vehicle3"> If you're an impostor, who the other impostors are in the current game</label><br><br>
  <input type="checkbox" id="win-loss-lifetime" name="win-loss-lifetime" value="win-loss-lifetime">
  <label for="vehicle3"> Your win-loss record lifetime</label><br><br>
  <input type="checkbox" id="win-loss-session" name="win-loss-session" value="win-loss-session">
  <label for="vehicle3"> Your win-loss record this session</label><br><br>
  <input type="checkbox" id="win-loss-streak" name="win-loss-streak" value="win-loss-streak">
  <label for="vehicle3"> Your current win/losing streak</label><br><br>
  <input type="checkbox" id="emergency" name="emergency" value="emergency">
  <label for="vehicle3"> How many emergency meetings you have left</label><br><br>
  <input type="checkbox" id="voting-long" name="voting-long" value="voting-long">
  <label for="vehicle3"> How long the voting time is</label><br><br>
  <input type="checkbox" id="speed" name="speed" value="speed">
  <label for="vehicle3"> How fast the player speed is</label><br><br>
  <input type="checkbox" id="bright" name="bright" value="bright">
  <label for="vehicle3"> How bright the crew light is</label><br><br>
  <input type="checkbox" id="kill-cooldown" name="kill-cooldown" value="kill-cooldown">
  <label for="vehicle1"> How long the kill cooldown is for the current game</label><br><br>
  <input type="checkbox" id="kill-distance" name="kill-distance" value="kill-distance">
  <label for="vehicle2"> How far the kill distance is for the current game</label><br><br>
  <input type="checkbox" id="common-tasks" name="common-tasks" value="common-tasks">
  <label for="vehicle3"> How many common tasks each player has for the current game</label><br><br>
  <input type="checkbox" id="long-tasks" name="long-tasks" value="long-tasks">
  <label for="vehicle3"> How many long tasks each player has for the current game</label><br><br>
  <input type="checkbox" id="short-tasks" name="short-tasks" value="short-tasks">
  <label for="vehicle3"> How many short tasks each player has for the current game</label><br><br>
  <input type="checkbox" id="your-tasks" name="your-tasks" value="your-tasks">
  <label for="vehicle3"> How many of your tasks are left for the current game</label><br><br>
  <input type="checkbox" id="name-your-tasks" name="name-your-tasks" value="name-your-tasks">
  <label for="vehicle3"> Which of your tasks are left for the current game</label><br><br>
  <input type="checkbox" id="where-your-tasks" name="where-your-tasks" value="where-your-tasks">
  <label for="vehicle3"> Where your remaining tasks are for the current game</label><br><br>
  <input type="checkbox" id="percentage-all-tasks" name="percentage-all-tasks" value="percentage-all-tasks">
  <label for="vehicle3"> The percentage of all crew tasks completed</label><br><br>
  <input type="checkbox" id="percentage-your-tasks" name="percentage-your-tasks" value="percentage-your-tasks">
  <label for="vehicle3"> The percentage of your tasks completed</label><br><br>
  <input type="checkbox" id="crew-etc" name="crew-etc" value="crew-etc">
  <label for="vehicle3"> For crew tasks, the estimated time of completion</label><br><br>
  <input type="checkbox" id="your-etc" name="your-etc" value="your-etc">
  <label for="vehicle3"> For your tasks, the estimated time of completion</label><br><br>
  <input type="checkbox" id="fake-tasks" name="fake-tasks" value="fake-tasks">
  <label for="vehicle3"> If you're an impostor, where your fake tasks are</label><br><br>
  <input type="checkbox" id="sus" name="sus" value="sus">
  <label for="vehicle3"> Instructions to complete a specific task -- e.g. how you do the canister task?</label>
  <br><br>
  <label for="other-ideas"><b>Anything else we didn't think of?</b></label>
  <p></p>
  <textarea name="other-ideas" placeholder="Other ideas here"></textarea>
  <br><br>
  <p><b>Can we contact you for follow-up questions?</b></p>
  <input type="radio" id="yes" name="yes" value="1">
  <label for="yes">Sure</label><br>
  <input type="radio" id="no" name="no" value="0">
  <label for="no">Nah</label><br>
  <br><br>
  <input type="text" name="name" placeholder="Your first name" />
  <br><br>
  <input type="email" name="_replyto" placeholder="Your email address" />
  <br><br><br>
  <button type="submit">Submit</button>
</form>