- 👋 Hi, I’m @Kin7ness
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Kin7ness/Kin7ness is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
curl -X POST \  
  https://open.feishu.cn/open-apis/bot/v2/hook/35db48ef-aa84-449d-8296-7fef16b0077b \  
  -H 'Content-Type: application/json' \  
  -d '{  
    "msg_type": "text",  
    "content": {  
      "text": "Hello, Feishu!"  
    }  
  }'
