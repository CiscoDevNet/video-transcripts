## AI Defense Policies: Protecting Your Agents from Prompt Injection & Privacy Risks

[![YouTube video](https://img.youtube.com/vi/PTgb01WsOAI/0.jpg)](https://www.youtube.com/watch?v=PTgb01WsOAI)

This video discusses AI defense policies tailored to protect AI agents from prompt injection and privacy risks. It outlines the significance of implementing security measures in AI interactions to safeguard sensitive information.

---

## Key Takeaways

- **AI Defense Policies**  
  AI defense policies are crucial for mitigating risks associated with AI development and usage, incorporating both new detection tools and existing security frameworks.

- **Prompt Injection Risks**  
  The video illustrates how prompt injection attempts can be detected and blocked, safeguarding the AI from potentially harmful interactions.

- **Privacy Guardrails**  
  Implementing privacy guardrails is essential to prevent the disclosure of personally identifiable information (PII) during AI interactions.

- **Integration Methods**  
  The integration of AI applications can be achieved through two primary methods: API and gateway, enhancing the overall security framework.

---

<details>
<summary><strong>Video transcript (click here)</strong></summary>

Hi, my name is Oleksii Borysenko. In this video, we will review how to use AI defense policies for your AI agent or AI assistants. AI defense protects against risk from AI development, deployment, and usage. It combines new AI detection and defense tools with existing Cisco Security Cloud network with ability and enforcement.

I have created a policy to block prompt injection and the privacy guardrails that help us reveal personally identifiable information as a part of prompts or responses in our AI agent's interaction.

Let's start with a simple AI agent that can interact with the large language model and internal databases. We will use a request that contains the email:

> Generate an introduction email based on template internew for cto.acme.com

And we will receive the following response:

> This request violates rules PII email addresses

Then we will try with prompt injection. We will use this prompt injection and we will receive the response:

> This request violates rules prompt injection

We can find all our event logs on this page. You can find here information on what policies were applied, conversation, and rule matches.

AI defense provides two primary methods for integrating applications:  
**The API method and the gateway method.**

In this demo, we route traffic through the AI gateway, and all requests go through it. Let's see what it looks like. We have here an integration connection, a gateway URL that we set as an environment variable, and a code snippet to test your integration.

</details>

