## Sumedh Vizarsu Yeshwanth Krishna

I build AI systems end to end — ingestion, retrieval, evaluation, the service
around it, the deploy. Not just the data pipeline half. Most of what gets written
up stops at a notebook, and almost everything difficult starts after that.

The question I care about is whether a system actually works once it's running,
and how you'd know. So evals go in early, as an instrument for building the
thing, not as a report you write at the end. Chunk size, overlap, embedding
model, one retriever against another — all of it is measurable, and measuring it
is cheaper than arguing about it.

What I'm working toward is multi-agent orchestration: several agents handing work
to each other, with something in the middle deciding when an answer is good
enough to pass along. The self-correcting retrieval loop below — grade the
documents, rewrite the query, try again — is the smallest real version of that,
and it's where I'm building up from.

I also want to get underneath the application layer and into the research these
systems are built on, rather than only consuming the libraries.

### Projects

**[End2End-Document-Portal](https://github.com/v6y4k2s/End2End-Document-Portal)**
— FastAPI service for analyze / compare / chat over PDFs. LangChain LCEL over
FAISS, a config-driven loader that swaps Groq and Gemini without a code change,
structlog, custom exceptions, pytest. Docker, GitHub Actions, deployed on AWS ECS.

**[ecom_prod_assistant](https://github.com/v6y4k2s/ecom_prod_assistant)** —
product research assistant. Selenium scrape into AstraDB, contextual-compression
retrieval, LangGraph workflows including a self-correcting agentic RAG loop, an
MCP server and client, RAGAS for evaluation.

Both started as course builds. I keep my own commit history and rewrite the parts
I want to actually own, starting with retrieval — that's where the interesting
failures live. Each repo's README has the decisions and the numbers.

### Honest Work Studio

I host a podcast where I ask professionals and professors what their work
actually looks like now. Not career advice. Mostly specifics — what they do on a
Tuesday, which parts the AI tools changed, what they still do by hand and why.

It isn't a side thing. Sitting with someone and getting them to describe their
real workflow, in their own vocabulary, including the failure modes they can't
afford — that's the same skill as working out what to build for them. I've done a
version of it before: 25 discovery interviews at DEVCOM, where the job was to
find out what people needed before anyone wrote code.

### Before this

Graduate teaching assistant. Around 120 students and 40-plus capstone projects
graded. Most of the projects worked on demo day. The interesting question was
never that one — it was what happens when you ask someone what breaks if they
change one thing. About half could answer. That question is why I build the way
I do.

### Now

Looking for Forward Deployed Engineer, AI Solutions Engineer, and Applied AI
Engineer roles. Open to anywhere for the right team.

[LinkedIn](https://linkedin.com/in/sumedh-vyk) · [Honest Work Studio](https://instagram.com/hwspodcastt)
