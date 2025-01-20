# CSS Filters

This project is a simple webpage that demonstrates the use of CSS filters, specifically the `hue-rotate()` function combined with `drop-shadow()`. The page applies various hue-rotation effects to an example image, visually showcasing how the `filter` property can manipulate colors.

---

## Features

- **Original Image**: Displays the unfiltered version of the image as a reference.
- **Filtered Images**: Applies the `hue-rotate()` filter at specific angles (45°, 90°, 180°, 270°, 315°, and 360°) to demonstrate how the filter alters the image's colors.
- **Drop Shadow**: Each filtered image includes a drop-shadow effect to make the image stand out.

---

## Code Details

The CSS `filter` property is applied as follows:

```css
filter: hue-rotate([n]deg) drop-shadow(
    0.25rem 0.5625rem 0.25rem rgba(0, 0, 0, 0.5)
  );
```

Where `[n]` is the rotation angle in degrees.

The angles used are:

- `45°`: Olive tone
- `90°`: Green tone
- `180°`: Blue tone
- `270°`: Violet tone
- `315°`: Red tone
- `360°`: Brick tone

---

## Caveats

It's important to note that downloading or dragging a filtered image from the webpage to your desktop will only save the original, unfiltered version of the image. This is because the CSS `filter` property only applies visual effects in the browser and does not alter the actual image file. To preserve the filtered appearance, you would need to use a screenshot tool or apply the desired filter in an image editing application.

---

## Testing and Compatibility

The application has been tested on the following platforms and browsers:

- **Operating System**: Windows 10
- **Browsers**:
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge

### Device View Testing

The layout and functionality have been verified in both browser and device simulation views to ensure responsiveness and usability.
