# Border Avatar phpBB Extension
This extension adds a rounded border of the same colour as the user's name to their avatar.

![phpBB 3.3.x Compatible](https://img.shields.io/badge/phpBB-3.3.x%20Compatible%20-blue.svg) ![phpBB 3.2.x Compatible](https://img.shields.io/badge/phpBB-3.2.x%20Compatible%20-blue.svg)

## Install
1. Download the latest release.
2. Unzip the downloaded release, and change the name of the folder to `borderavatar`.
3. In the `ext` directory of your phpBB board, create a new directory named `cabot` (if it does not already exist).
4. Copy the `borderavatar` folder to `/ext/cabot/`.
5. Navigate in the ACP to `Customise -> Manage extensions`.
6. Look for `Border Avatar` under the Disabled Extensions list, and click its `Enable` link.

## Uninstall
1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Border Avatar` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/cabot/borderavatar` folder.

## Style customisation
1. To customise the default border colour according to the style, make a copy of the `cabot/borderavatar/styles/custom_style` directory and rename it with the folder name of the style concerned.
2. Open the file `cabot/borderavatar/styles/your_dir/template/ba_custom_colour.html` and change the colour in this line: `--ba-group-colour: #105289;`.
3. You can have as many directories as you have styles if you want to assign a default border colour to each of them.

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2023 - cabot
