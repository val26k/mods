<table>
  <thead>
    <tr>
      <th align="left">Version</th>
      <th align="left">Changelog Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><strong>1.5.2</strong></td>
      <td>
       - Added a new <code>Theme</code> configuration option to quickly switch between 5 distinct color palettes (Valheim, Blood, Ocean, Nature, and Monochrome).<br>
       - Refactor the `README` and `CHANGELOG`
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.5.1</strong></td>
      <td>
       - Fixed a bug where <code>Weather text</code> is clipping outside the panel.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.5.0</strong></td>
      <td>
        <img src="https://i.imgur.com/CcZcHx2.png" alt="Time Slider Preview" width="300"><br>
        - Added a visual <code>Time Slider</code> progress bar at the bottom of the clock to track the day/night cycle.<br>
        - Added a dynamic sliding sun (☀) and moon (🌙) icon handle that swaps at nightfall.<br>
        - Added smooth cross-fade color transitions for the progress bar as the time of day changes.<br>
        - Upgraded the UI with smooth rounded edges and larger circular corner rivets using sprites.<br>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.4.0</strong></td>
      <td>
        - Added a configuration toggle <code>Show Weather</code> to dynamically display the current weather and environment alongside the time.<br>
        - Added a configuration toggle <code>Weather Font Size</code> to allow independent scaling of the weather text.<br>
        - Added dynamic translation of internal Valheim weather states and boss events into immersive, player-friendly names.<br>
      </td>
    </tr>
     <tr>
      <td valign="top"><strong>1.3.1</strong></td>
      <td>
        - Completely rewrote how the mod talks to RandyKnapp's <code>Minimal Status Effects</code> (like when using AM/PM or Stacked mode).<br>
        - Fixed a bug where moving the clock far to the left or right still pushed your status effects down on the right side of the screen.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.3.0</strong></td>
      <td>
        - Added a configuration toggle (<code>Use12HourFormat</code>) to switch between 24-hour time and a 12-hour AM/PM format.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.2.2</strong></td>
      <td>
        - Fixed <code>CHANGELOG</code> formatting.<br>
        - Added <code>website_url</code> in <code>manifest.json</code>.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.2.1</strong></td>
      <td>
        - Implemented a high-performance memory cache for the <code>UI loop</code>.<br>
        - Text string formatting is now strictly restricted to run only when the in-game minute shifts, reducing <code>CPU</code> and <code>Garbage Collector</code> overhead to near zero.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.1.1</strong></td>
      <td>
        - Added <code>CHANGELOG</code>.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.1.0</strong></td>
      <td>
        - Added full, automatic UI compatibility for RandyKnapp's <code>Minimal Status Effects</code>.<br>
        - Refactored internal code structure for improved maintainability.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>1.0.0</strong></td>
      <td>
        - Initial Release.
      </td>
    </tr>
  </tbody>
</table>