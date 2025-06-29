Client: Chris Smith, [Jagex](Jagex "wikilink") <chris.smith@jagex.com>

Automated sentiment analysis tools are big business, but often
inaccurate - consider the difference between the tweets “practically the
best game I’ve ever played” and “hardly the best game I’ve ever played”,
which can get very similar scores. A key to future success will be far
more rapid training, collecting actual human responses to huge data
sets. Your task is to create an engaging interface for navigating and
coding millions of items from in-game chat and forum posts. Analysts
should start by typing a word, with the system responding by showing
frequency-weighted distributions of neighbouring words from all other
texts. Users should be able to move left and right, filter out texts
they are not interested in, and “deep-dive” to check meaning of
individual texts. The system should dynamically build a thesaurus,
learning which words might have similar meanings from context, and
adjusting the sentiment weighting of words and phrases. You’ll need to
use a super-fast index algorithm such as the Symmetric Compacted
Directed Acyclic Word Graph from Schulz & Mihov. The client will provide
a sanitized set of chat data from their own industry-leading games, and
would appreciate a dashboard-style visualisation of current status.