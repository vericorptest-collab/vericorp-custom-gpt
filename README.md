# VeriCorp Custom GPT

Custom GPT for European company verification via the [VeriCorp API](https://rapidapi.com/vericorp/api/vericorp-api).

## Setup

1. Go to [ChatGPT → Create a GPT](https://chatgpt.com/gpts/editor)
2. **Name**: VeriCorp — European Company Verification
3. **Description**: Look up and verify European companies by tax ID. 28 countries supported.
4. **Instructions**: Copy contents of [instructions.md](instructions.md)
5. **Actions**: Import [openapi-gpt.yaml](openapi-gpt.yaml)
6. **Authentication**: API Key
   - Auth type: API Key
   - Header name: `X-RapidAPI-Key`
   - API Key: Your RapidAPI key
7. Add custom header: `X-RapidAPI-Host: vericorp-api.p.rapidapi.com`

## Example Prompts

- "Look up the company with tax ID PT502011378"
- "Is VAT number DE811871080 valid?"
- "Show me details for UK company 00445790"
- "What countries do you support?"

## License

MIT
