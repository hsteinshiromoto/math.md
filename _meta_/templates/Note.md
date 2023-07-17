<% NoteType = await tp.system.prompt("Note Type") %>
<% NoteTitle = await tp.system.prompt("Note Title") %>
<% await tp.file.rename(NoteTitle) %>

tags: #<% NoteType %>

# <% NoteTitle %>

## Context


## Statements

**<% NoteType %>**. ()


## References
