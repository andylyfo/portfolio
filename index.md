### PROJECTS

<br><br>
Here is a recent selection of data and developer projects, as well as a short summary of my Master's thesis in climate modelling.
<br><br>

[MScR - Global Environtmental Challenges, University of Bristol](/pdf/bridge_retreat_slides_AL.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>
<br><br>

---
[F1 2022 - Ferrari Driver Analysis](https://substack.com/home/post/p-132087612)
<img src="images/dummy_thumbnail.jpg?raw=true"/>
<br><br>

---
#### James Ward-Prowse: All Free Kicks Analysed
<img src="images/JWP_FKS.jpg?raw=true"/>
<br><br>
A short project to brighten my mood as a fan of (at the time) struggling Southampton. James Ward-Prowse seems destined to break the premier league free kick record so I wanted to see if I could analyse them from a data perspective to gain insight on his best location and angle. To find his 'territory', as it were. First this involved using some tutorials to write a __web scraping API__ to pull all the shot data for every attempt (including open play) from [Understat](https://understat.com/player/843). The next step was cleaning and stripping the data down to just his free kick attempts and the essentials. Then it was a simple case of plotting the data with __Python__ and it's packages. The findings were enlightening. Grey spots represent attempts that missed the goal. Yellow represents shots that were on target but blocked/saved of marginally off-target hitting the posts. Green spots are goals. The size of each dot relates to the xG of the shot as it was taken. Across 100+ attempts from all areas outside the box, Ward-Prowse scored 17. Most of which came from a remarkably tight area a few yards outside the box and to the left hand side, aiding his technique combining leftward-swing and dip. Remarkably, the total attempts accumulate to 7.31xG (expected goals, a measure of how likely a shot becomes a goal). He outperformed this by nearly 10 goals. 16 of 17 goals used this technique. The only free kick he has scored I've deduced from video analysis that doesn't use this technique is his goal in the 3-1 defeat to Wolves in January 2022. For this goal he basically just channels deep rage and hits a powerful knuckleball from just over 35 yards (xG=0.04!). In laymans terms, [he really c*nted it](https://www.youtube.com/watch?v=eQdEplTv0_0).

---
[Browser Boids](https://andylyfo.github.io/boids/)
<img src="images/murmuration.jpg?raw=true"/>
<br><br>
I've always been enamoured by the migratory activity of starlings (who isn't?) known as murmurations, so I set out to make my own version that I can view from my desktop rather than a 4 hour journey down to Brighton beach. Upon the pleasing discovery that this was a well trodden corner of computer science (in particular game design), I built my own simulation with __JavaScipt/HTML/CSS__ to work in a browser window. Sit back and relax. This was adapted from Ben Eater's work, the repo is [here](https://github.com/andylyfo/boids).
<br><br>

---

### WRITING

I try to keep my pen sharp by publishing a food-related journal called TRIPE on substack. TRIPE being a synonym for nonsense, naturally.

- [Fooling around with the worlds most expensive spice by weight](https://open.substack.com/pub/tripeblog/p/on-paella-saffron-and-the-pulp-fiction?r=lg3sj&utm_campaign=post&utm_medium=web)
- [Here's a few books I've enjoyed recently](https://open.substack.com/pub/tripeblog/p/heres-a-few-books-i-enjoyed-recently?r=lg3sj&utm_campaign=post&utm_medium=web)
- [On Keith Floyd](https://open.substack.com/pub/tripeblog/p/on-floyd-on?r=lg3sj&utm_campaign=post&utm_medium=web)

---

### CONTACT

<div class="container">
  <form action="action_page.php">

    <label for="fname">Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">

  </form>
</div>