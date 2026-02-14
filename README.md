# 📊 My GitHub Metrics

Generate beautiful, embeddable metrics for your GitHub profile README!  
Supports users, organizations, and repositories — fully customizable with plugins.

<table>
  <tr>
    <th align="center">User Profile Example</th>
  </tr>
  <tr>
    <td align="center">
      <img alt="Example Metrics" width="600" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.svg">
      <br>
      <small>(Your metrics will appear here once generated via workflow)</small>
    </td>
  </tr>
  <tr>
    <th align="center">
      <h3>🧩 Customizable with 40+ plugins and hundreds of options!</h3>
    </th>
  </tr>
  <tr>
    <th><a href="#isocalendar">📅 Isometric commit calendar</a></th>
    <th><a href="#languages">🈷️ Languages activity</a></th>
  </tr>
  <tr>
    <td align="center">
      <details open><summary>Full year calendar</summary>
        <img alt="Isocalendar Full Year" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.isocalendar.full.svg">
      </details>
      <details><summary>Half year calendar</summary>
        <img alt="Isocalendar Half Year" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.isocalendar.svg">
      </details>
    </td>
    <td align="center">
      <details open><summary>In-depth analysis</summary>
        <img alt="Languages Indepth" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.languages.indepth.svg">
      </details>
      <details><summary>Recent activity</summary>
        <img alt="Languages Recent" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.languages.recent.svg">
      </details>
    </td>
  </tr>
  <tr>
    <th><a href="#stargazers">✨ Stargazers</a></th>
    <th><a href="#lines">👨‍💻 Lines of code changed</a></th>
  </tr>
  <tr>
    <td align="center">
      <details open><summary>Worldmap</summary>
        <img alt="Stargazers Worldmap" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.stargazers.worldmap.svg">
      </details>
      <details><summary>Classic charts</summary>
        <img alt="Stargazers Chart" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.stargazers.svg">
      </details>
    </td>
    <td align="center">
      <details open><summary>History & diff</summary>
        <img alt="Lines History" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.lines.history.svg">
      </details>
    </td>
  </tr>
  <tr>
    <th><a href="#habits">💡 Coding habits and activity</a></th>
    <th><a href="#achievements">🏆 Achievements</a></th>
  </tr>
  <tr>
    <td align="center">
      <details open><summary>Charts</summary>
        <img alt="Habits Charts" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.habits.charts.svg">
      </details>
      <details><summary>Facts</summary>
        <img alt="Habits Facts" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.habits.facts.svg">
      </details>
    </td>
    <td align="center">
      <details open><summary>Compact</summary>
        <img alt="Achievements Compact" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.achievements.compact.svg">
      </details>
      <details><summary>Detailed</summary>
        <img alt="Achievements Detailed" width="400" src="https://github.com/KozmikLojik/KozmikLojik/raw/main/metrics.achievements.svg">
      </details>
    </td>
  </tr>
  <!-- Add more plugin sections if you generate them via workflow -->
</table>

## Quick Setup for Your Profile (GitHub Actions – Recommended)

1. Create a repo named exactly `KozmikLojik` (this one!)
2. Add `.github/workflows/metrics.yml` with your config (see earlier messages for code)
3. Create PAT token → add as repo secret `METRICS_TOKEN`
4. Run workflow → SVGs commit automatically
5. Embed in README as above (raw links)

## Live Preview (while workflow runs)

```markdown
![My Metrics Live](https://metrics.lecoq.io/KozmikLojik?template=classic&config.timezone=Asia/Calcutta&isocalendar=1&languages=1&habits=1&achievements=1&commit_time=1&theme=tokyonight)
