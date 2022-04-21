# Installation
https://addons.mozilla.org/en-US/firefox/addon/styl-us/


# Userstyles
Once the stylus extension is installed you will be able to install these by clicking:
  - https://raw.githubusercontent.com/haydenbroadhead/stylish/master/Duckduckgo.user.css
  - https://raw.githubusercontent.com/haydenbroadhead/stylish/master/Stackoverflow.user.css
  - https://raw.githubusercontent.com/haydenbroadhead/stylish/master/Wikipedia.user.css
  - https://raw.githubusercontent.com/haydenbroadhead/stylish/master/BT.user.css

## Note
Stylus extension only will update when version is updated

## Refs
https://github.com/openstyles/stylus/wiki/Usercss


# Duck duck go settings
```javascript
{"kae":"-1","k5":"2","kay":"b","kat":"-1","kl":"uk-en","kp":"-2","kav":"1","k1":"-1","kaj":"m","kak":"-1","kax":"-1","kao":"-1","kau":"-1","ko":"1","kt":"u","kaf":"s","kj":"f8f8f8"}
```

# Joplin
Adds styling to joplin
https://joplinapp.org/

## Note
Github can't host CSS:
```
Here's why:

    When you request a file (CSS, Javascripts, HTML and some other files) via Raw link, they are usually served with a Content-Type Header "text/plain" and most modern browsers won't interpret that file as a CSS, Javascript or HTML. So, basically you are just serving a plain text file through that raw link.

GitHub does this in purpose because its relatively inefficient to serve raw files from a git repo directly, so they want to discourage people from using their repos for just static file hosting.

To overcome this, there are two solutions :

1) Turning GitHub repos into CDN and fetch proper Content-Type Header to browsers
2) Using GitHub pages 

```
Reference: https://www.twistblogg.com/blog/use-github-for-hosting-files

## Add this to Joplin app
```css
@import url("https://rawcdn.githack.com/haydenbroadhead/stylish/726c9f70cd984052ae36de957a196fc80193ba24/joplin-userstyle.css"); 
```
### Ref
https://raw.githack.com/

