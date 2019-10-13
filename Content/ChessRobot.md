---
title: Chess Robot
layout: landing
description: 'A fully automated chess playing robot using the FRANKA Panda arm.'
image: assets/images/Chess/Title.png
nav-menu: true
tags: [Robotics, Machine Vision, ROS]
---


<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
    <div class="video-frame">
      <p align = "center">
        <iframe width="560" height="315" src="https://player.vimeo.com/video/291377091" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="" ></iframe>
      </p>
    </div>
  </div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Project Breakdown</h3>
				</header>
				<p>The aim of this project was to code a 7 degree of freedom robotic arm to play a fully automated game of chess. This was a team project in which I worked on the perception module. This involved sensing the locations of the chess pieces after each move in the game. OpenCv was used with a RBG-D Camera.</p>
        <p>Check out the <a href="https://github.com/nebbles/DE3-ROB1-CHESS">Github repository</a> and the <a href="https://de3-rob1-chess.readthedocs.io/en/latest/">documentation</a>.</p>
			</div>
		</div>
	</section>
</section>


<section id="three" class="spotlights">
	<section>
		<img src="assets/images/Chess/Chessboard.tiff" alt="" data-position="top center" />
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Find Chessboard Corners</h3>
				</header>
				<p>Fetch picture from the feed..</p>
			</div>
		</div>
	</section>
	<section>
		<img src="assets/images/Chess/Threshold.tiff" alt="" data-position="25% 25%" />
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Adaptive Thresholding</h3>
				</header>
				<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa sed magna lacinia magna pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis tempus.</p>
			</div>
		</div>
	</section>
  <section>
    <img src="assets/images/Chess/Mask.tiff" alt="" data-position="25% 25%" />
    <div class="content">
      <div class="inner">
        <header class="major">
          <h3>Masking</h3>
        </header>
        <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa sed magna lacinia magna pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis tempus.</p>
      </div>
    </div>
  </section>
  <section>
    <img src="assets/images/Chess/Canny.tiff" alt="" data-position="25% 25%" />
    <div class="content">
      <div class="inner">
        <header class="major">
          <h3>Canny Edge Detection</h3>
        </header>
        <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa sed magna lacinia magna pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis tempus.</p>
      </div>
    </div>
  </section>
  <section>
    <img src="assets/images/Chess/Hough.tiff" alt="" data-position="25% 25%" />
    <div class="content">
      <div class="inner">
        <header class="major">
          <h3>Hough Lines</h3>
        </header>
        <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa sed magna lacinia magna pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis tempus.</p>
      </div>
    </div>
  </section>
  <section>
    <img src="assets/images/Chess/Classified2.tiff" alt="" data-position="25% 25%" />
    <div class="content">
      <div class="inner">
        <header class="major">
          <h3>BWE Matrix</h3>
        </header>
        <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa sed magna lacinia magna pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis tempus.</p>
      </div>
    </div>
  </section>
</section>
