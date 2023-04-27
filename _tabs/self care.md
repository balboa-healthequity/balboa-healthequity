---
icon: fas fa-info-circle
order: 1
title: Self Care
---

![Self Care Title](../assets/img/selfcaretitle.jpeg)

## What is self care and what can it help you with?
Self care is the different ways that you can take care of yourself and your mental and physical health. Self care is also a coping mechanism that can help you deal with daily stress and other things that can impact your mental health and overall well being. Self care can be anything that makes you feel good like exercise, mindfulness, eating healthy, journaling, and hanging out with friends.

## Examples of Self care
- <div class="collapsible">
    <p>Exercise: lowers cortisol or stress hormone and increases endorphins which make you feel more positive.</p>
    <p>Exercise can also be a way to build community, especially by joining sports teams or exercising or going on a run with friends.<br><br> Examples of different types of exercise:<br> Running, going to the gym, walking, biking, gardening, playing a sport, yoga</p>
  </div>

  ![Exercise Image 01](../assets/img/exercise01.png)
- <div class="collapsible">
    <p>Mindfulness allows you to focus on yourself and on one thing at a time.</p>
    <p>You stay in the present, and be mindful of your emotions and surroundings. Some common forms of mindfulness are meditation, and breathing exercises. Setting time for mindfulness often and trying to be consistent about it is how you get the most benefits. In addition, it's good to start small with a couple of minutes of mindfulness if you are not used to it because then you can build consistency and after that you can start to do mindfulness or meditation for longer periods of time.</p>
  </div>

  ![Mindfulness](../assets/img/minedfulness.jpeg)
- <div class="collapsible">
    <p>Journaling: Writing how you feel</p>
    <p>Journaling is a way to express yourself and your emotions in a positive way. When we are stressed, we get stuck in how we are thinking but by journaling we can write down what is happening and what is bothering us and be able to release the negative thoughts and think of solutions.<br><br> Example of prompts that you can use to journal for your mental health:<br>- List 10 things or people that you are grateful for?<br>- What coping mechanisms do you know you use? If they are unhealthy or toxic coping mechanisms, how do they negatively affect the situation or yourself?<br>- List 5 things you are stressed about that you can change and then make a plan.<br>- What are the emotions you experience the most and when do you feel them?<br>- What is a challenge you went through recently and what have you learned about yourself because of it?<br>- What are you looking forward to?<br>- What are some goals you have for yourself and what are the steps you can make to achieve them?<br>- Describe a place where you feel happiest.<br>- What is a challenge you have right now and how does it make you feel?<br>- Reflect on your day. What is the best thing that has happened to you today?</p>
  </div>

  ![Journaling](../assets/img/journaling.png)

<script>
document.querySelectorAll(".collapsible").forEach(function(current) {

    let toggler = document.createElement("div");
    toggler.className = "toggler";
    current.appendChild(toggler);

    toggler.addEventListener("click", function(e) {
      current.classList.toggle("open");
    }, false);

  });
</script>

<style>

  .collapsible {
    position: relative;
    padding-bottom: 1em;
  }
  .collapsible:not(.open) > * {
    display: none;
  }
  .collapsible:not(.open) > p:first-child {
    display: block;
  }

  .collapsible > .toggler {
    position: absolute;
    left: 0;
    bottom: 0;
    display: block;
    width: 100%;
    background: #fff;
    text-align: center;
    cursor: pointer;
  }
  .collapsible > .toggler::after {
    content: "\25bc";
  }
  .collapsible.open > .toggler::after {
    content: "\25b2";
  }

</style>
