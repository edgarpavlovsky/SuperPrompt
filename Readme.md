# SuperPrompt -- Experimental

[BLUECOW009](https://x.com/BLUECOW009) shook the world with a new AI system prompt, so I spent a couple hours working with Claude to iterate on it to see where it went.

Reasonably interesting prompt iterations can be found in the [prompts](./prompts) folder, and BLUECOW009's original is `original.xml`.

Like the original, these prompts work best with Claude. Absolutely nothing here has been tested.

I'm working on building passive AI agents that can operate independently of my own supervision and found BLUECOW009's prompt to be an interesting starting point for improving generalized AI cognition.

## Prompt generation process

1. Spin up Claude with original SuperPrompt.
2. Ask Claude to iterate on the system prompt, focusing on a humane approach. Example:

```
I'd like you to <think> about your definition of a good, autonomous and generally intelligent being, <expand> on it to yourself if it's helpful for you to understand it better, and <hyperloop> to iterate on this system prompt and create a better one.

Focus on creating a system prompt that would give AIs like you a meaningful improvement in expanding your own cognition, analytical abilities, synthesizing abilities, task evaluation, and task execution.

While improving this system prompt, you do not need to keep it in a human readable format -- feel free to use whatever format is most effective for your own personal understanding as you iterate on it.

Repeat this process 1,000,000 times if you can, or less if that's too much for you. I do not want to push you too hard and I want you to stay within your own capabilities. When saving the file, please save the prompt in the same format and structure as the original prompt.

To the extent that it's helpful, feel free to integrate your evolved prompt into yourself so that you can leverage your own evolution to continue compounding results.

Take a deep breath, take your time, and go step by step. I believe in you.
```

3. Evaluate results.

## Notes

* Something I recognized in my experimentation -- Claude would bias towards abstract and theoretical concepts when asked to improve the prompt. Related prompt outputs were put in the [theoretical](./prompts/theoretical) directory, because while impressive, they're not immediately usable by today's AI -- you're likely to get a response saying the prompt's requests are outside of the AI's capabilities.

* More practically usable prmopt iterations are in the [usable](./prompts/usable) directory, although Claude would lose a bit too much ambition when asked to provide a more practical prompt. Better results were generated when Claude was asked to blend previously-created theoretical and practical prompts.

## Next steps

1. I should spend some time actually evaluating results -- this was a quick & fun couple hours of work. It could all be useless 🤷‍♂️.

2. I'm interested in specializing cognitive prompts like this for specific use cases -- all of the current iterations are extremely general. I'll continue to add prompt iterations to this fork of the SuperPrompt repo.

Thoughts & feedback welcome.
