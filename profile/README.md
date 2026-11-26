<p align="center"><img src="https://raw.githubusercontent.com/commentexport/.github/main/profile/logo.png" width="96" alt="Combly logo"></p>

# Comment export by Combly

Comment export, comment search and a giveaway winner picker for YouTube, TikTok and Instagram posts: export comments to CSV, find what viewers ask and draw fair giveaway winners.

## Connect with AI assistants

Our [MCP server](https://github.com/commentexport/mcp-server) connects Combly to compatible AI clients, with browser sign-in and explicit permission.

get_account reads your plan and usage. load_comments and search_comments read a post's comments and find them by keyword, author, date, questions or links; export_comments returns CSV. draw_giveaway picks random winners under your rules and publishes a winner page; list_giveaways and get_giveaway read past draws. Loads and draws use your plan's limits: every call runs on a Combly account, and a free account includes 5 post loads and 2 giveaway draws, once, no card; subscribe for more (paid plans count per month).

## Links

- [Combly website](https://commentexport.app)
- [MCP & API docs](https://commentexport.app/developers)
- [MCP source and setup](https://github.com/commentexport/mcp-server)
- [Agent skill](https://github.com/commentexport/agent-skill) — install with `npx skills add commentexport/agent-skill`
