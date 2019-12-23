---
title: Whatever The Weather
layout: landing
description: 'A Spotify playlist generator based on the weather in your current location.'
image: assets/images/Spotify/Title-01.png
nav-menu: true
tags: ['Raspberry Pi', 'CSS', 'HTML', 'JavaScript', 'Python', 'API']
show_tile: false
---
<!-- Main -->


<section id="one">
	<div class="inner">
    <header class="major">
			<h3>Idea</h3>
    </header>
			<p>
				Music is such an important and beautiful part of everyday life. This project looks into using the weather and audio features to create more adaptive music recommendations based off of the weather outside your window.
 			</p>
    	<p>Check out the <a href="https://github.com/leahpattison/Sensing-IOT">Github repository</a> which includes the source code for the data collection, analysis and app deployment.</p>

			<header class="major">
				<h3>Track</h3>
	    </header>
				<p>
				 For two weeks data was collected using the Spotify API and Dark Sky weather API on the music I listen to and the weather in London. A Raspbery Pi was used to call retrieve the data and then store it on a Google Sheet using the Sheets API.
	 			</p>

			<header class="major">
				<h3>Learn</h3>
	    </header>
				<p>
				 A regression model was created to map the weather in London to the audio features of Spotify tracks. The data was split into 3:1 to train and test the model, with an achieved R squared of 0.5. The reliance of this model could be improved by collecting data over a longer period of time with a larger range of weather patterns.
	 			</p>
			<header class="major">
				<h3>Recommend</h3>
			</header>
				<p>
				 An online portal was created where users can request a playlist recommendation based on their current location. This playlist can then be added to their account.
				</p>
				<div class="images" align="middle">
					<img src="{{site.baseurl}}/assets/images/Spotify/animation.gif" alt=""  width="80%"/>
				</div>

				<header class="major">
					<h3>WIP</h3>
				</header>
				<p>This project is currently a Work In Progress. I am currently changing the authorization pathway to allow multiple users to use the app. The app will then be launched online. </p>


	</div>
</section>
