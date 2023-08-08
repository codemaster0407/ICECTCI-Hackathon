# ICECTCI-Hackathon

# PROBLEM STATEMENT

Problem Statement 3– Natural language processing
 Title: AI-Assisted Learning for NVIDIA SDKs and Toolkits
 Problem Statement: Develop an AI-powered language model (LLM) that assists users in
 understanding and effectively using various NVIDIA SDKs (Software Development Kits) and
 toolkits. The objective of this hackathon is to create an interactive and user-friendly platform
 that provides comprehensive information, examples, and guidance on NVIDIA's SDKs and
 toolkits. By leveraging the power of language models and NVIDIA toolkits, participants aim to
 simplify the learning curve for developers and empower them to utilize NVIDIA's technologies
 more efficiently.
 Note that you can either use a pre-trained model and modify it according to the task or you
 can develop one from scratch.
 To provide you with an idea, here are some illustrative inquiries that can be directed towards
 the LLM. When posed with these questions or queries, the LLM should respond with
 answers in and around the following context:
 Question
 Expected Response
 1. What is the NVIDIA CUDA Toolkit? The CUDA Toolkit from NVIDIA provides everything
 you need to develop GPU-accelerated applications.
 The CUDAToolkit includes GPU-accelerated libraries,
 a
 compiler, development tools and the CUDA runtime.
 2. How can I install the
 NVIDIA CUDAToolkit on
 Windows?
 The setup of CUDA development tools on a system
 running the appropriate version of Windows consists of a
 few simple steps:
 1.Verify the system has a CUDA-capable GPU.
 2. Download the NVIDIA CUDA Toolkit.
 3. Install the NVIDIA CUDA Toolkit.
 4.Test that the installed software runs correctly and
 communicates with the hardware.
3.Whatarethekeyfeaturesof
 theNVIDIATensorRT?
 NVIDIA®TensorRT™,anSDKforhigh-performance
 deeplearninginference,includesadeeplearning
 inferenceoptimizerandruntimethatdeliverslow
 latencyandhighthroughputforinference
 applications.SomekeyfeaturesofTensorRTinclude:-NVIDIATensorRT-basedapplicationsperformup
 to36XfasterthanCPU-onlyplatformsduring
 inference,enablingyoutooptimizeneuralnetwork
 models-TensorRT,builtontheNVIDIACUDA®
 parallelprogrammingmodel,enablesyoutooptimize
 inferenceusingtechniquessuchasquantization,layer
 andtensorfusion,kerneltuning,andotherson
 NVIDIAGPUs.-Formoreinformationonecan
 checkout
 [https://developer.nvidia.com/tensorrt]
 (https://developer.nvidia.com/tensorrt)
 4Whatisthedifferencebetween
 NVIDIA'sBioMegatronandMegatron
 530BLLM?
 BioMegatronfocusesspecificallyonbiomedicalNLP
 tasksandhasbeentrainedonrelevantbiomedicaldata,
 Megatron530BLLMisamoregeneral-purpose
 languagemodeltrainedonawidevarietyoftextfrom
 differentdomains.Thechoicebetweenthetwomodels
 dependsonthespecificrequirementsanddomainofyour
 NLPtask..
 DatasetfortheChallenge:
 TobuildanAI-poweredlanguagemodel(LLM)forassistingusersinunderstanding
 andeffectivelyusingvariousNVIDIASDKsandtoolkits,thedatasetcanbe
 composedofthefollowingsources:
 1. NVIDIADocumentation:Theprimarydatasourcewouldbetheextensive
 documentationprovidedbyNVIDIAfortheirSDKsandtoolkits.Thisdocumentation
 containscomprehensiveinformation,usageguidelines,examples,andtroubleshooting
 detailsforeachSDKandtoolkit.Itcoverstopicssuchasinstallation,APIreferences,
 samplecode,andbestpractices.Link:https://docs.nvidia.com/
 2. InternetArticlesandTutorials:Alongsidetheofficialdocumentation,incorporating
 relevantarticlesandtutorialsfromtheinternetcanenhancethedataset.Blogposts,
 tutorials,andguidesauthoredbydevelopersandtechnologyenthusiastsprovide
 real-worldinsights,usecases,andtipsforeffectivelyutilizingNVIDIASDKsand
 toolkits.
 3. CommunityForumsandQ&APlatforms:CommunityforumslikeNVIDIA
 DeveloperForums,question-and-answerplatformssuchasStackOverflow,and
 discussionsonGitHubcanserveasvaluablesourcesofinformation.Theseplatforms
 hostdiscussions,providesolutionstocommonissues,andaddressuserqueriesrelated
 toNVIDIASDKsandtoolkits.
 4. Incorporatingdatafromthesesourcesenablesthelanguagemodeltoofferpractical
guidance and address specific user concerns. Link: https://forums.developer.nvidia.com
 By combining the NVIDIA documentation with curated internet articles and insights from
 community forums, the language model can be trained to effectively respond to a wide range of
 user queries related to NVIDIA SDKs and toolkits. This approach ensures the model is
 up-to-date, incorporating information from official sources as well as the broader developer
 community
Evaluation Criteria: These below factors/criteria will be evaluated by a review panel.
 1. Authenticity: Assessing the correctness of the information provided by the
 language model in response to user queries related to NVIDIA SDKs and
 toolkits.
 2. Comprehensiveness: Evaluating the extent to which the language model
 provides complete and thorough information on NVIDIA's SDKs and toolkits,
 covering key features, APIs, usage guidelines, and best practices.
 3. Contextual Understanding: Evaluating the model's comprehension of user queries
 and its ability to provide relevant responses and explanations tailored to the specific
 SDKor toolkit being discussed.
 4. Consistency: Same or similar prompts should generate identical or almost
 identical responses related to NVIDIA SDKs and toolkits.
 5. Speed: The speed at which the model can produce results is important, especially
 when it needs to be deployed for critical use cases.
 6. GrammarandReadability: The model must generate language in a readable
 format. Ensuring proper grammar and sentence structure is essential.
 7. Interactive Assistance: Assessing the model's interactivity and responsiveness
 in assisting users with their queries, offering step-by-step guidance, code
 snippets, and troubleshooting tips.
 By considering these aspects, the language model can be evaluated holistically, ensuring they
 meet the needs of users and developers utilizing NVIDIA's SDKs and toolkits.
 Submission instructions:
 1. Submission Components: Submissions must include the following components:
 a. Trained Model: The language model trained for providing
 information on
NVIDIA SDKs and toolkits.
 b. Training Process Details: A detailed document (A pdf file preferably)
 outlining the steps taken in data collection, data preprocessing, model
 architecture design, model training, hyperparameter tuning and training
 time/duration.
 c. Testing Notebook: Include a notebook (.ipynb) with clear instructions on
 how to load the model and how to ask a query to test our hold-out test dataset.
 Ensure the notebook is executable and produces accurate results when run. We
 will execute them to verify their functionality. Failure to run these notebooks
 successfully will lead to disqualification of the submission.
 d. Example Responses: A collection of example responses generated by your
 model, showcasing its capabilities in providing informative and accurate
 information related to NVIDIA SDKs and toolkits. Provide necessary
 screenshots.
 e. Report: One page report/summary of the work should be submitted in the
 provided template

