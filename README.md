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

**Key Features**

```
‣ probabilistic ban predictions from historical veto analysis of the opposing captain
‣ per-map win probability via ML classification
‣ post-veto opponent position heatmaps aggregated from parsed match replays
‣ player in-game-role classification derived from population-normalized stat profiles
‣ suite of real-time in-browser player and team performance analytics
```

**Architecture**

```
Extension: TS, React, Webpack
ML service: Python
Match replays processing pipeline: Go, Rust
Auth & Billing: AWS Lambda (TS), Redis, OAuth, JWT, Stripe
Web: Svelte (TS)
Infra: VPS, Docker, GH Actions CI/CD, Route53 geo-DNS (regional proxies for throttled ISPs)
```

<sub><a href="https://chrome.google.com/webstore/detail/faceit-mappio/kaeamgghipbhkjgibgglnmmnobdakapa">[chrome]</a></sub>&nbsp;&nbsp;&nbsp;<sub><a href="https://addons.mozilla.org/addon/faceit-mappio/">[firefox]</a></sub>&nbsp;&nbsp;&nbsp;<sub><a href="https://www.mappio.pro/">[web]</a></sub>

<hr>
