# Personal Learning Notes

Private Markdown archive synchronized automatically from Personal Learning OS.

Each completed session creates one file under:

```text
sessions/YYYY/MM/YYYY-MM-DD-HHMM-<session-id>-<title>.md
```

Every document contains session metadata, its title, and the original Markdown
details. Formula source such as `$...$` and `$$...$$` is preserved verbatim for
renderers with KaTeX or MathJax support.

Files are written by the tracker through the GitHub CLI installed on the host.
Failed pushes remain queued in the tracker database and are retried by its
systemd timer.
