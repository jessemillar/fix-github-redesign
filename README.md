# Fix GitHub's Redesign

I hate GitHub's new design. There's no reason for it and it [makes my eyes tired](https://twitter.com/JahedDEV/status/1275532988772683776). This Userstyle attempts to fix some of the more glaring issues.

Modified from [this gist](https://gist.github.com/montanaflynn/ca64cc0fcf55bcd4556a016bffd8a7e3).

## Usage

1. Install the Stylish extension
    - [For Chrome](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe)
    - [For Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/)
1. Create a new style in the Stylish extension
1. Paste in the contents of [`userstyle.css`](userstyle.css)
1. Set the URL for the style to match the following regex:

    ```
    https:\/\/github\.com/(?!notifications)(.+)
    ```
