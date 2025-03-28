# KAPLAY Kolors 🦖🎨

Use the colors used on the [KAPLAY](https://kaplayjs.com/) website.

## Installation 📦

You can install Kaplay Kolors via npm:

```bash
npm install kaplay-colors
```

## Kolors 🎨

The possible kolors are:

| Kolor    | Description                                                               |
| -------- | ------------------------------------------------------------------------- |
| `BLACK`  | The black color used for navbar and main sections                         |
| `GREEN`  | The green color used for buttons                                          |
| `ORANGE` | The orange color used for some header texts and as background in examples |
| `PURPLE` | The purple color used for some header texts, links etc.                   |
| `YELLOW` | The yellow color used for some header texts and as button outline         |
| `WHITE`  | The white color used for some header texts                                |

## Usage 🧑‍🎨

This package just exports and object with the above mentioned kolors.

Hence, it can be used like this:

```javascript
import kaplay from "kaplay";
import "kaplay/global";

import { Kolor } from "kaplay-colors";

kaplay();

add([rect(200, 100), color(Kolor.PURPLE)]);
```

## License 🪪

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact 📇

Have questions or suggestions? Reach out via:

- GitHub Issues
