# Embed a free Calcupia calculator

[Calcupia](https://calcupia.com/) has more than 200 free calculators (math, finance, science, unit conversion, construction and more). Each one shows its formula and a worked example, and any of them can be added to your own page with one copy and paste.

- Free, no sign-up, no API key
- Nothing to install: it is a standard `<iframe>`
- The numbers your visitors type are calculated in their browser

## Quick start

1. Open the calculator you want on [calcupia.com](https://calcupia.com/).
2. Scroll to **Embed this calculator** and click **Copy code**.
3. Paste the code into your page (see the platform notes below).

The code looks like this:

```html
<iframe src="https://calcupia.com/math/percentage-calculator/?embed=1"
        title="Percentage Increase Calculator | Calcupia"
        width="100%" height="680"
        style="border:0;border-radius:12px" loading="lazy"></iframe>
<p style="font:13px/1.4 sans-serif;margin:6px 0 0;color:#5b667a">
  <a href="https://calcupia.com/math/percentage-calculator/" rel="nofollow">Percentage Increase Calculator</a>
  by <a href="https://calcupia.com/">Calcupia</a>
</p>
```

To embed a different calculator, replace the address in `src` with the calculator's address and keep `?embed=1` at the end. That parameter shows the compact version, without the site menu.

The [widgets page](https://calcupia.com/widgets/) lists the calculators and gives you the code for each one.

## Where to paste it

| Platform | How |
|---|---|
| **WordPress** | Add a **Custom HTML** block and paste the code. |
| **Google Sites** | **Insert → Embed → Embed code**, paste, then resize the box. |
| **Canvas** | In the page editor, open the **HTML editor** (`</>`) and paste. |
| **Moodle** | Add a **Page** or **Label**, switch the editor to HTML (`</>`) and paste. |
| **Blogger** | Switch the post to **HTML view** and paste. |
| **Plain HTML** | Paste the code where the calculator should appear. |

Some platforms only allow iframes from approved sites. If the calculator does not show, ask your site administrator to allow `calcupia.com`.

## Adjusting the size

- **Width**: `width="100%"` fills the column. Use a fixed value such as `width="480"` for a narrow sidebar.
- **Height**: `680` fits most calculators. Increase it (for example `height="900"`) if a calculator with a schedule or chart is cut off.

## Examples

[EXAMPLES.md](EXAMPLES.md) has ready-to-use codes for a few popular calculators: speed, distance and time; percentage increase; discount; concrete volume; and compound interest.

## Questions

Found a problem or want a calculator that does not exist yet? Use the contact page on [calcupia.com](https://calcupia.com/contact/).

The text and examples in this repository are under the [MIT License](LICENSE). The calculators themselves stay hosted on calcupia.com.
