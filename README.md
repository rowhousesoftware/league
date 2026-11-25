# League

Youth league schedules, checked by code. Fix rainouts with the fewest moved games.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://league.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http league https://league.rowhousesoftware.com/mcp
```

## Tools

- `preview_schedule`: Finds a valid schedule and shows it, without saving anything.
- `build_schedule`: Builds a fair schedule, or fixes one after a rainout with the fewest moved games.
- `check_schedule`: Checks every game against your fields, coaches, rest and caps.
- `import_table`: Reads a CSV of teams, coaches, fields, slots or games.
- `export_schedule`: Makes team and field PDFs, team calendar files and a CSV.
- `publish_calendars`: Shares team calendar links that update when the schedule does.

## Free and paid

Free: up to 6 teams. A season code will be $79 once, for up to 70 teams and ten rainout fixes. It isn't on sale yet.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://league.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
