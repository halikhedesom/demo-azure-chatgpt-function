This is Azure funciton to call Azure OpenAI ChatGPT service through a scoped package **@freistli/azurechagptapi** , related Azure OpenAI ChatGPT wrapper code is [in ../src/](https://github.com/freistli/chatgpt-api/blob/main/src/azure-chatgpt-api.ts)

To use it:

1. Deploy the Turbo model with "chatgpt" or other deployment names in Azure OpenAI service.

2. Please set three environments variables:

```
    AZURE_OPENAI_API_KEY
    AZURE_OPENAI_API_BASE
    CHATGPT_DEPLOY_NAME
```

3. Intstall packages:

   npm install

Follow you tube series part 3 to deploy functions onto Azure functions

Part1:https://youtu.be/jy08dnjOV1k?si=Jv89ELvYpspvvoN6
Part2:https://youtu.be/CqHyLQRpkI8?si=v-5uxmE6w_TISt-D
Part3:https://youtu.be/F1vTrFAaYck?si=xRL5XoOucEX8QCvv
