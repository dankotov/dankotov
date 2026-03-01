# 🕹️ Dan Kotov

**`Software Engineer`**
**`BSc: Computer Science @ Toronto Metropolitan (Ryerson) University`**

<div id="user-content-toc">
  <ul>
    <summary><h2 style="display: inline-block;">PROJECTS</h2></summary>
  </ul>
</div>

<img src="/media/mappio/icon.svg" width="40" height="40" align="left" alt="FACEIT mappio logo"><h3 align="left" style="float: left;">Mappio<img valign="middle" src="https://img.shields.io/chrome-web-store/rating/kaeamgghipbhkjgibgglnmmnobdakapa" align="right"><img valign="middle" src="https://img.shields.io/chrome-web-store/users/kaeamgghipbhkjgibgglnmmnobdakapa" align="right"></h3>

######

> Browser extension for the FACEIT CS2 competitive platform that turns opponent data into a tactical advantage - combining real-time stats, behavioral predictions, and ML-powered analytics to help players make smarter decisions in every match.

<h4>Key Features</h4>
<ul>
<li>probabilistic ban predictions from historical veto analysis of the opposing captain</li>
<li>per-map win probability via ML classification</li>
<li>post-veto opponent position heatmaps aggregated from parsed match replays</li>
<li>player in-game-role classification derived from population-normalized stat profiles</li>
<li>suite of real-time in-browser player and team performance analytics</li>
</ul>

<h4>Architecture</h4>
<ul>
<li>**Extension**: TS, React, Webpack</li>
<li>**Web**: Svelte</li>
<li>**Match replays processing pipeline**: Go, Rust</li>
<li>**ML service**: Python</li>
<li>**Auth & Billing**: AWS Lambda (TS), OAuth, JWT, Stripe</li>
<li>**Infra**: self-host VM, Docker, GitHub Actions CI/CD, Route 53 geo-based DNS with regional proxies for throttled regions</li>
</ul>

<p>
  <img src="/media/technologies/chrome-extension.svg" width="30" height="30" align="right" alt="Chrome extension logo">
  <img src="/media/technologies/webpack.svg" width="30" height="30" align="right" alt="Webpack logo">
  <img src="/media/technologies/typescript.svg" width="30" height="30" align="right" alt="Typescript logo">
  <img src="/media/technologies/react.svg" width="30" height="30" align="right" alt="React logo">
</p>
<sub><a href="https://github.com/dankotov/faceit-mappio">[repo]</a></sub>&nbsp;&nbsp;&nbsp;<sub><a href="https://chrome.google.com/webstore/detail/faceit-mappio/kaeamgghipbhkjgibgglnmmnobdakapa">[chrome]</a></sub>&nbsp;&nbsp;&nbsp;<sub><a href="https://addons.mozilla.org/addon/faceit-mappio/">[firefox]</a></sub>&nbsp;&nbsp;&nbsp;<sub><a href="https://www.reddit.com/r/FACEITmappio/">[reddit]</a></sub>

<hr>
