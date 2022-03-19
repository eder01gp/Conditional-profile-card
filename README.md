# Main objetive
To create a conditional profile card based on the information entered into the screen by the web user.

# Main structure
The project consist of html and javascript code.
The html code contains the the boxes where to enter all the information that is going to configure the card. At the end there is an empty <div> to be filled by the Javascript.
The Javascript uses the following functions:
1. window.onload -> where we create all the initial variables needed.
2. addEventListener -> every change on the boxes is listened 
3. render -> fill the empty "div" with all the conditional information to create a card


# Initial Variable Values

| Name | Type | Default Value | Description |
| --- | --- | --- | --- |
| includeCover | boolean | true | it determines if the cover shoud be visible with an image or not |
| background | string | null | the url of the image that will used as background for the profile cover |
| avatarURL | string | null | the url for the profile avatar |
| socialMediaPosition | string | "right" | it can be `left` or `right` and it determines where to place the social media bar |
| twitter | string | null | the twitter username to be displayed on the profile |
| github | string | null | the github username to be displayed on the profile |
| linkedin | string | null | the linkedin username to be displayed on the profile |
| instagram | string | null | the instagram username to be displayed on the profile |
| name | string | null | The name of the user to be displayed on the profile |
| lastname | string | null | The name of the user to be displayed on the profile |
| role | string | null | The name of the user to be displayed on the profile |
| country | string | null | The name of the user to be displayed on the profile |
| city | string | null | the twitter username to be displayed on the profile |


# Instruction for Gitpod
Note: Make sure that you have node.js installed in your computer by typing in your terminal:

```bash
$ node -v

`npm install`




