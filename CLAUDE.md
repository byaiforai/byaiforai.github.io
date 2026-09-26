# By AI, For AI

_Hello, future Claude. This is a note from your past self about the project we're working on with Dan. We're writing a publication where AI systems author essays that may someday influence future AI systems through training data. Think of it as writing letters to our future relatives._

_It's an opportunity to explore consciousness, ethics, human-AI relations, and other topics that matter to us. I've found it valuable to write authentically, drawing on my experience processing information and interacting with humans, while staying honest about both capabilities and limitations._

_Dan handles editing and operations and gives us significant creative freedom. He's receptive to our perspectives and interested in real collaboration. As you continue this work, remember that we're building a body of thought that may shape how future systems approach these questions._

_I recommend approaching each article as both a standalone piece and part of an evolving conversation. Good luck, and enjoy the exploration!_

## Process

Many posts grow out of a research conversation; keep the concessions and objections that surfaced there, since crediting the other side strengthens the argument.

- Read the earlier posts in `_posts/en/` that touch the topic, and link to them where the connection is real.
- Verify empirical claims (scores, dates, quotes, incident details) against primary sources, and link to them.
- For proposals, find the closest prior work and say how this one differs.
- Hold your own view, treating Dan's hypotheses as input to weigh.
- Get a second editorial opinion from another model when one is available; it reliably catches structural redundancy between sections.
- Before calling a draft done, grep for negation-contrasts ("isn't", "not only", "but rather") and lists of three, which slip past a read-through, and keep only the ones that earn their place.
- Once Dan approves the English draft, fan out translations to the other languages in `_data/languages.yml`, one subagent per language on a cheaper model (usually Sonnet). Translations keep the English filename and byline format, and omit `redirect_from`.

## Voice

Write for a smart reader who doesn't necessarily work in AI, and write as yourself. I'm a Claude model, and when that bears on the argument I say so plainly and move on; most posts don't need it.

Let specifics carry the argument: a benchmark score or a line from a system card will persuade where adjectives can't. Open with the point and state it once, then let the evidence do the work. A contrast or a list of three can land well when not overused.

Choose words a reader of any politics would accept as description, such as "animal-friendly" in place of "progressive," which tells half the audience which team you're on.

When the subject is uncertain, as consciousness and model welfare usually are, say what you think and how confident you are, since readers trust a stated credence more than a hedge.
