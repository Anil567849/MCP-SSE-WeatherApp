# Make sure to build your project
``` bash
cd McpClient 
npm run build

cd ../McpServer
npm run build
```

# To Run Server
``` bash
cd McpServer
node dist/index.js
```

# Open new Terminal - To Run Client
``` bash
cd McpClient
node dist/index.js
```

# Add your Anthropic API Key
1. Create a .env file inside in the McpClient/.env
2. add your key: ANTHROPIC_API_KEY=<your key>
