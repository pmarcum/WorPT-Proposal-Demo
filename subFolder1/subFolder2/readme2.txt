%======================================================
%     H O W   T O   U S E   T H I S   F I L E
% (1)  add the following in the preamble of your main paper:
%          \makeatletter \def\expinput#1{\@@input#1} \makeatother
% (2) type the following into the main latex file where you want to put this table:
%\newcolumntype{L}[1]{>{\raggedright\let\newline\\\arraybackslash\hspace{0pt}}p{#1}}
%{
%   \renewcommand{\arraystretch}{1.0} %adjust to control vertical row separation/spacing, comment-out if not needed
%   \setlength{\tabcolsep}{5pt} %adjust to control horizontal column separation/spacing, comment-out if not needed
%   \begin{longtable}{
%      |L{1.8in}!{\color{lightgray}\vrule}L{1.3in}!{\color{lightgray}\vrule}L{2.5in}!{\color{lightgray}\vrule}p{0.10in}!{\color{lightgray}\vrule}p{0.28in}|
%      }
%      \caption{Work Effort for All Team Members \label{tab:NOTANONhst}}\\
%      \multicolumn{5}{l}{\textbf{Program \#:} HST-xx-xxxxx (Cycle XX)}\\
%      \multicolumn{5}{l}{\textbf{Program Admin PI:} Dr. Pamela Marcum}\\
%      \multicolumn{5}{l}{\textbf{Science PI:} Dr. Alejandro Borlaff}\\
%      \expinput{do_NOT_manally_edit/NOTANONhst}
%   \end{longtable}
%}
%======================================================
\textbf{\cellcolor{Blue}\color{White}Contributor} & \textbf{\cellcolor{Blue}\color{White}Position} \newline{\textbf{\cellcolor{Blue}\color{White}Institution}\newline{\textbf{\cellcolor{Blue}\color{White}US/Foreign}}} & \textbf{\cellcolor{Blue}\color{White}Role} & \textbf{\cellcolor{Blue}\color{White}\$?} & \textbf{\cellcolor{Blue}\color{White}FTE}\\
\hline\hline
Alejandro S Borlaff \newline{Science PI} &  NPP postdoc \newline{NASA Ames} \newline{US} &  & Y & 2.90\hline
Pamela M.I. Marcum \newline{Administrative PI} &  research scientist \newline{NASA Ames} \newline{US} &  & Y & 0.75\hline
Fernando  Buitrago \newline{Collaborator} &   \newline{} \newline{F} &  & N & 0.00\hline
Seppo  Laine \newline{co-Investigator} &   \newline{} \newline{US} &  & N & 0.00\hline
Mireia  Montes \newline{Collaborator} &   \newline{} \newline{F} &  & N & 0.25\hline
tbd  postdoc \newline{co-Investigator} &   \newline{} \newline{US} &  & N & 0.68\hline
undergrad  student1 \newline{Undergraduate Student} &   \newline{} \newline{US} &  & Y & 0.30\hline