# CallaTwitterCell
Preferences Twitter cell that displays two users next to each other

## Preview
<img src="Preview.png" alt="Preview" width=50% height=50%>

## Implementation
1. Copy both the `.m` and `.h` file into your preference bundle
2. Add them to your `Makefile`
3. Add the cell to your `Root.plist` and update the user strings accordingly
```xml
<dict>
    <key>cellClass</key>
    <string>CallaTwitterCell</string>
    <key>leftUserDisplayName</key>
    <string>LEFT_USER_DISPLAY_NAME</string>
    <key>leftUserUsername</key>
    <string>LEFT_USER_USERNAME</string>
    <key>rightUserDisplayName</key>
    <string>RIGHT_USER_DISPLAY_NAME</string>
    <key>rightUserUsername</key>
    <string>RIGHT_USER_USERNAME</string>
    <key>height</key>
    <real>58</real>
</dict>
```
