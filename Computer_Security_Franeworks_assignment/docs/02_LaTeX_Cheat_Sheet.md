# LaTeX Cheat Sheet

The commands you'll use 95% of the time.

---

# Chapters

```latex
\chapter{Title}
```

---

# Sections

```latex
\section{Title}
```

---

# Subsections

```latex
\subsection{Title}
```

---

# Bold

```latex
\textbf{Bold Text}
```

---

# Italics

```latex
\textit{Italic Text}
```

---

# Bullet List

```latex
\begin{itemize}

\item First

\item Second

\end{itemize}
```

---

# Numbered List

```latex
\begin{enumerate}

\item First

\item Second

\end{enumerate}
```

---

# Figure

```latex
\begin{figure}[H]

\centering

\includegraphics[width=.8\textwidth]{figures/example}

\caption{Example Figure}

\label{fig:example}

\end{figure}
```

Reference later

```latex
\cref{fig:example}
```

---

# Table

```latex
\begin{table}[H]

\centering

\caption{Example Table}

\begin{tabular}{ll}

\toprule

Column A & Column B \\

\midrule

A & B \\

\bottomrule

\end{tabular}

\label{tab:example}

\end{table}
```

Reference

```latex
\cref{tab:example}
```

---

# Citation

Narrative

```latex
\textcite{nist2024}
```

Parenthetical

```latex
\parencite{nist2024}
```

---

# Cross References

```latex
\label{sec:pdca}

...

\cref{sec:pdca}
```

---

# New Page

```latex
\clearpage
```

---

# Footnote

```latex
\footnote{Footnote text}
```

---

# Compile Often

Whenever you

✔ add a figure

✔ add a table

✔ add a citation

✔ rename a label

Compile.

Small errors are easy.

Large ones become archaeological excavations.