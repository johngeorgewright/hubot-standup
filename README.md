# Hubot standup

A hubot script that ping the team everyday for the standup.

## Install

Add **hubot-standup** to your *package.json*.

    npm install --save hubot-standup

Then add **hubot-standup** to *external_scripts.json*.

```javascript
[..., "hubot-standup", ...]
```

## Usage

To set a standup for every week day:

    hubot standup at 8 for user, user2, user3

Specify a timezone:

    hubot standup at 8 (Europe/Paris) for user, user2, user3

Report a standup for today:

    hubot standup report at 15

Remove the standup:

    hubot standup remove

### Tests

    npm test

## License

Copyright (c) 2014 François de Metz

See [LICENSE](LICENSE).
