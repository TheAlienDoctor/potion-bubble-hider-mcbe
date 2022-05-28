# Potion bubble hider for Minecraft Bedrock
## Download
You can download this on my website https://TheAlienDoctor.com
## How does it work?
<p>This potion bubble hider works differently from other packs that also hide the potion bubbles.</p>
<p>Most packs modify the particles.png texture file. In my experience this method of hiding particles works...sometimes.</p>
<p>When I tried using this method (and I even eventually tried other packs to see if I had done something wrong), I would get very inconsisten results. For example sometimes it would work on singleplayer but not on a multiplayer server. I even tried using it without any other resource packs so there would be no conflicts but it would still not work. Other times it just didn't work on singleplayer or multiplayer.</p>
<b>So what makes my pack different?</b>
<p>My pack modifys the mobspell.json file in the vanilla resource pack. This is .json file that controls potion particles. I made one simple modification, which was to set '"num_particles": 1' to 0.</p>
<p>So my pack actually doesn't just "hide" the particles like others that change the particles.png file, it actually completly removes them from actually existing (on your client anyway, other people would still be able to see them unless they are using this pack as well)</p>
