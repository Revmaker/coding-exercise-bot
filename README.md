**CarLabs Coding Exercise**

Jan 2017

**Introduction**

If you’re reading this, then you’re applying for a job at CarLabs. Thanks for your interest in joining our team! If you’ve made it this far, know that we already think you know your stuff; it’s just a matter of figuring out if your knowledge, style, and technique are a good fit for our somewhat-obscure needs.

**Purpose of this Exercise**

Our success as a company rests on our ability to execute and change direction quickly. So, in addition to gaining insight into your coding style and technique, we want to see how you respond to the unfamiliar.

**Instructions**

You will build a bot. This is intentionally open-ended, but many (free) resources and tutorials have been curated for you and are in the section below. You’ll make decisions such as:

* Should you code everything from scratch, start with a framework like Botkit, or use a more all-in-one GUI like API.ai?

* Will the frontend of your bot be Messenger, Slack, or JS/HTML/CSS?

* What will you show off? Will you tweak an already working bot and focus on the front end? Or will you show off your backend skills?

1. Clone this repo and rename this file to INSTRUCTIONS.md - we want to know that you use Git(Hub) effectively, and we’ll use your git history and commit messages to understand what you did

2. Create a README.md and use it to document instructions and explain why you made decisions

3. Get coding! The cloned repo should be all we need to understand what you did and why.

**Resources**

*Bot Tools / Frameworks*

[BotKit](https://github.com/howdyai/botkit)

[Init.ai](https://www.init.ai/)

[api.ai](https://api.ai/)

[MSFT Bot Framework](https://dev.botframework.com/?ref=stackshare)

[Recast.ai](https://recast.ai/)

[GoMix Bots](https://gomix.com/community/handy-bots)

*Content*

[WolframAlpha](http://products.wolframalpha.com/api/) - Knows a lot of facts. Siri uses to answer questions

[Sight Hound](https://www.sighthound.com/products/cloud) - Computer Image Recognition API, identify faces, landmarks, etc...

[Text Analysis API](https://developer.aylien.com/) - sentiment analysis, summarization, classification...

*Deployment*

[now](https://zeit.co/now/)

[Heroku](https://www.heroku.com/)

*Other*

[React Chat App](https://medium.com/front-end-hacking/react-webpack-and-horizon-quick-start-b9335c1ece53#.je2aeupxx)

[Slackbot tutorial](https://medium.com/@samhavens/building-somerset-d518ba284c49#.gb1y45wx1)

[Messenger bot with Wit tutorial](https://chatbotsmagazine.com/psst-time-to-jack-up-your-dumb-chat-bot-brain-using-wit-ai-aada04e8a303#.5gbrvihwn)

**Appendix I - Background on our Product**

CarLabs’ primary product is Carla - a bot that can talk about and give advice on car-related decisions. As such, we face many interesting challenges. An obvious one is how to understand and process natural language. However, another interesting challenge is designing a user interface and experience in a conversational setting. We believe the industry is in the early days of solving this problem.

**Appendix II - Our Stack**

CarLabs’ web applications are written in React (though some prototypes are still being ported from jQuery). However, as a messaging product, one of Carla’s front-ends is Messenger - a rigid, non-customizable platform (with the exception of webviews, a new addition). We also see Carla living, potentially, on Amazon Echo/Google Home.

Backends are written in Node v6, with Redis for caching, PostgreSQL for persistence, Flow for types (when needed), and Hapi or Express depending on the size of the application. Tests are written in Elixir. CarLabs’ data pipeline is a PHP7/MySQL application, with services written in PHP, Python, and R.

Parts of our stack are Dockerized, and we continue to move in that direction. In production, we are currently all-AWS, but since we won a Joyent competition, we are testing out their cloud as well.
