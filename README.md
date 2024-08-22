# BRK421 Data Security for AI

## Session Desciption

In an era where artificial intelligence (AI) is transforming industries, ensuring the security of data used in AI systems is paramount. This session, “Data Security for AI,” will delve into the critical aspects of protecting data throughout the AI lifecycle. Participants will gain insights into the unique challenges and best practices for securing data in AI applications, from data collection and storage to processing and deployment.

## Learning Outcomes

* Understand Data Security in AI: Explore the fundamentals of data security and its importance in AI systems.
* Threats and Vulnerabilities: Identify common threats and vulnerabilities in AI data pipelines and how to mitigate them.
* Data Privacy and Compliance: Learn about regulatory requirements and best practices for maintaining data privacy and compliance in AI projects.
* Secure Data Handling: Discover techniques for secure data handling, including encryption, anonymization, and access control.
* AI Model Security: Understand the importance of securing AI models and preventing adversarial attacks.

## Technology Used

* Copilot Studio
* Microsoft Purview
* Azure AI Studio

## Additional Resources and Continued Learning
TODO: If you would like to link the user to further learning, please enter that here.

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Docs  | [Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/) | Learn more about Copilot Studio |
| Docs  | [Microsoft Purview](https://learn.microsoft.com/en-us/purview/purview) | Learn more about Microsoft Purview |
| Docs  | [Azure AI Studio](https://learn.microsoft.com/en-us/azure/ai-studio/) | Learn more about Azure AI Studio |

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="https://github.com/joey-snow">
        <img src="https://avatars.githubusercontent.com/u/23324389?v=4" width="100px;" alt="Joey Snow
"/><br />
        <sub><b>Joey Snow
</b></sub></a><br />
            <a href="https://github.com/joey-snow" title="talk">📢</a> 
    </td>
</tr>

</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI
Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at https://aka.ms/RAI. Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics.](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in)

You can evaluate your AI application in your development environment using the [prompt flow SDK.](https://microsoft.github.io/promptflow/index.html) Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide.](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk) Once you execute an evaluation run, you can [visualize the results in Azure AI Studio.](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results)

