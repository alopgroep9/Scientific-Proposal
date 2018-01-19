# Scientific-Proposal

\documentclass[11pt]{article}
\usepackage[utf8]{inputenc}
\usepackage{geometry}
\geometry{a4paper}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{array}
\usepackage{paralist}
\usepackage{verbatim}
\usepackage{subfig}
\usepackage{mathtools}
\usepackage{amssymb}
\usepackage{amsthm}
\usepackage{bm}
\usepackage[dutch,english]{babel}
%\selectlanguage{dutch}
\usepackage{nicefrac}
\usepackage{dirtytalk}
\usepackage{textcomp}
\usepackage{gensymb}
\usepackage{hyperref}
\usepackage[usenames,dvipsnames,svgnames,table]{xcolor}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{mathrsfs}
\usepackage{pgfplots}
\usepackage{titling}
\pgfplotsset{compat=1.14}
\usepackage{cancel}
\usepackage{chemmacros}
\usepackage{changepage}
\changepage{90 pt}{80 pt}{-40 pt}{-40 pt}{}{-20 pt}{}{-10 pt}{15 pt}
%\changepage{textheight}{textwidth}{evensidemargin}{oddsidemargin}{columnsep}{topmargin}{headheight}{headsep}{footskip}
\usepackage{fancyhdr}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\rfoot{\thepage}
\pagestyle{fancy}
\usepackage[bottom]{footmisc}
\usepackage{calligra}
\DeclareMathAlphabet{\mathcalligra}{T1}{calligra}{m}{n}
\DeclareFontShape{T1}{calligra}{m}{n}{<->s*[2.2]callig15}{}
\newcommand{\scripty}[1]{\ensuremath{\mathcalligra{#1}}}
\newcommand{\dau}[2]{\frac{\partial#1}{\partial#2}}
\usepackage{listings}
\lstset{language=Python, showstringspaces=false, basicstyle=\small,
  numbers=left, numberstyle=\tiny, numberfirstline=false, breaklines=true,
  stepnumber=1, tabsize=4, 
  commentstyle=\ttfamily, identifierstyle=\ttfamily,
  stringstyle=\itshape, inputpath=Python/}
\hypersetup{linktoc=all}
\graphicspath{ {pictures/} }
\setcounter{page}{0}
\newcommand\addtag{\refstepcounter{equation}\tag{\theequation}}
\pretitle{\centering \LARGE}
\title{Astronomy Lab and Research Project\\} %Title
\posttitle{Proposal for La Palma Trip
\vspace{10mm}\\}
\preauthor{\centering}
\author{Dani de Boe - s1816942,\\
Sharon Diamant - s1847848\\
Jeroen van Duijvenbode - s1832395,\\
Jurriaan de Gier - s1619179 \&\\
Yorick Konijn - s1815660\\} %Author
\postauthor{\vspace{5mm}}
\predate{\centering \large }
\date{\today\\}
\postdate{\vspace{10mm}}%hier kan een plaatje in
\begin{document}
\maketitle

\section{Scientific Justification}

With this research we want to follow up on multiple of the MASCARA targets. The Multi-site All-Sky CAmeRA or  MASCARA in short is a sky survey set up to detect new exoplanets transiting bright stars with $4<m_V<8$. Mascara consists of two stations, one in the northern hemisphere at La Palma and one in the southern hemisphere in Chile. Ignas Snellen and his research group have already discovered two new exoplanets orbiting around the bright stars called MASCARA-1b and MASCARA-2b. The expectation is that the MASCARA will detect new exoplanets orbiting bright stars in the future.\\

Our research will consist of photometric transit observations of these bright stars. Because the resolution of MASCARA is quite low the transit-like signal MASCARA measures could be caused by a varying background object in the vicinity of the star. By making more precise observations with the Isaac Newton Telescope we can rule this possibility out and refine the shape of the transit. \\

For the photometric transit observations we will measure the flux of a bright star before, during and after a transit. If we measure a slight decrease in flux for a period we have measured a transit. Using the shape of the transit curve we can reason which object is likely causing the transit, e.g. an exoplanet or binary. This will enable further spectroscopic transit observations and radial velocity measurements to characterize the system and determine if the transiting object is indeed an exoplanet.\\
%misschien info erbij hoe de curve eruit gaan zien zowel voor binary als exoplanet

However as seen in figure \ref{fig:1}, most discovered exoplanets using transit observations are around fainter star, whereas radial velocity measurements are mostly done around brighter stars. Having both transit and radial observations of an exoplanet around a bright star is valuable for modeling the system. Using both methods for bright early type stars allows us to create better models to characterize the formation and evolution of exoplanets around early type stars.


\clearpage
\begin{figure}[h!]
    \centering
    \includegraphics[scale=0.75]{Observed.png}
    \caption{Discovered planets by primary transit and radial velocity. As seen in the figure very few exoplanets have been discovered around bright stars, whereas most radial velocity discoveries have been around brighter stars. We got the data from a catalogue of exoplanet.eu.}
    \label{fig:1}
\end{figure}

\section{References}
\begin{itemize}
\item Talens, G.J.J; Justesen, A.B; et al. The Multi-site All-Sky CAmeRA. (2017) A\&A Volume 601\\
\href{https://arxiv.org/pdf/1702.03931.pdf}{\textcolor{blue}{\underline{https://arxiv.org/pdf/1702.03931.pdf}}}

\item Talens, G.J.J; Justesen, A.B; et al. MASCARA-2b: A hot Jupiter transiting a $m_V=7.6$ A-star. (2017) A\&A Volume 601\\
\href{https://arxiv.org/pdf/1707.01500.pdf}{\textcolor{blue}{\underline{https://arxiv.org/pdf/1707.01500.pdf0}}}

\item Roques F., Schneider J., (2017) The Extrasolar Planets Encyclopedia\\
\href{http://exoplanet.eu/catalog/}{\textcolor{blue}{\underline{http://exoplanet.eu/catalog/}}}[Accessed December 1, 2017]
\end{itemize}

\end{document}

Dit is vooral nodig in het vervolg
\thispagestyle{empty}
\titlepage
%\tableofcontents
\clearpage
\section{Project}
We want to observe a MASCARA target and try to confirm the presence or absence of a planet.\\
\\
\section{Technical Remarks}
To do this it is critical to account for the high magnitude of these types of stars. We can do this by observing the star out of focus, changing the observed star from a point source to a \say{donut}. This would of course make the errors larger and make the data-reduction more difficult.\\
\\
\clearpage
