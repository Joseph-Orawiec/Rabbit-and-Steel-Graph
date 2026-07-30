# Rabbit and Steel Graph
Importantly, this was made before the free [Extra Mode](https://store.steampowered.com/news/app/2132850/view/503975183931932790) update so 10 of the 35 item sets are not included combined with the fact that many items got reworks during this update.

Made on 2025/3/8

## About
A friend of mine asked me about how they should be thinking about the [items](https://rns.miraheze.org/wiki/Loot) in [Rabbit and Steel](https://store.steampowered.com/app/2132850/Rabbit_and_Steel) and how to pick/what item archetypes to focus on.

In my opinion, I explained how there do exists some major item themes but for the most part it doesn't really matter if they all synergize really strongly since, often times out of 6 items, only a few will synergize which is ok.

However, I was curious about what Items I would classify as synergizing and wanted to visualize how many items of Rabbit and Steel synergized with each other.

## Process

Manually scraped data from the [loot page](https://rabbitandsteel.fandom.com/wiki/Loot) at the time and downloaded all the sprites.

Manually evaluated each item pair and decided if they synergized, therefore creating an edge.

Used pyvis to visualize the graph

## Viewing
Download the [Rabbit and Steel Graph zip file](https://github.com/Joseph-Orawiec/Rabbit-and-Steel-Graph/blob/main/Rabbit%20and%20Steel%20Graph.zip), extract and open the HTML file. <br>
Then when it loads, scroll down and set the solver to "forceAtlas2Based" and setting physics enabled to false will stop it from slowly spinning.<br>
Also, hovering over items will then pull up their effect!