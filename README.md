# Promo Hangover

A discount borrows from the weeks after it. Enter your normal weekly sales, price, cost, the discount, how the promo weeks went and how the weeks after it went, and see the net profit once the dip is counted, not just the promo window.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Verdict:** `pays`, `the dip eats it` or `loses money`.
- **Shows:** net profit change, the promo-window result, the cost of the dip, the share of the promo's extra units that came back out of the dip, the uplift needed to break even, and the discount given to people who would have bought anyway.
- **Tables:** net profit at dip depths from 0 to 40%, and the uplift each discount from 10% to 40% needs, with and without your dip.
- **Arithmetic:** margin now m = price - cost, margin on promo mp = price x (1 - discount) - cost. Uplift needed to break even in the promo is m / mp - 1, which does not depend on volume. The full formulas are on the page.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

It uses a typical dip nowhere: you enter the one you measured. It assumes price returns to regular afterwards, and it counts one promotion's profit, not customers kept, a price people learn to wait for, or a competitor's response. Seasonality and other marketing in the same weeks move units, so compare against a control or the same weeks last year if you can.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
