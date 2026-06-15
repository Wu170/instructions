# instructions

[Click here to see the wiki](https://github.com/pi-node/instructions/wiki)

**Test note:** This line was added for testing README modification.

Instructions:
1. For each file listed above, produce the complete modified file content.
2. Write a concise commit message describing the changes.
3. Write a pull request title (short, under 80 chars) and body.

Output ONLY valid JSON in this exact format (no markdown code fences, no extra text):

{
  \"proposed_files\": [
    {
      \"path\": \"<exact file path from above>\",
      \"content\": \"<complete modified file content>\",
      \"change_summary\": \"<one-line summary of what changed>\"
    }
  ],
  \"commit_message\": \"<conventional commit message, e.g. docs: add test note to README>\",
  \"pull_request_title\": \"<short PR title, under 80 chars>\",
  \"pull_request_body\": \"<PR description, can be multi-line>\"
}

Important rules:
- ONLY output the JSON object, nothing else.
- Do NOT invent new file paths; only use paths listed above.
- Content should be the complete file after modification, not a diff.
- The output must be valid JSON (use double quotes, proper escaping).