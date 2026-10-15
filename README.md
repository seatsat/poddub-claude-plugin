# poddub for Claude Code

This plugin lets Claude Code work with [poddub](https://poddub.com): your teams, sources, episodes and scripts, signed in as you. It adds poddub's server to Claude Code; it holds no key and nothing of yours.

## Install

In a terminal:

```bash
claude plugin marketplace add seatsat/poddub-claude-plugin
claude plugin install poddub@poddub
```

With Claude Code 2.1.292 or later, one command does both:

```bash
claude plugin install poddub --marketplace seatsat/poddub-claude-plugin
```

The plugin is installed for you, in every project.

## Sign in

Start Claude Code, run `/mcp`, choose poddub and follow the steps in your browser. On poddub.com you sign in with your work email and a code, choose your organization, and choose what Claude Code may do. You need a poddub account first: create one in the poddub app.

## Other ways to connect

You do not need this plugin if you added poddub in claude.ai and use Claude Code with your claude.ai account: poddub is in `/mcp` already. To add poddub with one command, to share it with a project, or to use a key for automation, see [Connect Claude Code](https://poddub.com/docs/agents/claude-code).

## Remove it

```bash
claude plugin uninstall poddub@poddub
claude plugin marketplace remove poddub
```

This removes the plugin from Claude Code. To end the connection on poddub as well, open [poddub.com/connections](https://poddub.com/connections) and select **End** next to Claude Code.

## Help

[Support](https://poddub.com/support) · [Privacy](https://poddub.com/privacy) · [Terms](https://poddub.com/terms)

## Licence

MIT. © 2026 Seats at, LLC.
