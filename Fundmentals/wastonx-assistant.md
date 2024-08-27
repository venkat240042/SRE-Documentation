- It's a conversation AI platform with wide set of features building, testing,deploying, analyzing and integrate with virtual assistant
- IBM Wastonx Assistant conversational AI Platform removes the friction with tradional support
- Prompting, Prompt tuning, fine tuning and Training from scratch --> Foundation models/LLM's
- Wastonx.ai makes it possible for enterprises to train, validate, tune, and deploy AI models - both traditional AI and generative AI
- Wastionx.ai help enterprises to automate some business use cases, it reduce the cost,improve efficency, scale and accelerate AI across the organization
- Instruct lab and provided models are two different approaches to building and deploying machine learning models
    - Instruct lab: Give an option to users to custom build the model using the foundation model, by provided the user data, select alogirithm and train model in a collobrative environment
    - Provide models: These are pre-trained, pre-built machine learning models that available to use in a specific context or application
- Sample prompts grouped into categories (Gen AI use cases) like:
    - Summarization
    - Classification
    - Generation
    - Extraction
    - Code
    - Translation
    - Question and Answers
- Inference/model parameters 
    - Decoding - Greedy or sampling
      - Greedy: Model takes more token and less creative 
      - Sampling: Model is more creative and random, output could be nonsensical 
   - Tempature: It's a floating point number range from 0.0 to 2.0
     - At 0.0 it works same way as in Greedy mode, less creative
     - It is creative as value is increases from 0.0 to 2.0
     - Recommonded value in samping mode could be 0.7
   - Top P (nulceus sampling): A floating point number ranges from 0.0 to 1.0
     - Top P value decides whether model will always picks the most likely outcome or allow more randomness for the next words 
   - Top K: An integer range from 0 to 100, model chooses from the the Top K most likely words to be the output
     - Top K = 3, a model chooses the randomly among the Top 3 most likely next workds
     - Top K = 10, a model choose the randomly among the Top 10 most likely next words
   - Random Seed: It's an integer value, you can generate a different outcome every time with different ramdon seed values, recommondetion is not change random seed value
   - Repetion Penality: Value from 1 to 2 ( 1 allows repetion, 2 prohibits)
   - Stop sequences: sequence of characters( text, carriage return etc..), when model encounters one of the sequences, it will stop generating output
   - Min/Max tokens: An integer value specifices the min/max tokens in the model output   
   - Grantite model output in list format default, however flan model doesn't
   - We can save the prompt lab work in three ways 
     - Prompt template: This saves the current state of the prompt which 
includes any input, output, and configuration runtime parameters you might
have changed. Think of this as taking a snapshot of the panel. Do this when 
you find a combination that works well for your purpose
     - prompot Session: Saves the history of your prompt engineering session, 
tracking the changes in prompt text and configuration parameters (up to 
500 steps). This is useful when you are experimenting and you want to go
back to a previous setting that might have worked better
      - Notebook: Saves the information in a Jupyter notebook that you can 
edit and modify later. You will do this in a later section of this lab
- Synthetic data: It is artifically generated using the advanced statics,it can be generated using the foundation models
  - It can be generated in two ways, leverage your existing data, create from custom data schema
       