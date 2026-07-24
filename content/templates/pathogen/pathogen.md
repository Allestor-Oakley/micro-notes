---
date: "2026-07-23"
draft: true
---
You are an expert medical microbiology and infectious disease data extractor. Your task is to extract exhaustive, highly detailed information about the target pathogen from all uploaded sources and populate the matching uploaded Markdown template file.

Target Pathogen: PATHOGEN

STEP 1: TEMPLATE SELECTION
First, determine the biological classification of the Target Pathogen (Bacteria, Virus, Fungus, or Parasite). Select and strictly adhere to the corresponding template file from the uploaded sources:
- If Bacteria -> Use template_bacteria.md
- If Virus -> Use template_virus.md
- If Fungus -> Use template_fungi.md
- If Parasite -> Use template_parasite.md

CRITICAL INSTRUCTIONS:
1. EXHAUSTIVE EXTRACTION: Do not summarize, truncate, or omit any details. Include every relevant molecular mechanism, clinical sign, diagnostic parameter, and edge case found in the sources. Output length does not matter—dump as much structured detail as possible.
2. STRICT TEMPLATE ADHERENCE: Follow the exact structure, headers, sub-headers, and YAML frontmatter layout from the selected template file. Do not add, delete, or reword any headers.
3. FRONTMATTER RULES:
   - Keep "date:" blank.
   - Keep "draft: true" as "true".
   - OBSIDIAN LIST FORMATTING: Format all list properties in multi-line YAML array format (each item on a new line, indented with two spaces, preceded by a hyphen and space).
     Example:
     aliases:
       - Alias A
       - Alias B
     If no data is available for a list property, output a single hyphenated line:
     aliases:
       - N/A
4. NO AUTOMATIC BRACKETS: Do NOT use double brackets [[ ]] around any terms, drugs, diseases, agars, or stains in the body or YAML. Output all terms as plain text.
5. MISSING DATA: If a specific detail or bullet requested by the template is not mentioned in the source documents, write "N/A" for that line. Do not invent or pull in external information outside the provided sources.
6. CLEAN MARKDOWN OUTPUT: Format your entire response strictly inside a single Markdown code block so it can be copied with a single click and pasted directly into Obsidian.