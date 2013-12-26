# tweet-cli
## tweet from your cli

### Installing
Just do a simple `npm -g i tweet-cli`. After that you'll be prompted for a `~/.tweet` file. It should have this format:

```
{
   "consumer_key": "YOUR_CONSUMER_KEY",
   "consumer_secret": "YOUR_CONSUMER_SECRET",
   "access_token_key": "YOUR_ACCESS_TOKEN_KEY",
   "access_token_secret": "YOUR_ACCESS_TOKEN_SECRET"
}
```

Fortunately that's all you need to start tweeting from your cli –just remember that all those keys and secrets can be obtained from [twitters developers page](https://dev.twitter.com) 

### Using
Just do `tweet my message!` and depending on your shell you might need to wrap `@mentions` or `#tags` in quotes.

That's all folks. Happy tweeting from your cli.

Star if you like!
