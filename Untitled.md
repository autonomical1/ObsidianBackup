$$
\documentclass {article}

\usepackage {tikz}
\usetikzlibrary {positioning}
%\usepackage {xcolor}
\definecolor {processblue}{cmyk}{0.96,0,0,0}
\begin {document}
\begin {center}
\begin {tikzpicture}[-latex ,auto ,node distance =4 cm and 5cm ,on grid ,
semithick ,
state/.style ={ circle ,top color =white , bottom color = processblue!20 ,
draw,processblue , text=blue , minimum width =1 cm}]
\node[state] (C)
{$1$};
\node[state] (A) [above left=of C] {$0$};
\node[state] (B) [above right =of C] {$2$};
\path (A) edge [loop left] node[left] {$1/4$} (A);
\path (C) edge [bend left =25] node[below =0.15 cm] {$1/2$} (A);
\path (A) edge [bend right = -15] node[below =0.15 cm] {$1/2$} (C);
\path (A) edge [bend left =25] node[above] {$1/4$} (B);
\path (B) edge [bend left =15] node[below =0.15 cm] {$1/2$} (A);
\path (C) edge [bend left =15] node[below =0.15 cm] {$1/2$} (B);
\path (B) edge [bend right = -25] node[below =0.15 cm] {$1/2$} (C);
\end{tikzpicture}
\end{center}
\end{document}
$$