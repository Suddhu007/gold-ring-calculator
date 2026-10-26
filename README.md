# Gold Ring Price Calculator

A free, responsive gold jewellery price estimator built with plain HTML, CSS, and JavaScript. No installation, server, or external libraries required.

## Features

- Gold purities: 14KT, 18KT, 20KT, 22KT, and 24KT
- 24KT market rate input (per 10 grams)
- Ring weight and making-charge inputs
- Optional 3% GST calculation
- Gold price, making charges, subtotal, tax, and effective per-gram breakdown
- Responsive on phones, tablets, and desktop
- Works locally and can be hosted on GitHub Pages

## Run locally

Open `index.html` in any modern browser.

## Publish using GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then click **Save**.
4. GitHub Pages will publish the `index.html` file. The site URL should be `https://suddhu007.github.io/gold-ring-calculator/`.

For official instructions, see the [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart).

## Calculation

Gold value = 24KT rate × (selected karat ÷ 24) × (weight in grams ÷ 10)

Making charges = gold value × making-charge percentage

GST, when selected, is calculated at 3% of the subtotal. These estimates exclude stones, wastage, discounts, and jeweller-specific adjustments; verify the final quote and applicable tax with the jeweller.

## License

MIT
