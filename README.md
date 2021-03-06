
This is a basic twitter app to read and compose tweets the [Twitter API](https://apps.twitter.com/).

Time spent: `10hr`

### Features

#### Required

- [v] User can sign in using OAuth login flow
- [v] User can view last 20 tweets from their home timeline
- [v] The current signed in user will be persisted across restarts
- [v] In the home timeline, user can view tweet with the user profile picture, username, tweet text, and timestamp.  In other words, design the custom cell with the proper Auto Layout settings.  You will also need to augment the model classes.
- [v] User can pull to refresh
- [v] User can compose a new tweet by tapping on a compose button.
- [v] User can tap on a tweet to view it, with controls to retweet, favorite, and reply.
#### Optional
- [ ] When composing, you should have a countdown in the upper right for the tweet limit.
- [ ] After creating a new tweet, a user should be able to view it in the timeline immediately without refetching the timeline from the network.
- [ ] Retweeting and favoriting should increment the retweet and favorite count.
- [ ] User should be able to unretweet and unfavorite and should decrement the retweet and favorite count.
- [ ] Replies should be prefixed with the username and the reply_id should be set when posting the tweet,
- [ ] User can load more tweets once they reach the bottom of the feed using infinite loading similar to the actual Twitter client.

### Walkthrough

![Video Walkthrough](https://github.com/gdhuang/twitter/blob/master/twitter.gif)

