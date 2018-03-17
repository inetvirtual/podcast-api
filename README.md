# Podcast API
Podcast Web API
The Podcast Web api is a web audio player specially crafted for listening to podcasts.
Experimented by using in our <a href="https://besttheme.com/podcast-wordpress-theme/">project</a> for the podcast audio section. The player is extensible and ships with many default extensions. The player is completely themeable, and can change the markup, which comes with a responsive default theme.
<ul>
<li><a href="https://github.com/inetvirtual/podcast-api#extensions">Extensions</a>
<li><a href="https://github.com/inetvirtual/podcast-api#usage">Usage</a>
<li><a href="https://github.com/inetvirtual/podcast-api#contribute">Contribute</a>
</ul>
<h2><a href="#extensions"></a>Extension</h2>
<ul>
<li>Sharing - This holds sharing options for different social networks, direct link sharing and the embed code.</li>
<li>Chaptermarks - If the podcaster supplies chaptermarks for an episode listeners can will see where in the episode they currently are and jump to a chaptermark with a click or tap.</li>
<li>Episode Info - Displays the episode title and description for the episode.</li>
<li>Playlist - Displays a list of podcast episodes based on as standard podcast RSS feed.</li>
<li>Transcript - Displays the transcript of an episode, highlights the currently spoken words and allows the listener to search and jump to certain passages by clicking or tapping.</li>
<li><a href="https://www.google.co.in/chromecast/setup/">Chromecast</a> (experimental) - Allows the listener to play the podcast episode on a Chromecast device. This is currently not enabled by default, because it's still in testing and requires a little polishing work.</li>
</ul>
<h2><a href="#usage"></a>Usage</h2>
By default the player is integrated into the page using a <script> HTML tag. This is necessary to render the player in an iframe to ensure it does not interfere with the enclosing page's CSS and JS while still being able to resize the player interface dynamically.

<code>data-configuration</code> should be set to the JS variable name you saved the configuration to.
<pre>
window.playerConfiguration = {
  "episode": {
    "media": {"mp3": "https://example.com/episode-1.mp3"},
    "title": "Transcript Test"
  }
}
<script class="podcast-player" src="https://your-website.com/podcast-player/javascripts/podcast-player.js" data-configuration="playerConfiguration"></script>
</pre>
<h2><a href="#contribute"></a>Contribute</h2>
If you would like to propose new features or have found a bug, please use <a href="https://github.com/inetvirtual/podcast-api/issues">Github issues</a> to tell us.
