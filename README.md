## Hi there 👋

<!--
**wei0210-hc/wei0210-hc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

name: Licenses and permissions
with:
  filename: metrics.plugin.licenses.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  template: repository
  repo: metrics
  plugin_licenses: yes
  plugin_licenses_setup: bash -c '[[ -f package.json ]] && npm ci || true'

