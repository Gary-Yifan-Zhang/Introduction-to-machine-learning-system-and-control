**Group 1. Image-based disease detection. Use of deep learning to aid breast cancer detection in images from mammography screening.**

In several countries, people with female as their legal gender are called to screening for early detection of breast cancer. In general, this means that radiologists examine a large amount of the images (usually mammograms) to find anomalies that could be growing cancers. Yet, it is argued that AI systems, such as deep learning based image analysis, can detect cancer with a similar performance as that of a radiologists. The question now is what the risks are and under what circumstances such a system can be used to improve medical screening. 

当涉及到AI伦理问题时，有一些重要的问题需要考虑：

1. 公平性和偏见：AI系统的设计和训练应该避免对不同群体的歧视和偏见。这包括避免性别、种族、年龄等方面的偏见。
2. 隐私和数据保护：AI系统应该确保个人数据的安全和隐私。数据收集、存储和使用应该符合相关的法律和道德准则。
3. 透明度和可解释性：AI系统应该能够解释其决策和行为的原因。这对于用户和相关利益相关者来说是重要的，特别是在涉及关键决策和影响个人生活的情况下。
4. 责任和问责制：开发和使用AI系统的个人和组织应该对其行为和后果负责。这包括确保AI系统的安全性和可靠性，以及处理由其造成的任何损害。
5. 社会影响和公共利益：AI系统的设计和应用应该有助于社会的福祉和公共利益。这意味着需要考虑其潜在的社会影响，包括就业、社会不平等和道德困境等方面。

以下是一些关于AI伦理的链接，供进一步阅读：

1. 《人工智能伦理原则》 - 来自OpenAI的一份伦理原则，旨在指导人工智能的研究和开发：https://openai.com/charter/#values



**Each group should:**

1. Write ==a short-paper (2-3 pages==, excluding references).  The deadline for submitting your paper is ==October 17, at 11.00 (AM)==, to enable the other group to read it prior to presentation.
2. Present your case and results at the seminar on ==October 19 ==. Each group has ==8-10 min for their presentation==.
3. Read and review another group’s paper. You don't have to submit this review in written form, it is examined by your group asking questions and reflecting after the presentation by the group you are reviewing.

**In the paper (2-3 pages, excluding references) you should:**

1. Introduce the case
2. Give examples if you find them
3. Make an analysis based on the ethics lectures and description below.

**We want you to focus on three common themes:** 

- ==Accountability== – For example: How should responsibilities best be distributed amongst different actors involved? If something goes wrong, who is to blame? What kinds of safety measures should be in place and who should ensure that nothing goes wrong?
- ==Fairness== – For example: What are the risks of unfair treatment? How can fairness be safeguarded?
- ==Transparency== – For example: What level or type of transparency or explainability, and for whom, would be fitting for this case? Who needs what information? Who should understand how a prediction works – a customer, a doctor, an operator, the developer, etc?

**These aspects can be approached in terms of:**

- *roles*, as in *who* are involved or affected; persons or user of various sorts, companies, authorities, or other stakeholders; 
- *context*, how is the context of use relevant
- *stakes*, that is, the magnitude of potential risks

Describe:
	• Roles
	• Context
	• Stakes
	• Pay attention to processes (data, training, model dev., validations, implementation，use, impact, risk)
Focus on three common themes:
	• Accountability
	• Fairness
	• Transparency

对于radiology来说，有什么特殊的？

AI in radiology与其他ai的应用在道德方面有什么不同？

AI在放射学中的应用与其他领域的AI应用在道德方面存在一些不同之处。放射学中的AI系统需要处理医疗数据，这些数据涉及患者的隐私和敏感信息，因此数据的安全和保护变得尤为重要。与其他领域的AI应用相比，放射学中的AI系统需要更加注重数据隐私保护和共享的道德问题。

另外，放射学中的AI系统直接应用于医疗决策，对患者的健康和生命产生直接的影响。因此，在放射学中应用AI系统时，需要更加关注道德准则和伦理原则，确保向患者提供合理和可信的结果。此外，由于放射学中的AI系统可能会面临数据选择偏差和转移的问题，因此需要更加谨慎地评估和处理数据的可靠性和可用性，以避免系统在特定人群中产生偏见[4]。

综上所述，与其他领域的AI应用相比，AI在放射学中的应用在数据隐私保护和医疗道德方面具有更高的道德要求。放射学中的AI系统需要更加注重患者的隐私权益，并确保提供可靠、准确和公正的医疗决策。



针对乳腺癌的检测，你认为ai在放射学的数据方面有什么特殊的吗？

在放射学乳腺癌检测方面，AI的数据方面存在特殊问题。文档中提到了数据偏倚（data bias）和数据转移（data shift）的问题[4]。因为DL技术在乳腺癌检测中利用数据进行训练，而训练数据可能来自发达国家，并不完全代表农村地区的情况。这就限制了这些模型在资源相对匮乏、专家稀缺、数据不足的地区的可用性和适用性。这种情况下，只有拥有足够资源（包括技术、专家和财富）和大量数据访问权限的人才能使用DL模型，同时限制了在农村地区出现的数据偏倚和转移，使得模型在这些地区的需求更加迫切，呈现出重要的道德和伦理困境。

对于贫困人口的？中东，非洲数据采集？

文档还提到了数据隐私和共享的道德问题[5a][5b]。虽然数据的匿名化是保护患者隐私权的重要步骤，但随着AI等技术的不断进步，重新识别数据变得越发容易，使得数据的来源可以被轻易确认。此外，数据共享方面的挑战还包括由控制社交媒体和医疗AI系统的大型数据公司的能力，他们可以从智能手机等日常使用工具收集数据，并与社交媒体的数据进行匹配。由于数据的经济价值，这可能被认为是一种不道德的数据使用方式。因此，需要开发新的隐私增强技