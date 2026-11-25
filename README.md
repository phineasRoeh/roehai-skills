# RoehAI Skills

**Give your AI assistant a real phone number.**

This repository contains the official RoehAI skill: a set of instructions that teaches your AI assistant (Claude, ChatGPT, or any assistant that can read a skill file and connect to an MCP server) how to get its own phone number and work for you over the phone, through [RoehAI](https://www.roehai.com).

Once installed, your assistant can:

- Get a real phone number (Canada and United States) and answer incoming calls for you, 24/7
- Make outbound calls with a natural AI voice: prospecting, follow-ups, appointment booking
- Research businesses for a campaign (name, phone, website, email), then call them one by one or as a sales mission
- Send and read SMS from its number
- Report back with call logs, transcripts and summaries

The skill itself is free. The phone service behind it is pay-as-you-go: you only pay for a number and for call minutes, no subscription.

## Install in 3 steps

**Step 1: send this link to your assistant**

Copy the link of this repository (or of the `SKILL.md` file) into your conversation and ask your assistant to install it.

**Step 2: create your RoehAI account and API key**

Your assistant will guide you:

1. Create a free account at [roehai.com](https://www.roehai.com)
2. In the dashboard, open the **API Keys** tab and create a key (the "Connect to Muse" card creates one in one click)
3. Give the key to your assistant when it asks for it

**Step 3: let your assistant finish the setup**

Your assistant connects to the RoehAI server, loads the full operating playbook by itself, then walks you through the rest in the conversation: creating its agent, choosing your number from at least 5 options, buying call credits, and placing a real test call. Nothing is charged without your explicit confirmation.

## Pricing (pay-as-you-go, USD)

- Phone number: about $2 setup + about $3/month (exact price shown before purchase)
- Call credits, bought in minutes, usable for inbound and outbound calls:
  - 60 minutes: $30
  - 120 minutes: $55
  - 250 minutes: $110
  - 500 minutes: $215
- No subscription, no monthly plan required

## How it works

The skill is just a playbook. It contains no code and no secrets. All the work happens on the RoehAI service, behind your personal API key:

- Your assistant reads `SKILL.md` and follows it
- It connects to the RoehAI MCP server at `https://www.roehai.com/mcp` with your API key
- RoehAI operates the phone lines, the voice engine, the business research engine and the billing

## For developers

- Developer portal: [dev.roehai.com](https://dev.roehai.com)
- JavaScript/TypeScript SDK: [github.com/phineasRoeh/roehai-sdk](https://github.com/phineasRoeh/roehai-sdk)

## En français

Ce dépôt contient le skill officiel RoehAI : il donne à ton assistant IA (Claude, ChatGPT ou tout assistant compatible) un vrai numéro de téléphone. Ton assistant peut alors répondre aux appels pour toi, appeler tes prospects, faire la recherche d'entreprises d'une campagne et t'envoyer les rapports, le tout guidé étape par étape dans la conversation. Le skill est gratuit ; le service téléphonique est en paiement à l'usage (numéro + minutes d'appel), sans abonnement. Pour installer : envoie le lien de ce dépôt à ton assistant et suis ses instructions.

## License

MIT. See [LICENSE](LICENSE).

The RoehAI service itself (phone platform, voice engine, research engine) is a separate commercial service, available at [roehai.com](https://www.roehai.com).
