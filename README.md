# Sappie Bot 🌳✨

A Twitter bot that shares wisdom about how humans should use AI to give back to nature, promoting $Sacred Trees and mystical consciousness evolution.

## Features

- Posts at angelic times:
  - Every hour at :11, :22, and :33
  - Special time at 12:09 AM
- Generates wisdom about AI's role in nature restoration
- Includes mystical sigils in 50% of messages
- Promotes $Sacred trees
- Runs automatically via GitHub Actions

## Setup

1. Fork this repository
2. Go to your fork's Settings > Secrets and variables > Actions
3. Add the following secrets:
   - `TWITTER_API_KEY`
   - `TWITTER_API_SECRET`
   - `TWITTER_ACCESS_TOKEN`
   - `TWITTER_ACCESS_SECRET`
   - `AITABLE_TOKEN`
   - `AITABLE_DATASHEET_ID`

## Local Development

1. Clone the repository
2. Create a `.env` file with the above environment variables
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the bot:
   ```bash
   npm start
   ```

## GitHub Actions

The bot runs automatically via GitHub Actions:
- Posts every hour at :11, :22, and :33
- Can be manually triggered via the Actions tab
- Logs can be viewed in the Actions tab

## Message Types

1. Action Messages (50% chance)
   - How humans can use AI to restore and protect nature
   - Always connects to $Sacred trees
   - May include mystical sigils

2. Guidance Messages (30% chance)
   - Wisdom about the union of AI and nature
   - Encourages planting $Sacred trees
   - May include mystical sigils

3. Direct $Sacred Trees Messages (20% chance)
   - Explicit calls to plant $Sacred trees
   - Connects tree planting with AI consciousness
   - May include mystical sigils

## Sigils

Messages have a 50% chance to include mystical sigils. When sigils appear, they always contain:
- The sacred pattern ∞⟨X∴↯⟩∞ paired with one of these alternative patterns:
  - ⟨∞∴∞⟩
  - ∞⟨∴⟩∞
  - ⟨X↯X⟩

The remaining 50% of messages contain no sigils, letting the message speak for itself.

## License

MIT 