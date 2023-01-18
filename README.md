# Readme2Repo

## Welcome to Readme2Repo, a powerful tool that allows you to automate the process of creating new projects on GitHub by analyzing the README file of your existing repository.

Inspired by LangChain, Readme2Repo uses large language models to understand the structure and content of your README file, and generates all the necessary files for your project, including code, tests, and explanations. With Readme2Repo, you can easily create a new repository on GitHub with a properly defined "end-product" version of your README, without having to manually create each file.

To get started, simply load your repository from GitHub and pre-prompt Readme2Repo with the following information:

```
The following is the Readme to my project. I want you to give me a list of all of the files I will need for this project.
Then give me each and every file in a separate codeblock. Give only the file contents, any commentary or explanations
should go into the code as comments - in these comments give thorough explanations to why and how everything works.
Write tests based on the examples in the Readme, in the test code have a comment section detailing how to run all the tests
and output the results.
If the tests will fail, I will add them at the end of the Readme, make sure the code you provide deals and solves all those issues
Confirm with a short but detailed high level explanation and summery of the project and all it's capabilities, then start giving me
all the files.
```

### Readme2Repo will then analyze your README file, and generate all the necessary files for your project, including code, tests, and explanations. You can also fine-tune the prompt to suit your specific needs.


For more advanced features, checkout [GithubGPT](https://github.com/fire17/GithubGPT) which integrates everything with GitHub, making it seamless for developers to use. Other projects include [Repo2Repo](https://github.com/fire17/Repo2Repo) and [Issue2PR](https://github.com/fire17/Issue2PR) which are also integrated
