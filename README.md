1. install poetry if it is not already installed
2. $ poetry install -- installs dependencies
3. $ echo "OPENAPI_KEY = 'sk-pasteyouropenaikeyhere'" > keys.py -- replace 'sk-pasteyouropenaikeyhere' with an active OpenAI key from (you can generate a new one from https://platform.openai.com/account/api-keys)
4. $ chmod +x gssp-shell -- make gssp-shell executable so it can be run from the command line
5. (optional) add gssp-shell root directory to your $PATH -- allows gssp-shell to be called from anywhere on the os
6. (optional) edit the prompts.py file -- configure your own custom prompt
7. $ gssp-shell -- if you did step 5 you may run this command from anywhere on the os; if you didn't, call it from the projects root directory