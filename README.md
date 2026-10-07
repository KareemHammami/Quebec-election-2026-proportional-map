# Quebec 2026 election under different electoral systems

An interactive, bilingual (FR/EN) map of the 2026 Quebec general election. It shows the actual result and
recomputes it under other systems (pure proportional, mixed-member proportional, and a "riding-share"
proposal with six variants), and lets you add your own system by describing it to an LLM and pasting
the JSON answer back.

- **Runs entirely in your browser.** The whole app is the single file `index.html`. It makes no network
  requests (a Content-Security-Policy blocks them), has no analytics, and never runs pasted code.
  You can download `index.html` and open it offline.
- **Data:** 2026 Quebec general election results and electoral district boundaries, Élections Québec.
  This is an illustrative simulation, not affiliated with Élections Québec or the National Assembly;
  results under alternative systems are not official results.
- **Author:** Kareem Hammami, khammamigis@gmail.com
