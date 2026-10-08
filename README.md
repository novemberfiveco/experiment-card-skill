# Experiment Card skill

A Claude Code skill that helps you turn a business idea or assumption into a testable experiment card. It follows the *Validating Business Ideas* (Strategyzer) method.

## Install

### Claude Code

Run these two commands in Claude Code:

```text
/plugin marketplace add novemberfiveco/experiment-card-skill
/plugin install experiment-card@novemberfive
```

### Claude desktop app

You need a paid Claude plan (Pro, Max, Team, or Enterprise).

1. Open **Customize** and go to the **Plugins** tab.
2. Click **Add**, then select **Add marketplace**.
3. Under **Add from a repository**, enter `novemberfiveco/experiment-card-skill`.
4. Find "experiment-card" in the new marketplace and click **Add**.

### Codex

Run these two commands in your terminal:

```bash
codex plugin marketplace add novemberfiveco/experiment-card-skill
codex plugin add experiment-card@novemberfive
```

### ChatGPT desktop app

1. Run this command in your terminal:

   ```bash
   codex plugin marketplace add novemberfiveco/experiment-card-skill
   ```

2. Restart the ChatGPT desktop app.
3. Open the Plugins Directory and select the "November Five" marketplace.
4. Install the "experiment-card" plugin.

## Use

Describe the assumption you want to test, for example "I want to know if customers will pay for X". Claude or Codex starts the skill and builds the card with you, one section at a time.

## License

MIT
