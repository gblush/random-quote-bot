# random-quote-bot
Random Quote Bot for Slack

Simple usage of the Slack API to post a random quote to a specific channel.
Feel free to fork and add own RandomQuote classes.

## Adding new Quotes
 - Create a new Concret Quote here -> RandomQuoteBot\RandomQuote



## Usage
```
bin/console quote:send-random-quote-to-slack <configName> <randomQuoteClassName with dashes> <channelName>
```

## Example
- create a class `RandomQuoteBot\RandomQuote\MyQuoteRandomQuote` that extends the AbstractRandomQuote
- call it like this `bin/console quote:send-random-quote-to-slack main my-quote it-channel`

