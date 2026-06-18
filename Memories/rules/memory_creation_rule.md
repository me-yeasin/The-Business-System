# Rule: Creating Memories

To ensure our AI agents can efficiently process hundreds or thousands of memories without reading every single file in full, all memories stored in the `memories/` directory must strictly follow this structure:

## 1. File Naming Convention
- The name of the memory file must be **reasonable, descriptive, and directly related to the topic**. 
- Example: `client_onboarding_process.md` or `successful_outreach_template.md`.

## 2. File Structure
Every memory file must begin with a clear Title and a short Subtitle. The agent will read these first to determine if the memory is relevant to the current task.

### Format Template:

```markdown
# [Title: Core Subject of the Memory]
**Subtitle / Short Detail:** [A 1-2 sentence description of what this memory contains and when to use it.]

---

## Summary / Details
[Provide the full summary of what we did, the actual memory, learnings, or strategies.]
```

## Why We Do This
By providing a clear Title and Subtitle at the very top, the AI agent can quickly scan multiple memory files and selectively pick only the ones that are required for the specific task at hand, saving time and context window limits.
