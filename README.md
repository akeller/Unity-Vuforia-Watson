**Not tested for Watson SDK for Unity version 3+, please use 2.x until this content is updated.**

# Unity-Vuforia-Watson
A complete Unity project using Watson SDK and Vuforia with voice activated animations.

## How can I make this work?

Vuforia is available with Unity, but will need to be enabled during Unity update or initial download.

You'll need an IBM Cloud account with the following Watson services:

* Assistant
* Speech-to-Text
* Text-to-Speech

Use the username, password, and URL for each service in the Unity editor (avatar GameObject with script component). Assistant requires a workspace id as well.

Upload the .json file into Watson Assistant to use the intents, entities, and dialog.
