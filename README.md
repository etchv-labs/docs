# Etchv documentation

The content of [etchv.com/docs](https://etchv.com/docs). Report problems at hello@etchv.com.

## Writing a page

- Lead with the task and a working example. Use tables for options, limits and response fields.
- Keep each paragraph to one point. Link to shared billing, retry and storage rules instead of repeating them.
- Keep requirements and security steps visible. Use `<Details title="…">` for optional recipes or deeper reference material; keep headings outside disclosures.
- Use `<Facts>` with three `<Fact label="…">` entries for a short endpoint summary.
- Preserve existing section IDs when moving or renaming content, and check examples against the API or SDK implementation.

The website renders these MDX files directly. Documentation checks in `web/src/lib/docs.test.tsx` cover rendering, outlines, internal links and concise paragraphs.
