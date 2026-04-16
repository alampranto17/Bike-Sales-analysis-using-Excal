\documentclass[a4paper,10pt]{article}

\usepackage[margin=1in]{geometry}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{graphicx} % For image

\titleformat{\section}{\large\bfseries}{}{0em}{}
\titleformat{\subsection}{\normalsize\bfseries}{}{0em}{}

\title{\textbf{Bike Sales Dashboard}}
\author{Alam Pranto}
\date{}

\begin{document}

\maketitle

\section*{Overview}
The \textbf{Bike Sales Dashboard} is an interactive data visualization project built using Microsoft Excel. It provides insights into customer demographics, income levels, and purchasing behavior related to bike sales.

\section*{Dashboard Preview}
\begin{center}
    \includegraphics[width=\textwidth]{dashboard.png}
\end{center}

\section*{Objectives}
\begin{itemize}[noitemsep]
    \item Understand customer behavior in bike purchasing
    \item Identify key factors influencing sales
    \item Enable data-driven decision-making
    \item Practice dashboard design and data analysis
\end{itemize}

\section*{Features}

\subsection*{Interactive Filters (Slicers)}
\begin{itemize}[noitemsep]
    \item \textbf{Marital Status:} Married, Single
    \item \textbf{Region:} Europe, North America, Pacific
    \item \textbf{Education Level:}
    \begin{itemize}[noitemsep]
        \item Bachelors
        \item Graduate Degree
        \item High School
        \item Partial College
        \item Partial High School
    \end{itemize}
\end{itemize}

\subsection*{Visualizations}
\begin{itemize}[noitemsep]
    \item \textbf{Income vs Gender}
    \item \textbf{Age Group Analysis}
    \item \textbf{Customer Commute Distance}
\end{itemize}

\section*{Tools \& Technologies}
\begin{itemize}[noitemsep]
    \item Microsoft Excel
    \item Pivot Tables, Charts, Slicers
\end{itemize}

\section*{Project Structure}
\begin{verbatim}
Bike-Sales-Dashboard/
│
├── Bike_Sales_Dashboard.xlsx
├── dashboard.png
└── README.tex
\end{verbatim}

\section*{Key Insights}
\begin{itemize}[noitemsep]
    \item Middle-aged customers buy the most bikes
    \item Higher income increases purchase likelihood
    \item Short-distance commuters are key buyers
\end{itemize}

\section*{Contact}
\textbf{Name:} Alam Pranto \\
\textbf{Field:} Data Analysis \& Software Development

\end{document}
