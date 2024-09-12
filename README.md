# 🪄 commitgen

Ever stared at your Git changes, wondering what to write? Say hello to
`commitgen`, your AI-powered commit message genie! 🧞

`commitgen` analyzes your Git changes and crafts concise, purposeful commit
messages. It aims for brevity (under 50 chars), uses imperative tone, and can
provide context on what changed and why – all without you typing a word.

## Quick Start 🚀

1. Install [Ollama](https://ollama.ai/)
2. Download `commitgen`:
   ```
   curl -O https://raw.githubusercontent.com/vinibrsl/commitgen/main/commitgen
   chmod +x commitgen
   sudo mv commitgen /usr/local/bin/
   ```
3. In your Git repo:
   ```
   git add your-amazing-changes
   commitgen
   ```
4. Magic!
   ```
   Update ESLint configuration to support latest standards

   Updated the ESLint configuration to support the latest JavaScript standards
   and best practices. Included new rules for code formatting and improved
   error detection.
   ```

## Options

- Need help? `commitgen --help`
- Feeling nostalgic? `commitgen --version`
- Want a different AI brain? `commitgen --model gemma:2b`

## Troubleshooting

- Nothing happening? Make sure you've staged some changes!
- Make sure you have Ollama and at least llama3.1 installed

## Contribute

Got ideas to make `commitgen` even more magical? PRs welcome! Happy committing! 🎈
