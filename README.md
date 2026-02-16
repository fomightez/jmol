# jmol
My place for hosting and serving my own Jmol / Jsmol- related content.  
Useful for things that are more complex than Proteopedia easily allows or when Proteopedia is down or upgrading as the case is currently in early 2026.


-------------------------------------------------------

## Technical

This uses GitHub actions to deploy the static content so no need for `gh-pages` branch or commands like `symbolic-ref "refs/heads/gh-pages" "refs/heads/master"` and `git push --mirror` after each commit and push.  
Example test site:  
https://fomightez.github.io/jmol/simple.htm  
My additional content beyond this custom README and all the standard JSmol content is in the subdirectory `w` to make updating Jmol/JSmol later convenient.

**When updating Jmol/JSmol first** follow directions there & test things at [my development / testing grounds for this repo](https://github.com/fomightez/testjmol).  
The root in this repo corresponds to the directory `testjmol/jsmol/jsmol/` [there](https://fomightez.github.io/testjmol/jsmol/jsmol/).
