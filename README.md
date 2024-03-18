# ai-case-study

Module 1 Challenge

Due date: 3/21/24 @ 11:59pm

# _Adept Ai -Reinventing User Experience: AI That Masters Your Software_

## Overview and Origin

### Name of company

Adept AI 

### When was the company incorporated?

Jan 2022 

### Who are the founders of the company?

Ashish Vaswani, David Luan, Niki Parmar

### How did the idea for the company (or project) come about?

The three co-founders of Adept AI - Chief Scientist Ashish Vaswani and CTO Niki Parmar - were former employees of Google Brain. They were part of the team that developed the transformer model architecture, a key component in applications like GPT-3.

At Google, their aim was to create a transformer that could handle all kinds of machine learning tasks. However, they encountered a challenge. Although models like GPT-3 excel at reading and writing, they still can't interact effectively in a digital environment. [1]

> *In Luan's words, “We’re not trying to replace humans at valuable tasks, like some other companies might be aiming to do. Our goal is simply to build the best AI teammate possible for everyone.” [19]*

### How is the company funded? How much funding have they received?

Adept AI emerged from stealth mode in April 2022 with a Series A funding round of $65 million from VC firms and angel investors. Adept AI has raised $415M to this date.
Adept AI closed its last funding round on Mar 14, 2023 from a Series B round.
This funding round was co-led by General Catalyst and Spark Capital with participation from Addition, Greylock, Atlassian Ventures, Microsoft, Nvidia, Workday Ventures, Caterina Fake, Frontiers Capital, PSP Growth, SV Angel and A.Capital. [2]

## Business Activities

### What specific problem is the company or project trying to solve?

Adept AI is a company that specializes in machine learning research and product development. Their work is similar to robotic process automation (RPA), a technology that uses automation, computer vision, and machine learning to automate repetitive tasks like filling out forms and responding to emails. However, Adept AI goes a step further. They're creating what they call a "general intelligence." This is a system that fosters creative collaboration between humans and computers. The goal of Adept AI's founders was to create a tool, a transformer, that could not only read and write but also actively interact within the digital world. [8]

[Adept.ai](http://adept.ai/) offers a unique advantage in the field of artificial intelligence by developing an Action Transformer (ACT-1) that is trained to use digital tools like browsers and spreadsheets through a natural language interface. This innovative approach enables seamless interaction between people and computers, allowing for more intuitive and efficient utilization of digital tools. This specific capability sets [Adept.ai](http://adept.ai/) apart from its competitors, providing a distinct edge in enhancing user experience and productivity within the realm of AI technology. [6]

### Who is the company's intended customer? Is there any information about the market size of this set of customers?

The intended customers of Adept AI are businesses and individuals looking to enhance their productivity and efficiency through advanced AI solutions. Adept AI aims to cater to enterprises seeking innovative technologies that can streamline workflows, boost creativity, and facilitate collaboration between humans and computers. By developing AI-powered tools that improve content creation, project management, and user interactions with digital tools, Adept AI targets a market segment interested in leveraging cutting-edge AI capabilities to enhance their operations.

Regarding the market size of these customers, the information provided does not explicitly mention specific data on the market size of Adept AI's intended customer segment. However, the company's ability to secure significant funding, attract strategic investors like Microsoft, Nvidia, Atlassian, and Workday, and achieve a revenue of $75 million in 2024 with a team of 75 employees indicates a strong market interest and potential for growth within the target customer base. [38]

Over the past few months, Adept AI has made significant strides. It's now capable of performing complex tasks, such as importing LinkedIn URLs into recruitment software. These advances have caught the attention of strategic investors like Microsoft, Nvidia, Atlassian, and Workday. All of these companies see potential benefits in integrating Adept's AI assistant into their software offerings in the future. [19]


### What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

In the field of Machine Learning and Generative AI, [Adept.ai](http://adept.ai/) stands out among major competitors like Alphabet-backed [DeepMind](https://deepmind.google/) and [Inflection AI](https://inflection.ai/). They are recognized for their unique approach to developing an AI assistant that can interact with various software tools via natural language commands. Their flagship model, ACT-1, is a large-scale Transformer trained to use digital tools, including web browsers like Chrome, enabling it to observe and interact with browser activities. [Adept.ai](http://adept.ai/) emphasizes the importance of large-scale human feedback to continuously evaluate and improve the performance of their AI systems. [3][36]

The company's innovative strategies, like training neural networks to carry out general tasks for enterprise clients and creating a natural language interface to access software tools like Adobe Photoshop and Airtable, have earned [Adept.ai](http://adept.ai/) a prominent spot in the AI industry. [9]

[Adept.ai](http://adept.ai/) is pushing the boundaries of AI technology. They are committed to creating advanced AI solutions that enhance human-computer interactions, making them more natural and productive.  

### Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

### ****Disclaimer: Adept AI's code is proprietary and protected. I gathered as much information as possible from publicly available sources, cited at the end of this research. I found the open-source code for their development of Persimmon-8B and referenced the available code below.

[Adept.ai](http://adept.ai/) leverages advanced tools and a complex programming stack to develop innovative AI technologies. They use Metaflow in conjunction with Argo on Kubernetes to optimize and monitor their machine learning processes. This not only enhances the efficiency of managing machine learning workflows and large language models but also aligns with their goal of creating transformers that can interact with various computer applications. [16]

However, the implementation of Metaflow and Argo presented some obstacles. The complexity of their codebase necessitated a thorough cleanup and detangling of the code for integration into Metaflow's workflows. Containerizing the large codebase, which is almost 1GB in size, added to the challenge. To simplify job launching and information retrieval, they developed their own command-line tool. [16]

Furthermore, [Adept.ai](http://adept.ai/) uses Metaflow and Argo to monitor different components of their infrastructure like Slurm, handle routine tasks, maintain nightly backups, and manage various infrastructure elements. They are continuously working on overcoming challenges, such as queuing workflows that require more nodes than currently available and creating easily customizable workflows. [16]

Another significant achievement of [Adept.ai](http://adept.ai/) is the development of [Persimmon-8B](https://github.com/persimmon-ai-labs/adept-inference), a powerful open-source language model released under an Apache license. Despite being trained on just 37% of the data used by its closest competitor, LLaMA2, it delivers comparable performance. This model, developed as part of Adept's model scaling program, is poised to support the company's future AI products. [18]
Over the past few months, Adept AI has made significant strides. It's now capable of performing complex tasks, such as importing LinkedIn URLs into recruitment software. These advances have caught the attention of strategic investors like Microsoft, Nvidia, Atlassian, and Workday. All of these companies see potential benefits in integrating Adept's AI assistant into their software offerings in the future. [2]
This product’s code has been made available and can be found [here](https://github.com/persimmon-ai-labs/adept-inference). [18]

## Landscape

### What field is the company in?

Adept AI operates in the field of artificial intelligence (AI), specializing in machine learning research and product development. Their focus is on creating a "general intelligence" system that promotes creative collaboration between humans and computers, aiming to develop advanced AI solutions that enhance user interactions with computers and boost productivity within the realm of AI technology. [37] 

### What have been the major trends and innovations of this field over the last 5–10 years?

The major trends and innovations in the field of artificial intelligence (AI) over the last 5-10 years have been characterized by significant advancements and transformative developments. Some key trends and innovations include:

1. **Advancements in Machine Learning**: Over the past decade, there have been remarkable advancements in machine learning techniques, particularly in deep learning algorithms. These advancements have led to breakthroughs in natural language processing (NLP), computer vision, and reinforcement learning.
2. **Generative AI**: The emergence of generative AI models, such as GPT-3 and Persimmon-8B, has revolutionized the field by enabling machines to generate human-like text and content. These models have opened up new possibilities for creative applications and content generation. [18]
3. **AI Assistants and Automation**: The development of AI assistants like those created by Adept AI, capable of interacting with software tools through natural language commands, has streamlined workflows and enhanced productivity in various industries. Automation through AI has become more prevalent, simplifying repetitive tasks and improving efficiency.
4. **Ethical AI and Responsible Innovation**: There has been a growing emphasis on ethical considerations in AI development, focusing on issues like bias mitigation, transparency, and accountability. Companies are increasingly prioritizing responsible innovation to ensure that AI technologies benefit society as a whole.
5. **AI in Business Applications**: AI has seen widespread adoption in business applications, ranging from customer service chatbots to predictive analytics for decision-making. Companies are leveraging AI to optimize operations, personalize customer experiences, and drive growth.
6. **Advances in Natural Language Processing**: The field of NLP has witnessed significant progress with the development of large-scale language models like BERT, GPT series, and Persimmon-8B. These models have improved language understanding, text generation, and conversational AI capabilities.
7. **AI Hardware Innovations**: Innovations in AI hardware, such as specialized chips like GPUs and TPUs optimized for deep learning tasks, have accelerated the training and inference processes of AI models. This hardware evolution has contributed to the scalability and efficiency of AI applications.
8. **Interdisciplinary Collaborations**: Collaboration between AI researchers, domain experts, and industry professionals has become more prevalent, leading to cross-disciplinary innovations that address complex real-world challenges. Interdisciplinary approaches have enriched AI research and application domains.

Overall, the last 5-10 years have witnessed a rapid evolution in artificial intelligence technologies, with a focus on enhancing capabilities, improving user interactions, ensuring ethical practices, and driving innovation across various sectors. [37]

### What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?

In the AI industry, companies gauge success through several core metrics such as funding, valuation, and revenue:

[Adept.ai](http://adept.ai/) has done impressively well in securing funding. Their successful raise of $350 million in a Series B funding round, led by well-known entities like General Catalyst and Spark Capital, reflects the strong investor confidence in their potential and strategic direction. 

Another noteworthy achievement is their revenue growth. [Adept.ai](http://adept.ai/) has managed to generate an impressive $75 million in revenue by 2024. Remember, they only started in 2022, so this growth within such a short time span is nothing short of remarkable. It clearly demonstrates their ability to efficiently scale their operations. [21]

But it isn't all about the numbers. [Adept.ai](http://adept.ai/)'s innovative approach sets them apart. Their development of an AI assistant that can interact with various software tools through natural language commands is a game-changer. This level of technological advancement really underlines their commitment to pushing the boundaries in the field of artificial intelligence. [23]

So, taking everything into account, [Adept.ai](http://adept.ai/)'s financial achievements and technological advancements have really put them on the map in the AI industry. They've shown impressive growth - their team has tripled in size from 25 to 75 members since 2023! This points to a promising future for the company. [23]
The company's innovative strategies, like training neural networks to carry out general tasks for enterprise clients and creating a natural language interface to access software tools like Adobe Photoshop and Airtable, have earned [Adept.ai](http://adept.ai/) a prominent spot in the AI industry. Moreover, their financial growth is quite impressive. They've reached $75 million in revenue in 2024. This is a testament to their success in scaling their operations and generating significant revenue within a short period. In fact, they started their journey in 2022 and have achieved so much in such a short time! [9]

### How is your company performing relative to competitors in the same field?

In the field of generative AI and machine learning, [Adept.ai](http://adept.ai/) holds its own against big players, among its 58 competitors. With $14.6 billion raised across 52 funding rounds by its competitors, [Adept.ai](http://adept.ai/) stands strong with its innovative approach in the industry. They're notably recognized for their AI assistant that can perform various tasks through text prompts, underscoring their commitment to advancing technology in the field of AI. Drawing parallels with the strategies of other AI-focused companies like [Anthropic](https://www.anthropic.com/claude), [DeepMind](https://deepmind.google/), and particularly [OpenAI](https://openai.com/) (where Sam Altman, the former boss of [Adept.ai](http://adept.ai/)'s founder, raised a reported $10 billion from Microsoft), [Adept.ai](http://adept.ai/) is also focused on fostering the growth of artificial general intelligence, or "AGI". This is a hypothetical AI system capable of making its own decisions without human input. However, there's a twist. [Adept.ai](http://adept.ai/)'s approach to AGI is more business-oriented and perhaps a bit less flashy, keeping humans firmly in control. [4][25][26].

## Recommendations

### If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

If I were to give advice to [Adept.ai](http://adept.ai/), I'd suggest they consider developing AI-powered solutions that can boost creativity and collaboration in the workplace. For example, they could create a virtual brainstorming platform that uses natural language processing and machine learning. This platform could help teams generate ideas, organize thoughts, and collaborate on projects in a more efficient and structured way.

In addition, [Adept.ai](http://adept.ai/) might want to venture into the space of AI-driven content creation tools. These tools could help users quickly and effectively produce high-quality written or visual content. By developing AI models that can assist with content ideation, drafting, editing, and design, [Adept.ai](http://adept.ai/) could cater to individuals and businesses looking to streamline their content creation processes and boost productivity.

Moreover, they could think about developing AI-powered project management tools that can seamlessly integrate with existing software platforms. These tools could help users manage tasks, deadlines, and resources more effectively, providing intelligent insights, automating repetitive tasks, and optimizing project workflows.

By focusing on products and services that enhance creativity, collaboration, content creation, and project management through AI, [Adept.ai](http://adept.ai/) can strengthen its position as a leader in the AI industry. Plus, it could cater to the evolving needs of businesses and individuals who are looking for innovative tech solutions to enhance productivity and efficiency. [24][25][26][27]

Finally, although Adept.ai is only a year old, they've already raised a significant amount of funding. The reason? Training robust AI models is costly. Therefore, making AI technologies and tools more accessible can benefit the broader community. 

>* As David Luan, one of the founders, said, they're still in the early stages. What they want to do now is, train powerful models that can do a lot. And over time, they'll figure out how to make them cheaper and smaller.* [19]

### Why do you think that offering this product or service would benefit the company?

Introducing AI-powered tools that boost creativity and teamwork could really benefit [Adept.ai](http://adept.ai/). Here's how:

First, imagine they create a virtual brainstorming platform powered by AI. Users could generate ideas, organize thoughts, and work together on projects more efficiently. By making the creative process more streamlined, businesses using these tools would see a boost in productivity and innovation. Sounds good, right?

Second, let's talk about content creation. There's a growing demand for tools that make creating high-quality content easier and quicker. If [Adept.ai](http://adept.ai/) were to expand into AI-driven content creation tools, they could help businesses save time and resources, while still maintaining high content quality. Think about it - help with content ideation, drafting, editing, and design all in one place. That's a game-changer!

And what about project management? If [Adept.ai](http://adept.ai/) developed AI-powered project management tools that integrate easily with existing software platforms, they could take their product range to the next level. These tools could help users manage tasks, deadlines, and resources more effectively by providing important insights and automating certain features. This would make project workflows so much smoother.

So, what's the big picture here? By focusing on AI-powered products and services that enhance creativity, collaboration, content creation, and project management, [Adept.ai](http://adept.ai/) could really stand out from the crowd as a one stop shop for all businesses. They could attract a wider customer base looking for innovative tech solutions and strengthen their position as a leader in the AI industry. Plus, it'd make interacting with technology a lot more natural and productive for everyone involved. [28][29][30][31]

### What technologies would this additional product or service utilize?

Tech tools and techniques [Adept.ai](http://adept.ai/) might use to bring their innovative AI solutions to life:

1. **Natural Language Processing (NLP)**

2. **Machine Learning Algorithms**

3. **Computer Vision**

4. **Cloud Computing Infrastructure**

5. **Metaflow and Argo on Kubernetes**

6. **Slurm**

7. **Containerization**

8. **CLI Tools**

By leveraging these technologies and integrating them effectively, [Adept.ai](http://adept.ai/) can create advanced AI solutions that boost creativity, teamwork, content creation, and project management. This robust tech stack paves the way for cutting-edge AI products that cater to the changing needs of businesses and individuals looking for innovative tech solutions. [10][15][16][32][33]

### Why are these technologies appropriate for your solution?

Here's why the technologies mentioned in the sources, such as natural language processing (NLP), machine learning, computer vision, cloud computing, Metaflow, Argo on Kubernetes, and containerization, are perfect for the AI-driven content creation and collaboration tool we're proposing for [Adept.ai](http://adept.ai/):

1. **Natural Language Processing (NLP)**: NLP is key for enabling the AI system to understand and respond to users using everyday language. It's like having a conversation with a human!
2. **Machine Learning Algorithms**: These are the brain behind the AI models. They power tasks like coming up with creative suggestions, automating processes, and providing smart insights.
3. **Computer Vision**: This tech allows the AI system to understand and process visual information. It's essential for creating and manipulating visual content.
4. **Cloud Computing Infrastructure**: This ensures [Adept.ai](http://adept.ai/)'s AI tools can be accessed on different devices and platforms. It's all about scalability and accessibility.
5. **Metaflow and Argo on Kubernetes**: These tools help fine-tune machine learning models, keep an eye on workflows, and manage different parts of the infrastructure effectively.
6. **Slurm**: [Adept.ai](http://adept.ai/) has used Slurm in the past for training and fine-tuning machine learning models. It's a handy tool for general high-performance computing workload management.
7. **Containerization**: This technique helps streamline the deployment process, manage dependencies efficiently, and ensures the AI applications can be used in different environments.
8. **CLI Tools**: [Adept.ai](http://adept.ai/) developed their own command-line tool to make launching jobs and getting job information easier.

By using these technologies in our proposed solution for [Adept.ai](http://adept.ai/)’s AI-driven content creation and collaboration platform, we can boost creativity, streamline processes, and provide innovative solutions that cater to businesses looking for advanced tech solutions for content marketing and collaboration. [16][29][30][34][35]

### Citations:

[1] [https://fourweekmba.com/adept-ai/#:~:text=Adept]

[2] [https://www.crunchbase.com/organization/adept-48e7]

[3] [https://www.cbinsights.com/company/adept-3/alternatives-competitors]

[4] [https://tracxn.com/d/companies/adept/__E1VU2MlFSZOIVSJlY1xthLHfe8LDWR9JnBTGy23cY-8/competitors]

[5] [https://www.cbinsights.com/company/inflection-ai/alternatives-competitors]

[6] [https://craft.co/adept-ai]

[7] [https://www.getapp.com/collaboration-software/a/adept/alternatives/]

[8] [https://techcrunch.com/2022/04/26/2304039/]

[9] [https://www.adept.ai]

[10] [https://www.adept.ai/blog/introducing-adept]

[11] [https://www.cbinsights.com/company/adept-3]

[12] [https://www.computerworld.com/article/3711620/essential-ai-reveals-funding-development-of-full-stack-ai-automation-tools.html]

[13] [https://www.adept.ai/blog/experiments]

[14] [https://fullstackai.co/tools/adept-ai/]

[15] [https://techcrunch.com/2022/04/26/2304039/]

[16] [https://outerbounds.com/blog/ml-at-adept-autodesk-epignosis/]

[17] [https://www.adept.ai/blog/act-1]

[18] [https://github.com/persimmon-ai-labs/adept-inference]

[19] [https://www.forbes.com/sites/kenrickcai/2023/03/14/adept-ai-startup-raises-350-million-series-b/?sh=b8abf122cc34]

[20] [https://www.adept-id.com/news/transparent-ai-model-performance/]

[21] [https://www.reuters.com/technology/adept-raises-350-mln-series-b-funding-2023-03-14/]

[22] [https://www.similarweb.com/website/adept.ai/]

[23] [https://getlatka.com/companies/adept.ai/team]

[24] [https://www.g2.com/products/adept-adept/competitors/alternatives]

[25] [https://aisupremacy.substack.com/p/six-more-companies-competing-with]

[26] [https://www.adept.ai/policies/privacy-policy]

[27] [https://www.adeptaisol.com]

[28] [https://www.forbes.com/sites/theyec/2023/05/30/14-benefits-and-drawbacks-of-using-ai-tools-to-write-business-content/?sh=58df50737177]

[29] [https://storychief.io/blog/ai-key-benefits]

[30] [https://valasys.com/8-benefits-of-content-automation/]

[31] [https://www.techtarget.com/whatis/feature/Pros-and-cons-of-AI-generated-content]

[32] [https://getkoala.com/companies/adept.ai]

[33] [https://theiotmagazine.com/generative-ai-tech-stack-building-the-future-of-autonomous-businesses-c44687891241]

[35] [https://www.simplilearn.com/tutorials/artificial-intelligence-tutorial/artificial-intelligence-applications]

[36] [https://huyenchip.com/2024/03/14/ai-oss.html?utm_source=tldrnewsletter]