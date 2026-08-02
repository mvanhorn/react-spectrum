Evidence for adobe/react-spectrum#10293.

- nested-tabs-recording.gif - React Aria Components "Nested tabs size transition"
  story, transition slowed 300ms -> 6s so it can be sampled. Green HUD: this
  branch. Red HUD: control with the reset stripped off the nested TabPanels.
- nested-tabs-comparison.png - both states with the outer --tab-panel-height
  pinned to the same 256px, so the only variable is the nested panel.

Captured in headless-driven Chrome on macOS. Page content only.
