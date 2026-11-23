# Example prompts for the Google Analytics 4 MCP server

These work as written in Claude, ChatGPT, Cursor, Codex, Gemini CLI and the other clients listed in the README. Anything that changes the account comes back as an approval first.

## Read and report

- With Sprites, what happened to conversions last week and which channel caused it?
- Ask Sprites for our top 10 landing pages by conversion rate this month.
- Use Sprites to compare organic and paid revenue quarter over quarter in GA4.
- Have Sprites break down ecommerce revenue by product for the last 30 days.
- Use Sprites to find which Google Ads campaigns bring sessions that never convert.
- With Sprites, check whether ads personalization is on for our linked Google Ads account.
- Have Sprites list the organic landing pages that lost the most sessions in 28 days.
- Use Sprites to explain the traffic spike on the 14th: source, landing page and conversion.

## Change, create and launch

- Ask Sprites to create a GA4 audience of people who visited pricing but never purchased.

## Recurring

- With Sprites, set up a Monday brief on traffic, conversions and the biggest change.

## Tips

- Name the campaign, ad set or page in full. Sprites receives only the request, not the earlier chat.
- Say the period ("last 30 days", "this quarter"); your client passes today's date so it resolves correctly.
- Working on several businesses? Say "switch to <business name>" first (`choose_business`).
- To compare channels, ask about them in one request, for example "compare Google and Meta CPA last month".
