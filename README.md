# Tweener plugin for Claude Code

Connects Claude to your own [Tweener](https://tweener.club) account so you can ask
about your racquet-sports life in plain language — tennis, padel, pickleball and
beach tennis.

```
/plugin marketplace add tweener-dev/claude-plugin
/plugin install tweener@tweener
```

The first Tweener question opens a browser to sign in to your Tweener account and
approve access, and you choose there whether Claude may only read your data or also
act on it. Claude sees only what your account can already see in Tweener.

## What you can ask

- "What's on my Tweener schedule this week?"
- "How have I done against Bruno this year?"
- "Has my tennis rating moved since June?"
- "Any open plays near me on Saturday morning?"
- "Set up auto-match for padel."
- "What did I write in my notes after last week's match?"
- "What does my coaching plan say I should work on?"
- "What's my scouting report on Bruno?"
- "Save a note that Bruno's backhand breaks down under pace."

## Other Claude surfaces

On claude.ai, Claude Desktop or ChatGPT you don't need this plugin — add
`https://mcp.tweener.club/mcp` as a custom connector instead. This plugin is the
Claude Code packaging of that same connector.

## Privacy

The connector acts as you and sees only what your account can already see in
Tweener: your own data — profile, matches, ratings, schedule, training, the
private notes you wrote, and your AI coaching plan and scouting reports — plus what other players make visible to you, such as
names, ratings and records their privacy settings allow, open plays and ranking
standings. It never reads another player's private data. Reading versus acting
on your behalf are separate permissions you grant when you connect, and
disconnecting in your assistant's settings revokes access immediately. See the
[privacy policy](https://tweener.club/PRIVACY_POLICY.html) — "Connected AI
Assistants" under Information Sharing and Disclosure.

## Support

support@tweener.club
