# PRODUCT.md Specification

Version: 0.1  
Status: Draft — pending review

## Purpose

A PRODUCT.md is a living reference document that describes a product line — what it is, who it serves, how it is made and distributed, and where it stands today.

The document answers two questions simultaneously: **What is this product?** and **Why does it exist?** It serves as the authoritative source of truth for anyone — human or AI — who needs to understand a product line's identity, specifications, capacity, and current state.

A PRODUCT.md has no end state. Unlike a project plan or proposal that gets approved and completed, a product document persists as long as the product line exists. Its sections are updated at different frequencies — positioning rarely changes, specifications occasionally change, and the current situation changes often — but the document itself is never "done."

The basic unit of a PRODUCT.md is a natural language sentence — the same principle that governs CHARACTER.md and QUEST.md. Each section is written in prose, not in structured fields or key-value pairs. An AI reading the document should understand the product line from the language alone, without requiring a schema to interpret it.

## Relation to Other Documents

A PRODUCT.md is not a QUEST. A QUEST has a Destination that can be reached or abandoned; a PRODUCT.md has no destination, only a reference state it continually approaches or drifts from. The relationship between them is that of a product manager to a project manager: PRODUCT.md describes what the product should be, QUEST cards describe the work being done to move it there.

A PRODUCT.md is not a proposal or business plan. Those are persuasion documents with an approval endpoint. A PRODUCT.md begins as an internal reference and may later be shared externally, but its primary function is orientation, not persuasion.

A PRODUCT.md is not a story bible. Narrative continuity details — characters, world-building, plot threads, timelines — belong in their own documents. A PRODUCT.md may reference a story bible but does not duplicate its contents.

## Sections

A PRODUCT.md consists of a one-line summary followed by five sections. The sections are ordered by stability: what changes least comes first, what changes most comes last.

### 0. Summary

One sentence. It captures the product line's reason for existing and its current form. This is the equivalent of a logline (in television), a vision statement (in game design), or an executive summary compressed to its essential tension.

The summary should answer: "If someone asks what this product line is and why it matters, what is the single sentence I would say?"

### 1. Positioning

This section defines the product line's identity. It answers: what is it, who is it for, and what is it not.

Contents include, but are not limited to:

- What the product is (genre, format, medium, tone)
- Target audiences (be specific — not "general public")
- Goals and brand attributes (what the product line stands for)
- How it differs from the organization's other product lines
- What it explicitly excludes (scope boundaries — borrowed from game design documents, where "what the game is NOT" prevents scope creep)

If the product is a narrative property, a brief reference to the story bible may appear here — a link or one-paragraph summary, not duplicated content.

This section changes rarely. When it does change, it usually signals a strategic pivot.

### 2. Specifications

This section describes the concrete form of the product. It answers: what does one unit of this product look like?

The specific contents vary by product type. For a book series, this might include word count range, publication cadence, physical format, cover specifications. For a game, this might include platform targets, core loop description, session length. For a podcast, episode length, release frequency, segment structure.

Because specifications are product-specific, this section is the most variable across different PRODUCT.md instances. The spec does not prescribe what fields must appear — only that the section must describe the product's tangible form in enough detail that someone unfamiliar with it could recognize a finished unit.

This section changes occasionally — typically when the product evolves or when lessons from production lead to revised standards.

### 3. Capacity and Distribution

This section describes the supply side. It answers: how is this product made, and how does it reach its audience?

Contents include, but are not limited to:

- Production capacity (realistic output rate, bottlenecks)
- Platform inventory (which platforms, ranked by priority — primary, secondary, tertiary)
- Distribution channels and their relationships
- Release rhythm and windowing (how content flows across platforms over time)

This section must be honest. Aspirational capacity does not belong here — only actual demonstrated capability and known constraints. If production is bottlenecked by a single person, say so.

This section changes seasonally or when distribution relationships change.

### 4. Current Situation

This section describes where the product line stands right now. It answers: what is the gap between the positioning/specifications described above and the reality on the ground?

Contents include, but are not limited to:

- A brief environmental scan (competitive landscape, relevant market shifts)
- The current gap between intended positioning and actual market presence
- Active constraints or blockers

This is the most frequently updated section. It should be written with the same honesty standard as Capacity — no reporting only good news.

### 5. Related QUESTs

This section contains only links to active QUEST documents or collection items that are currently advancing this product line. No content is duplicated from the QUESTs themselves — this is purely an index.

When a QUEST is completed or abandoned, its link is removed from this section. The QUEST's own record preserves its history.

## Naming

A PRODUCT.md instance is titled with the product line's name. It does not carry a "PRODUCT" prefix in its title — the prefix belongs to the specification, not to instances. For example, a document would be titled "Short Fiction Series" rather than "PRODUCT — Short Fiction Series."

## Design Principles

**No end state.** A PRODUCT.md is never completed, only maintained. This distinguishes it from QUEST (which has a Destination) and from proposals (which have an approval point).

**Stability gradient.** Sections are ordered from most stable to least stable. Positioning rarely moves; the current situation moves constantly. This ordering means a reader scanning from top to bottom moves from bedrock identity to volatile present — the same information architecture used in television production bibles and game design documents.

**Honesty over aspiration.** Capacity, current situation, and gap analysis must reflect reality. This principle is shared with the organization's asset tracking philosophy: narrative text that reports both good and bad news is more valuable than structured indicators that create false precision.

**Semantic, not structural.** Like CHARACTER.md and QUEST.md, this specification defines what to communicate, not how to format it. A PRODUCT.md can live in a Markdown file, a Craft document, a Google Doc, a Notion page, or any other medium that supports prose.

## Prior Art

**Television Production Bible.** A production bible is a living reference document maintained throughout a series' run. It simultaneously answers "what is this show?" and "why will audiences watch it for years?" — the dual purpose that PRODUCT.md inherits. The stability gradient (premise rarely changes, episode details change constantly) directly informs the section ordering. Source: industry practice documented across StudioBinder, Script Reader Pro, Celtx, and others.

**Game Design Document (GDD).** A GDD is described by practitioners as a "living document" that evolves throughout development. The explicit inclusion of "what the game is NOT" in GDD templates inspired the scope boundary requirement in the Positioning section. The shift from waterfall-era static GDDs to agile living documents parallels the shift from one-time business plans to persistent product documents. Source: industry practice documented across Game Design Skills, Nuclino, Codecks, and Wikipedia.

**Transmedia Marketing Plan (Zeiser).** Anne Zeiser's marketing plan outline in *Transmedia Marketing: From Film and TV to Games and Digital Media* (2015) provides a comprehensive cross-platform planning structure. Its key insight adopted here: "goals rarely change, strategies occasionally change, and tactics are often revised" — which maps directly to the stability gradient. The plan's separation of Story Bible Overview (optional, brief, reference only) from the marketing plan body confirmed the decision to exclude narrative continuity details from PRODUCT.md. The plan's Transmedia Platforms section (primary/secondary/tertiary ranking with inter-platform relationships) informed the Capacity and Distribution section structure.

**QUEST.md.** The companion specification for project-level documents with a defined endpoint. PRODUCT.md borrows the one-line Summary concept (analogous to QUEST's Destination summary) and the principle that tactical details belong in execution documents, not in reference documents. The two specifications share the same semantic-not-structural philosophy and natural-language-sentence foundation.
