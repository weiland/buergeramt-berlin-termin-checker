## buergeramt-berlin-termin-checker

This is a simple script repo which will check the next available appointment at the `Buergeramt Berlin`. The script can be run as a cronjob.

### Initial setup

```bash
# Clone the repo
git clone https://github.com/weiland/buergeramt-berlin-termin-checker
cd buergeramt-berlin-termin-checker

# Install dependencies
npm i

# create a config.js 
mv config.js.sample config.js

# put in pushover keys and desired month into config.js
vim/mate/subl config.js

# run it
node index.js
```
