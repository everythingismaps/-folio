---
layout: post
title: melbourne tram map
date: 2017-10-20 11:30:00
description: a new map for the largest tram network in the world
comments: true
---
{% include map_header.html %}

<div class="img_row_map">
	<a href="{{ site.baseurl }}/img/maps/Melbourne_Tram_Route_Map_Schematic_v0.4_web.png"><img class="col three" src="{{ site.baseurl }}/img/maps/Melbourne_Tram_Route_Map_Schematic_v0.4_web.png"></a>
</div>

Earlier this year, Yarra Trams and Public Transport Victoria (PTV) <a href="https://www.ptv.vic.gov.au/news-and-events/news/new-train-network-map-for-victoria/" target="_blank">released a new map</a> for Melbourne's tram network. At the time, I was already working on this new version of my own.

This new map by PTV is a large improvement on the old one. Lines are more legible, the map is smaller and it uses standardised angles.

As a result of this release, I stopped working on my version. But recently I decided to finish this project anyway; if for no other reason, for the sake of not having folders full of unfinished maps on my hard drive.

<hr>
<br/>
### The Map

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/map_post_headers/2.png">
</div>

I should state from the outset that I am not claiming that my work is a huge improvement over the existing official map. As I stated earlier, I did most of the work on my map well before the new PTV map was released. However, I have taken advantage of this and incorporated some of the feedback from the official map's release into this new design. 

As always, it is worth restating that schematic maps are not intended to replicate actual geography. Rather, they are intended to make the network as simple and legible as possible. Most cities have adopted this approach to mapping their transport systems. You can read more on this topic in <a href="/2017/06/20/what-are-schematic-maps.html">this post</a>.

This map uses 90 and 45 degree angles to an 8pt grid. Like the previous official tram map, I have aligned the lines to a straight 90 degree angle rather than the 'tilt' characteristic of Melbourne's actual geography.

One advantage of this map is that it is readable at a smaller size than the PTV version. Other improvements are listed below.

#### Line groups and colours
The most obvious difference from the official map is line grouping and colours.

To make the network easier to understand, I decided to arrange lines into six groups:
<ul>
	<li>Swanston</li>
	<li>Elizabeth</li>
	<li>Collins</li>
	<li>Bourke</li>
	<li>La Trobe</li>
	<li>Flinders</li>
	<li>Suburban</li>
</ul>

| Group	        | Lines        | Notes |
| ------------- |:-------------:| ----------------|
| Swanston      | 1, 3, 3a, 5, 6, 16, 64, 67, 72 | All lines travel down Swanston Street/St Kilda Road. |
| Elizabeth   	| 19, 57, 58, 59      | All travel down Elizabeth Street except for the 58. |
| Collins		| 11, 12, 48, 109     |  Changed this group from 'East' to 'Collins' by moving the 30 into a new 'La Trobe' group with the City Circle (35). |
| Bourke	    | 86, 96      | All travel down Bourke Street. |
| La Trobe		| 30, 35		| New group created in v0.4
| Flinders	    | 70, 75      | All travel down Flinders Street. |
| Suburban      | 78, 82      | The only two lines that do not travel to the CBD. |

<br/>
<br/>
These are arbitrary groupings to a certain extent. However, I have tried to make them as logical and few in number as possible based on common routes and other similarities.

The main aim here is to make the lines easier to read. At the moment, line colours on the PTV map are randomly selected from a standard colour palette. There are some advantages to this approach. But to my mind it makes the map look more difficult to understand.

As for the colours that used in the map, each group has a base colour with various shades for each individual line. Some of them are a little light or dark (particularly lines 1 and 72) but with my approach this is not easily avoided.

#### Street names
One of the most common issues that I noticed people raise about the official map is the lack of major street names. As a result, these have been included in this map.

#### Interchanges
I adopted a rule of thumb for including interchang symbols. To avoid the map appearing too cluttered, interchange bubbles are only included in certain places:
<ol>
	<li>Three or more tram lines intersect</li>
	<li>At least one line branches off from another</li>
</ol>

<hr>
<br/>
### Future development

<br>
This map is not perfect and is still really in a sort of beta. For example, I tested out including railway stations on this map but it ended up being too cluttered and difficult to read. However, based on feedback from v0.3, I will look at including them in a future version to see how it turns out.

If you have any feedback or suggestions for improvement, please let me know.

UPDATE (2017-11-03): based on <a href="https://www.reddit.com/r/melbourne/comments/78419q/a_new_map_of_melbournes_tram_network_feedback/">feedback from Reddit</a>, I have made some changes and corrections to the map. Large-scale changes like adding landmarks and railway stations will need to come in a future release. This is due to the significant redesign and realignment that will need to take place.