<h1>Valheim Clock</h1>

<p>A lightweight, server-synchronized, highly customizable HUD clock for Valheim.</p>
<p>Valheim Clock adds a permanent, vanilla-friendly time display directly beneath your minimap. Unlike client-based clocks, this mod hooks directly into the server's authoritative <code>ZNet</code> time, ensuring that every player sees the exact same time, synchronized down to the minute.</p>

<h2>✨ Features</h2>
<ul>
  <li><strong>Vanilla-Friendly UI:</strong> Designed to seamlessly blend into Valheim's aesthetic with a dark semi-transparent background, crisp gold trims, and metallic corner rivets.</li>
  <li><strong>Highly Configurable:</strong> Move it, resize it, or change the font size to fit your exact screen resolution and personal taste.</li>
  <li><strong>Dynamic Layouts:</strong> Choose between a standard "Single Line" display or a compact "Stacked" layout.</li>
  <li><strong>Instant Hot-Reloading:</strong> Adjust your configuration file while playing! The UI will instantly snap to your new settings without needing to restart the game or log out of your server.</li>
  <li><strong>Client-Side:</strong> Only players who want to see the clock need to install it.</li>
</ul>

<h2>🎨 Themes</h2>
<p align="center">
  <img src="https://i.imgur.com/i2MSWKK.jpg" alt="Valheim Clock Preview" width="400">
</p>

<h2>⚙️ Configuration Options</h2>
<p>Upon launching the game for the first time, a configuration file will be generated at <code>BepInEx/config/com.orfox.valheimclock.cfg</code>.</p>

<p><strong>General</strong></p>
<ul>
  <li><strong>12 Hour Format</strong> displays the clock in a 12-hour format with AM/PM instead of 24-hour format time.</li>
  <li><strong>Weather</strong> displays the current weather/environment alongside the time.</li>
  <li><strong>Progress bar</strong> displays a progress bar at the bottom tracking the day/night cycle.</li>
</ul>

<p><strong>Position</strong></p>
<ul>
  <li><strong>Offset X:</strong> Move the clock horizontally (Default: 0)</li>
  <li><strong>Offset Y:</strong> Move the clock vertically (Default: -10)</li>
</ul>

<p><strong>Visuals</strong></p>
<ul>
  <li><strong>Panel Width:</strong> Width of the clock background (Default: 160)</li>
  <li><strong>Panel Height:</strong> Height of the clock background (Default: 34)</li>
  <li><strong>Font Size:</strong> Adjust the text size (Default: 18)</li>
  <li><strong>Text Layout:</strong> Choose between <code>SingleLine</code> (Day 32  14:45) or <code>Stacked</code> (Day on top, Time on bottom).</li>
  <li><strong>Weather Font Size:</strong> Adjust the Weather text size (Default: 14)</li>
  <li><strong>Themes:</strong> Choose between <code>Valheim, Blood, Ocean, Nature, Monochrome</code></li>
</ul>

<p><em>Note: Because this mod supports hot-reloading, you can edit these values in a text editor while standing in-game and hit Save to watch the UI update instantly!</em></p>

<h2>📥 Installation</h2>

<p><strong>Recommended (Mod Manager):</strong></p>
<ol>
  <li>Download and install <a href="https://valheim.thunderstore.io/package/ebkr/r2modman/">r2modman</a> or Thunderstore Mod Manager.</li>
  <li>Click "Install with Mod Manager" on this page.</li>
</ol>

<p><strong>Manual Installation:</strong></p>
<ol>
  <li>Ensure you have <a href="https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/">BepInEx</a> installed.</li>
  <li>Download the <code>.zip</code> file from this page and extract it.</li>
  <li>Move <code>ValheimClock.dll</code> into your <code>BepInEx/plugins</code> folder.</li>
  <li>Launch the game.</li>
</ol>
