# A Paper Reading Workflow: From Zotero to Obsidian

*By Devon Hill (devon.hill@usu.edu)*

This is the workflow I use to move a paper from "something I should probably read" to "something I actually understand and can build on." It spans two tools — **Zotero** (for collecting, tagging, and annotating) and **Obsidian** (for connecting ideas and writing my own notes) — and it has three stages that map to how deeply I engage with a given paper.

A quick note on philosophy: not every paper deserves the same amount of effort. Most papers only ever make it through Stage 1 or 2, and that's the point. I reserve the deep, hours-long Stage 3 read for the handful of papers that are genuinely central to my research. Treating every paper as a full read is the fastest way to burn out and fall behind.

> **A few of the steps below are purely my own personal conventions.** I've flagged those so you can take or leave them. The overall three-stage structure may be the part worth borrowing.

---

## Stage 1 — Zotero: Familiarize and Categorize

The goal of this stage is to get the paper into my library in a *findable* state without yet committing to reading it deeply. I focus on the abstract, the metadata, and tags.

I load the paper into my main library and leave it unfiled — that "unfiled" state acts as my staging area.

> A word of warning from experience: keep this staging pile small. When I added papers indiscriminately, I ended up with an overwhelming heap I never touched — not necessarily because the papers were irrelevant, but because there were simply too many to face. If a paper isn't worth at least a tag explaining why I saved it, it probably isn't worth saving.

My Stage 1 checklist:

1. *(Personal convention)* Rename the primary PDF attachment to **"main"**. The file-type icon already tells me it's a PDF, so I use the title to mark the one attachment where all my annotations and notes will live. This makes my primary attachments trivial to find later.
2. *(Personal convention)* Put the title in **sentence case**, with a short list of proper nouns I always capitalize (place names, etc.). This is just an APA-style consistency preference of mine — adopt it only if consistent casing matters to you.
3. Fix the abstract text. Automated imports sometimes mangle it, so I clean it up here.
4. **Add tags** while I highlight the abstract (see the tagging and abstract sections below).
5. *(Personal convention)* Move the paper into a **"Tagged"** folder so I know it has cleared this stage.

### Tagging — the most important habit in this whole workflow

> **Key tip: keep a running, written list of every tag you use.** This single habit is what makes a tag system actually work. Without it, you silently create `#groundwater`, `#ground-water`, and `#GW` for the same concept, and your tags stop being a reliable way to find things. I maintain a master list with a one-line definition of what each tag means and when I apply it.

I organize my tags into **five broad groups**, numbered 0–4. Numbering them keeps related tags together and gives me a mental checklist when I'm tagging a new paper:

- **0 — General subject area.** The broad domain of the paper (e.g., cold-regions, karst, groundwater–surface-water interaction, ecohydrology). Deliberately broad.
- **1 — Site description.** Everything about *where* the study took place: climate zone, permafrost type, ecosystem/vegetation, named study areas, and notable landforms. These let me build a library of "examples of research in environment X."
- **2 — Paper type.** Two flavors: the journal's own categories (article, review, letter, comment) and a research-method classification I borrowed from a professor (model-based, field-based, lab-based, data-based, theory-based, etc.).
- **3 — Specific topics.** The granular, content-level tags — the actual phenomena, methods, and concepts a paper is about. This group grows the fastest. I try to favor tags that map to *questions I might later ask* (e.g., "water-tracks" + "hillslope-hydrology") rather than tags that only help with sorting.
- **4 — Status.** Workflow markers like "read" and "summarized" that record how far I've taken a paper.

> **Tip — turn off Zotero's automatic tag import.** Many papers arrive with dozens of publisher-supplied keyword tags, which flood your library (and, if you sync to Obsidian, pollute that too) with tags you'll never use. You can stop this: in Zotero go to **Settings → General** and uncheck **"Automatically tag items with keywords and subject headings."** From then on you control the tag vocabulary yourself, which is exactly what the running tag list above depends on.
>
> *(If you've already imported a library full of automatic tags, you can bulk-remove them from the tag selector in the bottom-left pane: right-click the filter and choose "Delete Automatic Tags in This Library.")*

### Highlighting the abstract

When I add a paper, I split the abstract into sentences and color-code each one by the role it plays. At minimum I use a **three-part partition**:

- **Introduction / background** — the setup and motivation
- **Methods** — what they did
- **Conclusion / results** — what they found

This makes the structure of the abstract visible at a glance and trains my eye to see how a well-built abstract is assembled.

> You don't have to stop at three parts. A typical abstract also contains a **gap** (the specific shortcoming in prior work the paper addresses) and **implications** (why the findings matter), and you may find it useful to highlight those separately. The right granularity is whatever helps *you* parse an abstract quickly — pick a scheme and apply it consistently.

I use a consistent color for each role. A simple, durable convention is something like: gray = introduction, orange = methods, magenta = conclusion. The specific colors matter far less than using the *same* colors every time.

---

## Stage 2 — Obsidian: Connect and Question

Stage 2 is where a paper stops being an isolated PDF and becomes connected to the rest of what I know. The goal is to capture the paper's contribution and the questions it raises, in my own note system.

1. **Skim for the contribution.** I glance at the conclusions and the major figures so I have a working idea of what the paper actually contributes.
2. **Mark key points.** In the PDF I underline (in green) any clear contributions or key points I want to surface later in my notes.
3. **Create the Obsidian note.** I push the paper into Obsidian so it has a home where I can link it to related ideas.

   > *I use a Zotero-to-Obsidian import setup to generate these notes automatically from the paper's metadata, annotations, and my highlights. The mechanics of getting annotations across are covered in the group's blog post, [A Zotero-to-Obsidian Workflow](https://hydroaggie.github.io/blog/2023/A-Zotero-to-Obsidian-Workflow/); the rest of this section is what I do once the note exists.*

4. **Record the contribution.** At a minimum, I write down what I can already tell is the paper's contribution.
5. **Answer my open questions fast.** At this stage I usually have a few specific questions about the paper. A great shortcut is to load the PDF into [NotebookLM](https://notebooklm.google.com/) and just ask — it does a good job of pulling targeted answers straight from the source. (I keep my NotebookLM library sorted so I can quickly check whether I've already loaded a given paper, and I'm starting to link the NotebookLM page back into the paper's Obsidian note.)
6. **Go one level deeper on something.** I pick one aspect to understand better — the study site, the methods, the modeling approach, or how it connects to other work.

   > **Tip: if you're deciding whether a paper is worth a full read, start with the discussion.** I picked this up from a panel of researchers: they read the discussion early because that's where you can see how developed the authors' thinking is and how well they connect their work to the broader literature.
   >
   > A caveat, though — discussions are hit-and-miss. **Some papers have no discussion section at all** (or fold it into the results), and among those that do, **not all of them open with a tidy summary of the results.** So this is a useful heuristic, not a guarantee; adapt to whatever structure the paper actually has.

---

## Stage 3 — The Full Read (and a Written Summary)

This stage is reserved for the small number of papers that are foundational to my work — the ones I'll read and reread for hours. Because I'm investing so much time in them, I write a **one-page summary** of each. If I don't, most of that effort evaporates over the following months. I save these summaries alongside the paper (I attach a PDF of the summary back to the Zotero record so it travels with the paper).

**Reading method.** Before writing the summary, I read with an outline. In the paper's Obsidian note I lay out the paper's own section headings (Methods, Results, etc.) and, as I read, jot a numbered note for each paragraph's main point under the relevant heading. This keeps me oriented — I can always see where the author is going — and surfaces the key points as I go.

### A template for the summary itself

The summary structure I use comes from guidance by Dr. Dennis Newell, which I've found to be an excellent, reusable framework for reading *and* writing about a paper. The core idea: **write the summary for your future self**, so you can refer back to it instead of rereading the whole paper. That means understanding the paper's *organization* — make an outline — and summarizing only the most important statements as the authors build their argument from beginning to end.

A good summary explicitly answers:

1. **Purpose.** What is the broad purpose of the paper, the problem it addresses, and its specific goal? And what *type* of research is it — qualitative or quantitative; field-, lab-, or model-based; empirical, theoretical, or philosophical; a research paper or a review?
2. **Methods & data.** What are the data? What are the research design and methods? What did they actually *do*?
3. **Results & conclusions.** What are the main results, and then the take-home interpretations and conclusions?
4. **Your assessment.** Your own read on the paper's strengths and weaknesses — its importance to the field, how it relates to other work, whether the data genuinely support the conclusions, whether there are important alternative interpretations the authors didn't address, and even its readability.

That fourth point is the one that turns a passive summary into active scholarship: it forces you to form and record your own judgment, which is exactly what you'll want when you cite the paper later.

---

## References

- [A Zotero-to-Obsidian Workflow](https://hydroaggie.github.io/blog/2023/A-Zotero-to-Obsidian-Workflow/) — the group's blog post on importing Zotero items (metadata, annotations, highlights) into Obsidian.
- [NotebookLM](https://notebooklm.google.com/) — for quickly answering targeted questions straight from a paper's PDF.
