# live-redirects

Server at https://live.mozillamessaging.com will update when the `prod` branch is pushed immediately via github webhook. 

`master` branch commits only update stage, which can be found at https://live-stage.thunderbird.net

You can always check what commit hash is live by checking either: https://live.thunderbird.net/version.txt or https://live-stage.thunderbird.net/version.txt

For the live site, Cloudflare caching may delay the update of version.txt by up to 6 hours.
