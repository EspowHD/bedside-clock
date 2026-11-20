# Development

No build step: edit `dist/bedside-clock-strategy.js`. Run `python -m http.server` in this folder and open
`test/test.html` (generator tests) and `test/wizard.html` (setup wizard tests); each prints PASS or FAIL per test.

Home Assistant caches `/local/` resources for 31 days. While developing, bump a `?v=N` suffix on the resource URL
after each change. The Marketplace does this for you on release.
