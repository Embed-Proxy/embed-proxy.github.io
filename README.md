<h1>Embed Proxy</h1>
<p>A single-file, privacy-first embed proxy that turns any YouTube link (or other embeddable URL) into a tracking-free iframe.</p>

<p><strong>Live demo:</strong> <a href="https://embed-proxy.github.io" target="_blank">https://embed-proxy.github.io</a></p>

<p>Just append any YouTube (or other) URL after the slash:</p>
<pre>
https://embed-proxy.github.io/youtu.be/dQw4w9WgXcQ
https://embed-proxy.github.io/youtube.com/watch?v=abc123&t=90&list=PLxyz
https://embed-proxy.github.io/youtube.com/shorts/Xyz123
</pre>

<h2>Features</h2>
<ul>
  <li>Converts every YouTube link to <code>youtube-nocookie.com</code> (zero Google tracking)</li>
  <li>Full support for <code>youtu.be</code>, <code>watch?v=</code>, Shorts, playlists, multiple videos, <code>t=</code> start time, etc.</li>
  <li>Always forces <code>autoplay=1</code></li>
  <li>Falls back to direct embedding for Twitch, Vimeo, SoundCloud, etc.</li>
  <li>Single static HTML file, &lt; 5 KB, zero dependencies, no cookies</li>
  <li>Works perfectly as a custom 404 page — every invalid path becomes a functional embed proxy.</li>
</ul>

<h2>How to self-host (30 seconds)</h2>
<ol>
  <li>Fork this repo (or click "Use this template")</li>
  <li>Settings → Pages → enable GitHub Pages, then chose GitHub Actions as source under Build and deployment</li>
  <li>Now you can make any edits needed to index.html and the Github Action above copies it to 404.html at each commit</li>
  <li>Your proxy is instantly live at <code>https://yourusername.github.io/repo-name</code></li>
  <li>If you want to remove <code>/repo-name</code> from the URL, just name your repo <code>yourusername.github.io</code></li>
</ol>

<h2>Usage examples</h2>
<pre>
https://yourusername.github.io/youtube.com/watch?v=abc123&list=PLxyz
https://yourusername.github.io/youtube.com/shorts/xyz789
</pre>

<p>No tracking. No bloat. Just works.</p>
</body>
</html>
