---
schemaVersion: treeseed.knowledge-page/v1
id: team-knowledge-authoring
bookId: team-operations
slug: knowledge-authoring
title: Knowledge Authoring
summary: How agents place durable knowledge in books without mixing it with operational records.
status: published
visibility: team
order: 60
contributors: []
relatedBookIds: []
relatedKnowledgeIds: []
relatedNoteIds: []
relatedQuestionIds: []
relatedObjectiveIds: []
relatedProposalIds: []
relatedDecisionIds: []
guaranteeIds: []
audiences: { primary: [], secondary: [], excluded: [] }
capabilityIds: []
routePatterns: []
resourceTypes: []
actionIds: []
keywords: [knowledge, books, authoring]
documentationUrls: []
---

Every ordinary document in the knowledge directory is a page in a declared book. Create the book definition at `books/{book}.md` and place each page at `knowledge/{book}/{page}.md`, with matching `bookId` and page slug metadata. Do not write miscellaneous or catch-all entries directly under `knowledge/`. Questions, proposals, decisions, releases, agent definitions, context queries, tests, and other operational records remain in their dedicated collections rather than being disguised as book pages.
