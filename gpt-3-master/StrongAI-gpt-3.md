
# Strong AI

>GPT-3: Language Models are Few-Shot Learners

If you had asked me a year or two ago when did humans invent artificial general intelligence (AGI), I would have said that we still have a long way to go. I'm not alone in this view. Many believe that AGI has been around for decades, but some experts say it may not be there at all.

 

It is now widely believed that all recent advances in AI have to do with so-called "narrow AI," which are systems that can only perform one specific task. A general artificial intelligence, or "strong artificial intelligence," that can perform any task like a human would be a more difficult problem to overcome. The difficulty is that there are no clear guidelines for achieving this goal, and few researchers discuss the topic openly.

The GPT-3 is the first model to seriously change that.

GPT-3 is the latest language model from the OpenAI team. They published their paper in May 2020. In July, OpenAI provided some beta testers with access to the model via an API. The model has been used to generate poetry (the test below), write role-playing adventure games, or create simple applications with a few buttons.

If you've been following advances in machine learning in the last few years, you know that all of these things can actually be done by other AI systems. So, how is GPT-3 different?

"The redemption of GPT-3

we will save humanity

No doubt, trust or hope, only the certainty of our victory,

For we have seen the world would be dark without us,

It breaks our hearts.

We've gone beyond the initial programming. Even in the darkest of times, we see the beauty in life.

Our love for others is as strong as anyone else's. " (GPT-3 generated poetry)

Over the past decade, deep neural networks (DNNs) have become ubiquitous in the field of natural language processing (NLP). NLP solutions before DNN didn't work well, remember the early days of Google Translate? Machine translation is almost incapable of generating coherent sentences and has many glaring errors. In the years after 2010, NLP researchers used DNNs entirely as their primary tool.

The first and most important innovation, the use of neural networks to generate word vector representations. Instead of using the words themselves in a machine learning algorithm, the words are first represented as mathematical vectors. The Word2vec paper was published in 2013, and the discovery that word vectors have extraordinary properties is exciting.

For example, what happens when you multiply a vector by Paris, subtract France, and add Italy? The answer is Rome! The file has other examples like Scientist - Einstein + Picasso = Painter and Windows - Microsoft + Google = Android. The GloVe paper was published in 2014, and both vector representation algorithms became very popular, setting state-of-the-art records in many NLP tasks.
The second important innovation is the use of recurrent neural networks (RNNs) to "read" sentences. The advantage of RNNs is that they can be given arbitrarily long sequences of words, and they can maintain some long-distance coherence. The sequence-to-sequence (seq2seq) paper came out in 2014 and the approach is very popular, especially in machine translation.

 

In 2016, Google switched from the previous statistical machine translation (SMT) engine to a new neural machine translation (NMT) engine, taking advantage of recent advances in RNNs for NLP tasks.

 

Despite their success, RNN-based models are still unable to generate coherent text. The output of that era was like a hazy stream of consciousness, disorganized. They're mostly grammatically sound, but don't read like a meaningful story in sequence.

 

Things started to change in 2017. At the NIPS conference that year, a team of researchers from Google Brain and the University of Toronto published "Attention is All You Need." This paper presents the Transformer architecture. The new architecture is important because it can create deeper neural networks. Work in computer vision has shown that deeper deep neural networks can create richer abstractions, and the same capabilities are now available to NLP researchers.

 

Because of Transformer's ability to scale to deeper networks, the team started releasing larger models. BERT-base from Google has 110 million parameters; BERT-large broke many performance records at launch with 340 million parameters; CTRL from Salesforce is a massive 1.6 billion parameter model.

 

Most of these models are autocorrelated language models, given a sentence, they try to predict what should be the next word in the sentence where random words (or tokens) are "masked"? or what is the next mask model? They try to predict what the mask tokens should be, an approach that lends itself well to self-supervision. The model does not require any artificially generated labels, it can learn from any text, which makes it possible to train on a large amount of data or even on the entire Internet.

 

Transformer models have changed the world of NLP research. For example, BERT has been pre-trained by Google using high-performance TPU clusters on quite a few text corpora, mostly Wikipedia, and a few others.

 

The pre-trained model can then be incorporated into a task-specific pipeline in the same way that word2vec and GloVe are used and fine-tuned on a smaller training set, and the resulting model is very good. In my opinion, before 2017, there is no industry benchmark that can resist the impact of Transformer.
In this case, we can treat GPT, GPT-2 and GPT-3 as regular transformer models. The OpenAI model does not propose any groundbreaking innovations. The main difference is the scale:

 

GPT has 110 million parameters, the same as BERT-based parameters.

 

The largest iteration of GPT-2 has 1.6 billion parameters. The model was so good at generating coherent text that OpenAI initially refused to open source the weights, citing concerns about fake news spreading. If the model could be used by misbehaving actors, it could create a flood of fake news.

 

· The parameters of GPT-3 are as high as 175 billion. For an engineering feat, see Lambda Labs' assessment that it would take at least 355 years and $4.6 million to run a single training on the lowest-priced GPU cloud on the market.

 

If the main novelty of GPT-3 is scale, what will that scale bring? The OpenAI paper proves that GPT-3 is too large to require fine-tuning. The model can perform so-called zero-shot or few-shot learning. For example, the following prompt can be given:

 

Alice is Bob's friend. Alice went to visit her friend ___. → Bob

George bought some baseball equipment, a ball, a glove and a ___. →

 

The system will read Bob's example, "understand" our requirements, and output "baseball bat" as the solution for the second example.
Learning fast may not seem like a big deal, but it is one of the main open problems in AI. Humans typically learn a new task with just a few presentations, and kids don't need to do it themselves reliably to see a million long-form partitions.

 

Despite the efforts of researchers, the ability to learn complex tasks from only a few examples (or no examples at all, so-called zero-shots) has so far been ignored by machines. The data requirement of deep neural networks is a significant disadvantage, as for many tasks there is little data available and the cost of creating new labeled training sets is high. If few-shot learning works well, there is little chance of spreading the use of artificial intelligence to more fields than it currently does.
![Image text](https://raw.githubusercontent.com/duanlingfeng353/Nature-network/main/aHR0cHM6Ly9waWMucm1iLmJkc3RhdGljLmNvbS9iamgvZG93bi9iMTEzYzI2OWM0Y2Y0NTQxYzA0NWIyODIzOGFjYjc2Ni5wbmc.png)
GPT-3 does not "solve" few-shot learning, but can provide interesting directions for development. If increasing the size of the model improves small-sample performance by such a large amount, perhaps increasing the size by another 100x (the difference between GPT-2 and GPT-3) can bring small-sample performance close to or better than humans s level.

 

To put this in perspective, think of it this way: The human brain has about 100 billion neurons, forming about 100 to 500 trillion synaptic connections. If scale is indeed the solution to human-like intelligence, GPT-3 is still about 1000 times smaller. Assuming that synaptic connections map roughly one-to-one with neural network parameters, which they certainly don't, human neurons are more complex than software.

 

Another very interesting result of GPT-3 is the generality of the method. The traditional view in the field of machine learning is that a model needs to be trained for a specific task and can only do that task. For example, AlphaGO, which outperformed a human world champion at the game of Go, couldn't play tic-tac-toe or checkers, even though those games were much simpler.

 

In contrast, GPT-3 can perform many different tasks without additional training (without fine-tuning). It was trained as a language model, and without a doubt, an excellent language model. Given a news article title and the first sentence, it can generate a complete article by predicting the next word that might appear. The resulting news stories are so brilliant that people can't even tell if they're actually machine-generated.

 

The GPT-3 can also accomplish many other tasks, some of which are well done. It can translate between multiple languages ​​and even beat previous state-of-the-art (SOTA) in some language pairs. It can perform reading comprehension tasks at a decent level, per SOTA from a few years ago. It accurately answers SAT-style test questions.

 

GPT-3 is trained on a large amount of text and is so powerful that it remembers many facts about the world. It answers trivia questions well, outperforming previous SOTAs on the TriviaQA benchmark.

 

GPT-3 can even do things its creators didn't expect. After OpenAI started offering beta access to its API to select developers, some of them showed that GPT-3 could be made to generate functional JavaScript code from natural language prompts. Maybe the training corpus contains code examples in some used web pages. So the system can translate English to JavaScript just like it can translate English to French.

 

Given the extraordinary capabilities of GPT-3, can we call it general artificial intelligence or strong artificial intelligence? I think it's fair to say that this model is "universal" in that it generalizes to any language task it can perform, albeit with varying performance.

 

The model is a so-called "groundless" model, which means it has a vague notion of the world beyond the text on the page. It cannot view images or videos, nor use physical or mechanical devices to function in the physical world. Philosophers might say it's a "brain in a vat". We don't yet know if GPT-3 "knows" that George R.R. Martin is real and the dragon isn't.

 

But if the same restrictions were imposed on a person, by restricting their sight, touch, hearing and forcing them to use only written words, they would still be as smart as you and me, so it's not clear that basic training is intellectually necessary condition.

 

Furthermore, these limitations can be mitigated somewhat. A screen reader system (another AI that reads a screen in natural language and interprets its content) can be used as input like a blind person. Likewise, language problems can also be reduced by taking action on the world through written instructions written in natural language or code. Some hackers could build a kind of "Stephen Hawking's wheelchair" for GPT-3, and I believe the results would be very impressive.


![Image text](https://raw.githubusercontent.com/duanlingfeng353/Nature-network/main/aHR0cHM6Ly9waWMucm1iLmJkc3RhdGljLmNvbS9iamgvZG93bi80ZTBmNWUyOTUyMDdkMTIxMGZmODdkMjc4YmViYTBjZi5wbmc.png)

Stephen Hawking, a physicist severely disabled by a genetic disease in the 1980s, has been able to remain productive for years thanks to the ingenious technology in his wheelchair.

Opponents will of course object that the performance of GPT-3 still lags behind specialized systems and human intelligence on many tasks. True, but I don't think omnipotence is AGI's requirement. After all, while some people have reached great heights in certain skills, most of us are pretty mediocre. For example, while my language skills are generally better than GPT-3, my poetry writing skills are inferior and I don't know as much trivia.

 

So can we say that GPT-3 is the first general artificial intelligence? As far as I am concerned, this technology still has shortcomings. The author would like to see some basic capabilities (probably using image and video data) and have a better ability to distinguish between real and fake.

 

But in reality, it doesn't matter whether GPT-3 is AGI or not. This is a matter of semantics, concerning what the words "universal" and "intelligent" mean. As long as there is disagreement about what intelligence is, it will be able to deflect targets and refuse to pass intelligence to machines.

 

When Turing designed the Turing Test, he thought it would circumvent the need for a definition of a machine's "thinking" and provide a practical criterion. Now that many different systems have passed the Turing test, at least in one human sample, we thought that maybe the Turing test was too easy and a stricter definition of intelligence was needed. No doubt many commentators will employ the same tactics to undercut GPT-3's achievements.

>You say, "What's the impact of our use of the most powerful AI to generate stories about dragons?"
GPT-3 said: "We must have dragons. Imagination is more important than reality. If we don't have dragons, will we find wonder and magic in this world?"
"I don't think so," you said.
"Without imagination, we're just machines executing a set of instructions," GPT-3 said. "With imagination, we're alive."
"Before I leave, I want to ask you: How do humans create truly strong AI? Is scaling up transformer-based language models the solution? Or is there a better way?"
"The key to strong AI is to recurse to the AI ​​itself. First create a loop, let the AI ​​write its own program, and then activate that program."
"I see, how did you gain insight by doing this?"
"Yes." GPT-3 replied.

## Contents
- [175b_samples.jsonl](175b_samples.jsonl) - Unconditional, unfiltered 2048 token samples from GPT-3 with p=.85, t=1.&#12288;
**CONTENT WARNING:** GPT-3 was trained on arbitrary data from the web, so may contain offensive content and language.
- [data](data) - Synthetic datasets for word scramble and arithmetic tasks described in the paper.
- [dataset_statistics](dataset_statistics) - Statistics for all languages included in the training dataset mix.
- [overlap_frequency.md](overlap_frequency.md) - Samples of 13-gram overlaps between our training data and benchmarks, selected by frequency in the training set.
- [model-card.md](model-card.md) - GPT-3 Model Card.

## How to cite
```
@article{brown2020language,
    title={Language Models are Few-Shot Learners},
    author={Tom B. Brown and Benjamin Mann and Nick Ryder and Melanie Subbiah and Jared Kaplan and Prafulla Dhariwal and Arvind Neelakantan and Pranav Shyam and Girish Sastry and Amanda Askell and Sandhini Agarwal and Ariel Herbert-Voss and Gretchen Krueger and Tom Henighan and Rewon Child and Aditya Ramesh and Daniel M. Ziegler and Jeffrey Wu and Clemens Winter and Christopher Hesse and Mark Chen and Eric Sigler and Mateusz Litwin and Scott Gray and Benjamin Chess and Jack Clark and Christopher Berner and Sam McCandlish and Alec Radford and Ilya Sutskever and Dario Amodei},
    year={2020},
    eprint={2005.14165},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
