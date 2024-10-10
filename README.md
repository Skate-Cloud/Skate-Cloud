- 👋 Hi, I’m @Skate-Cloud
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Skate-Cloud/Skate-Cloud is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
--request GET \
  --url https://api.dune.com/api/beta/balance/{address} \
  --header 'X-Dune-Api-Key: <x-dune-api-key>'
{
  "balances": [
    {
      "address": "native",
      "amount": "605371497350928252303",
      "chain": "ethereum",
      "decimals": 18,
      "price_usd": 3042.816964922323,
      "symbol": "ETH",
      "value_usd": 1842034.6622198338
    }
  ],
  "next_offset": "dKMBWDLqM7vlyn5OMEXsLWp0nI4AAAABA5JLazNO7x4poVGqUwsgxgqvvIg",
  "request_time": "2023-11-07T05:31:56Z",
  "response_time": "2023-11-07T05:31:56Z",
  "wallet_address": "0xd8da6bf26964af9d7eed9e03e53415d37aa96045"
}
