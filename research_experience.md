I currently contribute part time to the the EleutherAI Eliciting Latent Knowledge Project to multiply empirical research on deception.
[See  my contributions here. I’ve mostly help in engineering -e.g. fixing broken reporters, implementing better tests and checks.](https://github.com/EleutherAI/elk/pulls?q=is%3Apr+is%3Aclosed+author%3Athejaminator)

I created ConditionMe two months ago to [help AI safety researchers explore conditional / decision transformer reinforcement learning.](https://github.com/thejaminator/conditionme)
Conditioning on discrete tokens is simple, such as in [Pretraining Language Models with Human Preferences](https://arxiv.org/abs/2302.08582).
But conditioning on scalar rewards is more tricky. There may some implications of scalar rewards - e.g. encoding an out-of-distribution reward ala decision transformers that can affect the model's performance.
My package figures out all the changes in padding / position ids / attention masks to help conditioning on scalar rewards for pretrained LLMs. 

I work as a Senior Machine Learning Engineer in my current company. In particular, I’ve built a labelling pipeline to build a model that was truthful and interesting to users, using decision transformer style techniques. I’ve used active learning to increase the efficiency of our labelling pipeline to collect reward feedback for our models.
You can see examples of decision transformer style finetuning using OpenAI's api in [Attempts to align Language Models by putting the reward in the prompt](https://github.com/thejaminator/prompt_reward_rl/blob/main/documentation/main_page.md) which uses the OpenAI finetuning API.
