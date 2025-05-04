\documentclass[a4paper,10pt]{article}
\usepackage[a4paper, top=0.5in, bottom=0.5in, left=0.5in, right=0.5in]{geometry}
\usepackage{hyperref}
\usepackage{enumitem}
\usepackage{parskip}
\usepackage{fontawesome5}
\usepackage{needspace}

% Hyperlink setup
\hypersetup{colorlinks=true, linkcolor=black, urlcolor=blue}

% Custom section style (full width, neat alignment)
\newcommand{\sectiontitle}[1]{%
  \vspace{1pt}%
  \noindent\textbf{\large #1} \\[-2pt]
  \noindent\rule{\linewidth}{0.5pt}%
  \vspace{1pt}%
}

\renewcommand{\baselinestretch}{1.01}
\setlength{\parskip}{1pt}

\begin{document}

% TITLE AND CONTACT INFO
\begin{center}
  {\Huge \textbf{SATHIYANARAYANAN}} \\[4pt]
  \href{mailto:sathiyaram5311@gmail.com}{\faEnvelope\,sathiyaram5311@gmail.com} \quad
  \faPhone\,+91 6382503809 \quad
  \href{https://www.linkedin.com/in/sathiyanarayanan5311}{\faLinkedin\,LinkedIn} \quad
  \href{https://github.com/Sathiyanarayanan53}{\faGithub\,GitHub}
\end{center}
\vspace{2mm}

% EDUCATION
\sectiontitle{Education}
\textbf{SASTRA Deemed University}, Thanjavur, India \\
B.Tech, Electronics \& Communication Engineering \\
Expected May 2025\hfill CGPA: 6.30/10.0 \\
\textbf{Sri Ramakrishna Boys HSS}, India \\
Higher Secondary, May 2021\hfill 85.1\% \\
\textbf{Immaculate Matric School}, India \\
Secondary, May 2019\hfill 81.4\%

% SKILLS
\sectiontitle{Skills}
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item \textbf{Programming:} JavaScript, HTML/CSS, Java, Verilog, VHDL
  \item \textbf{Hardware:} VLSI, FPGA (Vivado), Arduino, ESP32, JTAG
  \item \textbf{Tools:} ModelSim, HSPICE, DSP
  \item \textbf{Soft Skills:} Problem-Solving, Teamwork, Analytical Thinking
\end{itemize}

% COURSEWORK
\sectiontitle{Coursework}
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item Introduction to Web Development
  \item VLSI Design Fundamentals
  \item Full Stack Development (Clever Academy, Apr--Jul 2024)
\end{itemize}

% EXPERIENCE
\sectiontitle{Experience}
\textbf{Ashok Leyland}, Hosur, Tamil Nadu, India \\
R\&D In-Plant Training \hfill Jun--Jul 2024
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item Optimized testing with MATLAB, cut time 10\%.
  \item Calibrated ECU for EVs with CAN bus.
\end{itemize}

% PROJECTS
\sectiontitle{Projects}
\textbf{Lightweight IoT Encryption (Simon \& Simeck)} \\
Jan--Apr 2025 \hfill \href{https://github.com/Sathiyanarayanan53/iot-encryption}{\faGithub\,GitHub}
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item Designed FPGA algorithms, cut power 15\%.
  \item Built JavaScript interface.
  \item Tech: Verilog, Vivado, ModelSim, JavaScript
\end{itemize}
\textbf{VLSI D Flip-Flop Optimization} \\
Sep--Dec 2023
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item Designed efficient circuit, improved 12\%.
  \item Created Java simulation tool.
  \item Tech: ModelSim, HSPICE, Java
\end{itemize}

% ACHIEVEMENTS
\sectiontitle{Achievements}
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item 1\textsuperscript{st}/50+ VLSI Quiz, SASTRA (2023)
  \item Distinction, IEEE FPGA Workshop (2024)
\end{itemize}

% PROFESSIONAL DEVELOPMENT
\needspace{2\baselineskip}
\sectiontitle{Professional Development}
\begin{itemize}[left=0pt, label=--, noitemsep, topsep=0pt, partopsep=0pt]
  \item IEEE Webinars: Low-Power VLSI, IoT (2024)
\end{itemize}

% INTERESTS
\needspace{2\baselineskip}
\sectiontitle{Interests}
IoT Systems, VLSI Design, Full-Stack Web Development

\end{document}
