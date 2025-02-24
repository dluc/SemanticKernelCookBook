# **Semantic Kernel Cookbook**


![cover](imgs/cover.png)

With the rise of LLM, AI has entered the 2.0 era. Compared with previous AI technologies, the threshold has been lowered and the applicability has been enhanced. It is no longer limited to the field of data science, and more different types of jobs and roles of people are participating in large-scale research in the application scenarios of the model. For how traditional engineering projects or enterprise applications to enter the field of LLM, a framework is an important key. Especially for traditional projects, companies must think about how to access LLM faster and at low cost. In 2023, the first year of LLM, the open source community has a lot of frameworks and solutions based on LLM applications. I personally like LangChain, BentoML, prompt flow , autogen and Semantic Kernel. But overall, Semantic Kernel is more suitable for traditional engineering and multi-language engineering teams, LangChain is suitable for data science personnel, and BenToML is suitable for multi-model deployment scenarios. In December 2023, when Semantic Kernel officially releases 1.0.1 based on .NET version, I also hope to use this manual to give you some ways to learn and get started. Although Semantic Kernel still has many imperfections, it does not prevent everyone from learning and using it.

| Session  | Intro | <center>.NET<br/> Samples</center> | <center>Python <br/>Samples</center> |
|----------|:----------|:-------------:|------:|
| [Getting started with LLM](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/00.IntroduceLLM.md) | Begin to know LLM, including OpenAI, Azure OpenAI Service and LLM on Hugging face |  |  |
| [Using Azure OpenAI Service With SDK](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/01.UsingAzureOpenAIServiceWithSDK.md)  |  Learn how to use Azure OpenAI Service with SDK  |  <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/dotNET/01/dotNETSDKAOAIDemo.ipynb)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/01/PythonSDKAOAIDemo.ipynb)</center> |
| [Foundations of Semantic Kernel](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/02.IntroduceSemanticKernel.md)  | What is Semantic Kernel? What are its advantages and disadvantages? Semantic Kernel related concepts, etc. | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/dotNET/02/LearnSK.ipynb)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/02/LearnSK.ipynb)</center> |
| [The skills of LLM - Plugins](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/03.Plugins.md) | We know that communicating with LLM requires the use of prompt engineering? For enterprise applications, there are many business-oriented prompt engineering. In Semantic Kernel we call it Plugins. In this session we will introduce how to use Semantic Kernel Plugins and how to define your own Plugins | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/dotNET/03/PluginWithSK.ipynb)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/03/FunctionCallWithSK.ipynb)</center> |
| [Planner - Let LLM have planning work](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/04.Planner.md) | Human beings need to complete a job step by step, and the same goes for LLMs. Semantic Kernel has a very powerful task planning capability - Planner, in this session we will explain in detail how to define and use Planner to make your application more intelligent | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/dotNET/04/PlannerWithSK.ipynb)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/04/PlannerWithSK.ipynb)</center> |
| [Embedding Skills](https://github.com/microsoft/SemanticKernelCookBook/blob/main/docs/en/05.Embeddings.md)  | Building RAG applications is the most commonly used LLM solution at this stage. It is very convenient to build RAG applications through Semantic Kernel This session will tell you how to use Semantic Kernel Embeddings  | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/dotNET/05/EmbeddingsWithSK.ipynb)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/05/EmbeddingsWithSK.ipynb)</center> |
| HandsOnLab | Through three hands on labs projects, let everyone truly understand the application of Semantic Kernel | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/tree/main/workshop/dotNET)</center> | <center>[Click](https://github.com/microsoft/SemanticKernelCookBook/tree/main/workshop/python)</center> |


***如果你需要中文，请 [点击这里](https://github.com/microsoft/SemanticKernelCookBook/blob/main/README.zh-cn.md)***


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
