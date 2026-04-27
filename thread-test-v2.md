## Review Thread Resolution Test v2

### TODO
- Item 1: This line is fine
- Item 2: This line has a problem that needs discussion
- Item 3: This line is also fine

### Notes
Testing required_review_thread_resolution: true

Steps:
1. Draft PR created
2. Admin opens an INLINE review thread on Item 2 above
3. Collaborator tries to merge — should be BLOCKED
4. Admin resolves the thread
5. Merge succeeds

