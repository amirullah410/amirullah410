# Amir Ullah

Software developer in London, moving into AI engineering. For three years I've built and run production apps end to end: Flutter and React Native on the front, Python APIs, MySQL and AWS behind them. The part I now want to do full time is the part I've enjoyed most: putting language models to work on real operational data, in a way people can trust.

## AI work I've shipped

**Delivery reporting with the OpenAI API (production, at F.H. Brundle)**
SQL pulls delivery data for 30+ drivers doing around 200 drops a day. The model returns structured JSON, which I turn into reports for branch managers: planned vs actual times, missing data and repeat issues.
- The model only ever sees anonymised IDs; names are matched back afterwards.
- I checked its findings against my own analysis before anyone relied on it. It picked out the same drivers running late on the same routes each week.

**Goal Pro (personal project, private repo)**
A personal finance app for iOS: React Native, Supabase and the Claude API.
- Claude categorises transactions from merchant names only. Amounts, dates and people's names are never sent.
- Code does the arithmetic and decides whether a savings goal is achievable; the model only writes the explanation and must not contradict it.
- AI output is stored and reused, with a hard monthly cap on calls.
- Row-level security on every table, with tests proving one user can't read another's data.

## Other things I've built

- **Customer eCommerce app** (Flutter, Python/Tornado, MySQL, Worldpay): the company's first app. £500k in its first four months, 10,000+ downloads, rated 5.0 on Google Play.
- **Offline-first driver app** (React Native, AWS Lambda and SQS): replaced a browser tool that lost proof-of-delivery records. No delivery record lost since launch.
- **Data** (MySQL): a database of 500,000+ customers and over a million orders, with stored procedures and triggers that cut manual work by around 40%.

## Skills

- **AI:** OpenAI and Claude APIs, prompt design, structured JSON outputs, data anonymisation, checking model output against ground truth
- **Languages:** Python, SQL, TypeScript/JavaScript, Dart
- **Backend and data:** Tornado, Pandas, REST APIs, MySQL, Postgres (Supabase)
- **Mobile:** Flutter, React Native
- **Cloud and DevOps:** AWS (Lambda, SQS), Docker, GitHub Actions, CI/CD, automated testing

## What I'm looking for

An AI engineering role where I can build LLM features into real products and own them through to production.

## Contact

- Email: [amir-ullah41@outlook.com](mailto:amir-ullah41@outlook.com)
- LinkedIn: [linkedin.com/in/amir41](https://www.linkedin.com/in/amir41)
