# LLm presentaion for Professionals

This Project is made for profestional to do their tasks lie power point etc and be productive with emails and wordks and be a fat ased worker with ai and llm data to get from thier prevoious works



## Getting Started

### 1. install the needed package:

```bash
npm i
```

### 2. Set the required environment variables:

copy `.env.local.example` to `.env.local` and populate the required environment variables.

> ⚠️ **Important:** Not all users have access to the GPT-4 model yet. If you don't have access, you can use GPT-3 by setting `OPENAI_MODEL` to `gpt-3.5-turbo` in the `.env.local` file.

### 3. Run the app

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### 4. Use the Copilot

TODO add details what to do as a user

## Zoom in on the CopilotKit code

1. Look for `/api/copilotkit/route.ts` and `/api/copilotkit/tavily.ts` - for the research agent integrated into the spreadsheet

2. Look for `useCopilotReadable` to see where frontend application context is being made accessible to the Copilot engine

3. Search for `updateSpreadsheet`, `appendToSpreadsheet`, and `createSpreadsheet` to see application interaction hooks made available to agents.

## Learn More

To learn more about CopilotKit, take a look at the following resources:

- [CopilotKit Documentation](https://docs.copilotkit.ai/getting-started/quickstart-chatbot) - learn about CopilotKit features and API.
- [GitHub](https://github.com/CopilotKit/CopilotKit) - Check out the CopilotKit GitHub repository.
- [Discord](https://discord.gg/6dffbvGU3D) - Join the CopilotKit Discord community.
