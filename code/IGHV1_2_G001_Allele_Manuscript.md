---
title: ""
output: 
  pdf_document:
    keep_md: true
header-includes: 
- \usepackage{pdflscape}
- \newcommand{\blandscape}{\begin{landscape}}
- \newcommand{\elandscape}{\end{landscape}}
- \usepackage{caption} 
- \captionsetup[table]{labelformat=empty} 
- \captionsetup[figure]{labelformat=empty}
---



































\begin{figure}[htbp]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig1-1} 

}

\caption{Composite Genotype-mRNA-HCDR3-Usage-Plot}\label{fig:fig1}
\end{figure}











<!-- modeling utilities -->





\blandscape
\begin{figure}[htbp]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig2-1} 

}

\caption[Allele model estimates by genotype]{Allele model estimates by genotype.}\label{fig:fig2}
\end{figure}
\elandscape








\begin{figure}[H]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig3-1} 

}

\caption[Ratio estimates]{Ratio estimates}\label{fig:fig3}
\end{figure}


\blandscape
\begin{figure}[htbp]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig4-1} 

}

\caption{Naive vs. VRC01 response correlations}\label{fig:fig4}
\end{figure}
\elandscape

\blandscape
\begin{figure}[htbp]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig3S-1} 

}

\caption{Naive vs. VRC01 response correlations}\label{fig:fig3S}
\end{figure}
\elandscape





\blandscape
\begin{figure}[htbp]

{\centering \includegraphics[width=1\linewidth,]{IGHV1_2_G001_Allele_Manuscript_files/figure-latex/fig2S-1} 

}

\caption[Quasipoisson fit plot]{Quasipoisson fit plot}\label{fig:fig2S}
\end{figure}
\elandscape

















\begin{table}[!h]

\caption{\label{tab:genotype-cnt-tab-supp}Table S1}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{lrrrrrrrr}
\toprule
Treatment & *02/*02 & *02/*04 & *02/*05 & *02/*06 & *04/*04 & *04/*05 & *04/*06 & *05/*06\\
\midrule
100 µg & 7 & 4 & 2 & 0 & 1 & 1 & 2 & 1\\
20 µg & 1 & 4 & 0 & 0 & 7 & 1 & 5 & 0\\
Placebo & 3 & 5 & 0 & 2 & 2 & 0 & 0 & 0\\
\midrule
Total & 11 & 13 & 2 & 2 & 10 & 2 & 7 & 1\\
\bottomrule
\end{tabular}
\end{table}



\begin{table}[!h]

\caption{\label{tab:usage-tab-supp}Table S2}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{llrllll}
\toprule
\multicolumn{2}{c}{Allele} & \multicolumn{1}{c}{n} & \multicolumn{1}{c}{Mean} & \multicolumn{1}{c}{95\% CI} & \multicolumn{1}{c}{Min} & \multicolumn{1}{c}{Max} \\
\midrule
*02 & Homozygote & 11 & 3.15\% & 2.72\% to 3.57\% & 2.28\% & 4.52\%\\
 & Heterozygote & 17 & 3.34\% & 2.87\% to 3.82\% & 1.98\% & 6.29\%\\
\midrule
*04 & Homozygote & 10 & 0.86\% & 0.67\% to 1.06\% & 0.41\% & 1.22\%\\
 & Heterozygote & 22 & 0.72\% & 0.63\% to 0.81\% & 0.25\% & 1.12\%\\
\midrule
*05 & Heterozygote & 5 & 0.09\% & 0.03\% to 0.14\% & 0.03\% & 0.14\%\\
\midrule
*06 & Heterozygote & 10 & 2.43\% & 1.87\% to 2.99\% & 1.78\% & 4.18\%\\
\bottomrule
\end{tabular}
\end{table}



\begin{table}[!h]

\caption{\label{tab:usage-comp-tab-supp}Table S3}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{llll}
\toprule
\multicolumn{1}{c}{Allele} & \multicolumn{1}{c}{Difference} & \multicolumn{1}{c}{95\% CI} & \multicolumn{1}{c}{P-value} \\
\midrule
*02 & -0.19\% & -0.80\% to 0.41\% & 0.51\\
\midrule
*04 & 0.14\% & -0.07\% to 0.35\% & 0.17\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:mag-tab-vrc01-supp}Table S4}
\centering
\fontsize{6}{8}\selectfont
\begin{tabular}[t]{ll>{\raggedright\arraybackslash}p{5.1cm}>{\raggedright\arraybackslash}p{.9cm}l>{\raggedright\arraybackslash}p{1.1cm}>{\raggedright\arraybackslash}p{1.1cm}}
\toprule
\multicolumn{5}{c}{ } & \multicolumn{2}{c}{P Value} \\
\cmidrule(l{3pt}r{3pt}){6-7}
 &  & Comparison & Sample Sizes & Median (Range) & Unadjusted & FDR Adjusted\\
\midrule
\addlinespace[0.3em]
\multicolumn{7}{l}{\textbf{20 µg}}\\
\hspace{1em} & Wk4 MBC & *02/*04 vs. *04/*04 & 4 vs. 6 & 0.0092 [0.0049, 0.0572] vs. 0.0121 [0.0026, 0.0924] & 1.0000 & 1.0000\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 6 & 0.0092 [0.0049, 0.0572] vs. 0.0066 [0.0031, 0.0140] & 0.4762 & 0.8081\\
\cmidrule{3-7}
\hspace{1em} &  & *04/*04 vs. *04/*05 or *04/*06 & 6 vs. 6 & 0.0121 [0.0026, 0.0924] vs. 0.0066 [0.0031, 0.0140] & 0.4848 & 0.8081\\
\cmidrule{2-7}
\hspace{1em} & Wk8 MBC & *02/*04 vs. *04/*04 & 4 vs. 4 & 0.0054 [0.0018, 0.0469] vs. 0.0081 [0.0014, 0.0264] & 0.8857 & 0.9797\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 6 & 0.0054 [0.0018, 0.0469] vs. 0.0024 [0.0007, 0.0216] & 0.2571 & 0.8000\\
\cmidrule{3-7}
\hspace{1em} &  & *04/*04 vs. *04/*05 or *04/*06 & 4 vs. 6 & 0.0081 [0.0014, 0.0264] vs. 0.0024 [0.0007, 0.0216] & 0.3524 & 0.8000\\
\cmidrule{2-7}
\hspace{1em} & Wk10 MBC & *02/*04 vs. *04/*04 & 4 vs. 6 & 0.0440 [0.0230, 0.1404] vs. 0.1263 [0.0214, 0.2148] & 0.3524 & 0.8000\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 6 & 0.0440 [0.0230, 0.1404] vs. 0.0854 [0.0005, 0.1057] & 0.7619 & 0.9797\\
\cmidrule{3-7}
\hspace{1em} &  & *04/*04 vs. *04/*05 or *04/*06 & 6 vs. 6 & 0.1263 [0.0214, 0.2148] vs. 0.0854 [0.0005, 0.1057] & 0.3939 & 0.8000\\
\cmidrule{2-7}
\hspace{1em} & Wk16 MBC & *02/*04 vs. *04/*04 & 4 vs. 5 & 0.0259 [0.0080, 0.0653] vs. 0.0263 [0.0030, 0.0412] & 0.9048 & 0.9797\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 6 & 0.0259 [0.0080, 0.0653] vs. 0.0225 [0.0001, 0.0826] & 0.9143 & 0.9797\\
\cmidrule{3-7}
\hspace{1em} &  & *04/*04 vs. *04/*05 or *04/*06 & 5 vs. 6 & 0.0263 [0.0030, 0.0412] vs. 0.0225 [0.0001, 0.0826] & 0.9307 & 0.9797\\
\cmidrule{2-7}
\hspace{1em} & Wk3 GC & *02/*04 vs. *04/*04 & 2 vs. 3 & 2.3429 [1.6281, 3.0577] vs. 1.2946 [0.7917, 2.8275] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk9 PB & *02/*04 vs. *04/*04 & 2 vs. 4 & 0.6629 [0.4731, 0.8527] vs. 0.6510 [0.1856, 0.9081] & --- & ---\\
\cmidrule{1-7}
\addlinespace[0.3em]
\multicolumn{7}{l}{\textbf{100 µg}}\\
\hspace{1em} & Wk4 MBC & *02/*02 vs. *02/*04 & 7 vs. 4 & 0.0566 [0.0139, 0.1649] vs. 0.0185 [0.0014, 0.0545] & 0.1091 & 0.7273\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *02/*05 or *02/*06 & 7 vs. 2 & 0.0566 [0.0139, 0.1649] vs. 0.0129 [0.0074, 0.0184] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *04/*05 or *04/*06 & 7 vs. 3 & 0.0566 [0.0139, 0.1649] vs. 0.0062 [0.0055, 0.0092] & ***0.0167*** & 0.2424\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *02/*05 or *02/*06 & 4 vs. 2 & 0.0185 [0.0014, 0.0545] vs. 0.0129 [0.0074, 0.0184] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 3 & 0.0185 [0.0014, 0.0545] vs. 0.0062 [0.0055, 0.0092] & 0.4000 & 0.8000\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*05 or *02/*06 vs. *04/*05 or *04/*06 & 2 vs. 3 & 0.0129 [0.0074, 0.0184] vs. 0.0062 [0.0055, 0.0092] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk8 MBC & *02/*02 vs. *02/*04 & 7 vs. 4 & 0.0159 [0.0055, 0.0608] vs. 0.0134 [0.0016, 0.0240] & 0.3152 & 0.8000\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *02/*05 or *02/*06 & 7 vs. 2 & 0.0159 [0.0055, 0.0608] vs. 0.0082 [0.0058, 0.0105] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *04/*05 or *04/*06 & 7 vs. 2 & 0.0159 [0.0055, 0.0608] vs. 0.0033 [0.0023, 0.0043] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *02/*05 or *02/*06 & 4 vs. 2 & 0.0134 [0.0016, 0.0240] vs. 0.0082 [0.0058, 0.0105] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *04/*05 or *04/*06 & 4 vs. 2 & 0.0134 [0.0016, 0.0240] vs. 0.0033 [0.0023, 0.0043] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*05 or *02/*06 vs. *04/*05 or *04/*06 & 2 vs. 2 & 0.0082 [0.0058, 0.0105] vs. 0.0033 [0.0023, 0.0043] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk10 MBC & *02/*02 vs. *02/*04 & 7 vs. 4 & 0.1951 [0.1188, 0.6376] vs. 0.1007 [0.0281, 0.1305] & ***0.0242*** & 0.2424\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *02/*05 or *02/*06 & 7 vs. 2 & 0.1951 [0.1188, 0.6376] vs. 0.0577 [0.0461, 0.0692] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *02/*05 or *02/*06 & 4 vs. 2 & 0.1007 [0.0281, 0.1305] vs. 0.0577 [0.0461, 0.0692] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk16 MBC & *02/*02 vs. *02/*04 & 7 vs. 4 & 0.1010 [0.0452, 0.2718] vs. 0.0457 [0.0110, 0.0817] & 0.1636 & 0.8000\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*02 vs. *02/*05 or *02/*06 & 7 vs. 2 & 0.1010 [0.0452, 0.2718] vs. 0.0332 [0.0280, 0.0385] & --- & ---\\
\cmidrule{3-7}
\hspace{1em} &  & *02/*04 vs. *02/*05 or *02/*06 & 4 vs. 2 & 0.0457 [0.0110, 0.0817] vs. 0.0332 [0.0280, 0.0385] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk3 GC & *02/*02 vs. *02/*04 & 4 vs. 3 & 2.1944 [0.4144, 4.6746] vs. 2.7265 [0.9546, 5.4440] & 0.6286 & 0.9670\\
\cmidrule{2-7}
\hspace{1em} & Wk11 GC & *02/*02 vs. *02/*04 & 2 vs. 4 & 0.2658 [0.0148, 0.5167] vs. 0.3717 [0.0116, 1.6519] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk9 PB & *02/*02 vs. *02/*04 & 4 vs. 3 & 0.7086 [0.0858, 2.2943] vs. 0.4593 [0.1946, 2.0745] & 0.8571 & 0.9797\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:mag-tab-vrc01-dose-supp}Table S5}
\centering
\fontsize{6}{8}\selectfont
\begin{tabular}[t]{ll>{\raggedright\arraybackslash}p{5.1cm}>{\raggedright\arraybackslash}p{.9cm}l>{\raggedright\arraybackslash}p{1.1cm}>{\raggedright\arraybackslash}p{1.1cm}}
\toprule
\multicolumn{5}{c}{ } & \multicolumn{2}{c}{P Value} \\
\cmidrule(l{3pt}r{3pt}){6-7}
 &  & Comparison & Sample Sizes & Median (Range) & Unadjusted & FDR Adjusted\\
\midrule
\addlinespace[0.3em]
\multicolumn{7}{l}{\textbf{\*02/*04}}\\
\hspace{1em} & Wk4 MBC & 20 µg vs. 100 µg & 4 vs. 4 & 0.0092 [0.0049, 0.0572] vs. 0.0185 [0.0014, 0.0545] & 0.8857 & 0.9048\\
\cmidrule{2-7}
\hspace{1em} & Wk8 MBC & 20 µg vs. 100 µg & 4 vs. 4 & 0.0054 [0.0018, 0.0469] vs. 0.0134 [0.0016, 0.0240] & 0.8857 & 0.9048\\
\cmidrule{2-7}
\hspace{1em} & Wk10 MBC & 20 µg vs. 100 µg & 4 vs. 4 & 0.0440 [0.0230, 0.1404] vs. 0.1007 [0.0281, 0.1305] & 0.4857 & 0.9048\\
\cmidrule{2-7}
\hspace{1em} & Wk16 MBC & 20 µg vs. 100 µg & 4 vs. 4 & 0.0259 [0.0080, 0.0653] vs. 0.0457 [0.0110, 0.0817] & 0.6857 & 0.9048\\
\cmidrule{2-7}
\hspace{1em} & Wk3 GC & 20 µg vs. 100 µg & 2 vs. 3 & 2.3429 [1.6281, 3.0577] vs. 2.7265 [0.9546, 5.4440] & --- & ---\\
\cmidrule{2-7}
\hspace{1em} & Wk9 PB & 20 µg vs. 100 µg & 2 vs. 3 & 0.6629 [0.4731, 0.8527] vs. 0.4593 [0.1946, 2.0745] & --- & ---\\
\cmidrule{1-7}
\addlinespace[0.3em]
\multicolumn{7}{l}{\textbf{\*04/*05 or *04/*06}}\\
\hspace{1em} & Wk4 MBC & 20 µg vs. 100 µg & 6 vs. 3 & 0.0066 [0.0031, 0.0140] vs. 0.0062 [0.0055, 0.0092] & 0.9048 & 0.9048\\
\cmidrule{2-7}
\hspace{1em} & Wk8 MBC & 20 µg vs. 100 µg & 6 vs. 2 & 0.0024 [0.0007, 0.0216] vs. 0.0033 [0.0023, 0.0043] & --- & ---\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:qaicc-tab-supp}Table S6}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{lrrrrr}
\toprule
Model & n & K & LL & Dispersion & QAICc\\
\midrule
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk4 MBC}}\\
\hspace{1em}Allele & 35 & 3 & -954.5112 & 67.96823 & 33.63438\\
\hspace{1em}Full & 35 & 4 & -953.5981 & 71.07256 & 36.16783\\
\hspace{1em}Dose & 35 & 3 & -1241.2651 & 102.81975 & 41.70371\\
\hspace{1em}Null & 35 & 2 & -1353.1930 & 110.50062 & 42.45420\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk8 MBC}}\\
\hspace{1em}Allele & 34 & 3 & -467.4507 & 27.70813 & 37.91914\\
\hspace{1em}Full & 34 & 4 & -461.2600 & 30.04265 & 40.08632\\
\hspace{1em}Dose & 34 & 3 & -615.3809 & 47.22338 & 47.76716\\
\hspace{1em}Null & 34 & 2 & -684.2942 & 44.60637 & 49.94195\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk10 MBC}}\\
\hspace{1em}Allele & 33 & 3 & -3913.2854 & 275.82562 & 34.31452\\
\hspace{1em}Full & 33 & 4 & -3913.0473 & 284.73788 & 36.91383\\
\hspace{1em}Dose & 33 & 3 & -4507.3975 & 325.05221 & 38.48756\\
\hspace{1em}Null & 33 & 2 & -4997.3051 & 397.41236 & 39.50109\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk16 MBC}}\\
\hspace{1em}Allele & 31 & 3 & -1192.3772 & 95.31918 & 31.38919\\
\hspace{1em}Full & 31 & 4 & -1189.6335 & 97.33573 & 33.98238\\
\hspace{1em}Dose & 31 & 3 & -1638.2275 & 127.00529 & 40.55027\\
\hspace{1em}Null & 31 & 2 & -2049.7041 & 178.03677 & 46.54474\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk3 GC}}\\
\hspace{1em}Allele & 26 & 3 & -7480.1546 & 486.41216 & 37.62126\\
\hspace{1em}Full & 26 & 4 & -7182.3606 & 490.01431 & 39.21966\\
\hspace{1em}Null & 26 & 2 & -11266.3607 & 803.67639 & 50.50554\\
\hspace{1em}Dose & 26 & 3 & -10976.7429 & 779.39438 & 51.89263\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk11 GC}}\\
\hspace{1em}Null & 26 & 2 & -8550.4050 & 1001.94407 & 26.62847\\
\hspace{1em}Allele & 26 & 3 & -7690.3863 & 705.77005 & 26.97410\\
\hspace{1em}Dose & 26 & 3 & -8333.1437 & 881.98514 & 28.63592\\
\hspace{1em}Full & 26 & 4 & -7474.9931 & 773.55665 & 29.23106\\
\addlinespace[0.3em]
\multicolumn{6}{l}{\textbf{Wk9 PB}}\\
\hspace{1em}Allele & 26 & 3 & -628.4218 & 45.03017 & 34.45853\\
\hspace{1em}Dose & 26 & 3 & -655.0902 & 46.71709 & 35.61993\\
\hspace{1em}Full & 26 & 4 & -613.5097 & 45.92447 & 36.62296\\
\hspace{1em}Null & 26 & 2 & -759.2088 & 49.71729 & 37.58511\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:quasipoisson-fit-tab-supp}Table S7}
\centering
\resizebox{\linewidth}{!}{
\begin{tabular}[t]{lllll}
\toprule
Parameter & Allele & Full & Dose & Null\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk4 MBC}}\\
\hspace{1em}*02 & 0.021 (0.011, 0.031) & 0.021 (0.008, 0.033) &  & \\
\hspace{1em}*04 & 0.006 (0.001, 0.012) & 0.006 (0.000, 0.012) &  & \\
\hspace{1em}Low &  &  & 0.013 (0.001, 0.025) & \\
\hspace{1em}Delta &  & 0.001 (-0.012, 0.015) & 0.015 (-0.004, 0.034) & \\
\hspace{1em}Vacc. &  &  &  & 0.022 (0.011, 0.032)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk8 MBC}}\\
\hspace{1em}*02 & 0.011 (0.006, 0.015) & 0.010 (0.004, 0.015) &  & \\
\hspace{1em}*04 & 0.003 (0.001, 0.005) & 0.003 (0.000, 0.005) &  & \\
\hspace{1em}Low &  &  & 0.006 (0.001, 0.012) & \\
\hspace{1em}Delta &  & 0.002 (-0.004, 0.008) & 0.008 (-0.001, 0.016) & \\
\hspace{1em}Vacc. &  &  &  & 0.011 (0.007, 0.015)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk10 MBC}}\\
\hspace{1em}*02 & 0.085 (0.056, 0.115) & 0.085 (0.041, 0.128) &  & \\
\hspace{1em}*04 & 0.052 (0.024, 0.079) & 0.052 (0.023, 0.080) &  & \\
\hspace{1em}Low &  &  & 0.086 (0.045, 0.127) & \\
\hspace{1em}Delta &  & 0.002 (-0.069, 0.073) & 0.060 (-0.008, 0.128) & \\
\hspace{1em}Vacc. &  &  &  & 0.116 (0.078, 0.153)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk16 MBC}}\\
\hspace{1em}*02 & 0.050 (0.032, 0.069) & 0.052 (0.029, 0.076) &  & \\
\hspace{1em}*04 & 0.012 (0.002, 0.021) & 0.012 (0.001, 0.023) &  & \\
\hspace{1em}Low &  &  & 0.026 (0.005, 0.046) & \\
\hspace{1em}Delta &  & -0.004 (-0.030, 0.023) & 0.049 (0.012, 0.087) & \\
\hspace{1em}Vacc. &  &  &  & 0.053 (0.030, 0.076)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk3 GC}}\\
\hspace{1em}*02 & 1.435 (0.874, 1.996) & 1.665 (1.070, 2.261) &  & \\
\hspace{1em}*04 & 0.506 (0.154, 0.858) & 0.584 (0.185, 0.983) &  & \\
\hspace{1em}Low &  &  & 1.353 (0.500, 2.206) & \\
\hspace{1em}Delta &  & -0.523 (-1.067, 0.020) & 0.584 (-0.747, 1.914) & \\
\hspace{1em}Vacc. &  &  &  & 1.645 (0.970, 2.320)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk11 GC}}\\
\hspace{1em}*02 & 0.602 (0.157, 1.047) & 0.630 (0.113, 1.147) &  & \\
\hspace{1em}*04 & 0.103 (-0.127, 0.333) & 0.008 (-0.071, 0.087) &  & \\
\hspace{1em}Low &  &  & 0.764 (0.116, 1.411) & \\
\hspace{1em}Delta &  & 0.147 (-0.631, 0.925) & -0.317 (-1.183, 0.550) & \\
\hspace{1em}Vacc. &  &  &  & 0.629 (0.154, 1.104)\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk9 PB}}\\
\hspace{1em}*02 & 0.386 (0.274, 0.497) & 0.268 (-0.009, 0.544) &  & \\
\hspace{1em}*04 & 0.159 (-0.008, 0.326) & 0.115 (-0.064, 0.295) &  & \\
\hspace{1em}Low &  &  & 0.205 (-0.080, 0.489) & \\
\hspace{1em}Delta &  & 0.225 (-0.274, 0.723) & 0.508 (0.160, 0.856) & \\
\hspace{1em}Vacc. &  &  &  & 0.648 (0.463, 0.834)\\
\bottomrule
\end{tabular}}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:quasipoisson-genotype-tab-supp}Table S8}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{ll}
\toprule
Genotype & Percent (95\% CI)\\
\midrule
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk4 MBC}}\\
\hspace{1em}*02/*02 & 0.042 (0.022, 0.062)\\
\hspace{1em}*02/*04 & 0.028 (0.017, 0.038)\\
\hspace{1em}*02/*05 or *02/*06 & 0.021 (0.011, 0.031)\\
\hspace{1em}*04/*04 & 0.013 (0.002, 0.023)\\
\hspace{1em}*04/*05 or *04/*06 & 0.006 (0.001, 0.012)\\
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk8 MBC}}\\
\hspace{1em}*02/*02 & 0.021 (0.013, 0.029)\\
\hspace{1em}*02/*04 & 0.014 (0.009, 0.018)\\
\hspace{1em}*02/*05 or *02/*06 & 0.011 (0.006, 0.015)\\
\hspace{1em}*04/*04 & 0.006 (0.002, 0.011)\\
\hspace{1em}*04/*05 or *04/*06 & 0.003 (0.001, 0.005)\\
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk10 MBC}}\\
\hspace{1em}*02/*02 & 0.171 (0.112, 0.229)\\
\hspace{1em}*02/*04 & 0.137 (0.100, 0.174)\\
\hspace{1em}*02/*05 or *02/*06 & 0.085 (0.056, 0.115)\\
\hspace{1em}*04/*04 & 0.103 (0.048, 0.158)\\
\hspace{1em}*04/*05 or *04/*06 & 0.052 (0.024, 0.079)\\
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk16 MBC}}\\
\hspace{1em}*02/*02 & 0.101 (0.063, 0.138)\\
\hspace{1em}*02/*04 & 0.062 (0.042, 0.082)\\
\hspace{1em}*02/*05 or *02/*06 & 0.050 (0.032, 0.069)\\
\hspace{1em}*04/*04 & 0.023 (0.004, 0.043)\\
\hspace{1em}*04/*05 or *04/*06 & 0.012 (0.002, 0.021)\\
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk3 GC}}\\
\hspace{1em}*02/*02 & 2.870 (1.747, 3.993)\\
\hspace{1em}*02/*04 & 1.941 (1.321, 2.561)\\
\hspace{1em}*02/*05 or *02/*06 & 1.435 (0.874, 1.996)\\
\hspace{1em}*04/*04 & 1.012 (0.308, 1.716)\\
\hspace{1em}*04/*05 or *04/*06 & 0.506 (0.154, 0.858)\\
\addlinespace[0.3em]
\multicolumn{2}{l}{\textbf{Wk9 PB}}\\
\hspace{1em}*02/*02 & 0.771 (0.548, 0.994)\\
\hspace{1em}*02/*04 & 0.545 (0.352, 0.738)\\
\hspace{1em}*02/*05 or *02/*06 & 0.386 (0.274, 0.497)\\
\hspace{1em}*04/*04 & 0.318 (-0.016, 0.652)\\
\hspace{1em}*04/*05 or *04/*06 & 0.159 (-0.008, 0.326)\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:quasipoisson-ratio-tab-supp}Table S9}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{ll}
\toprule
Visit & Ratio (95\% CI)\\
\midrule
Wk3 GC & 2.836 (0.443, 5.229)\\
Wk4 MBC & 3.278 (0.000, 6.613)\\
Wk8 MBC & 3.259 (0.584, 5.934)\\
Wk9 PB & 2.425 (0.000, 5.124)\\
Wk10 MBC & 1.650 (0.544, 2.757)\\
Wk16 MBC & 4.360 (0.163, 8.557)\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:quasipoisson-diff-tab-supp}Table S10}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{lll}
\toprule
Visit & Difference (95\% CI) & P Value\\
\midrule
Wk3 GC & 0.929 (0.226, 1.632) & ***0.0095***\\
Wk4 MBC & 0.015 (0.003, 0.027) & ***0.0169***\\
Wk8 MBC & 0.007 (0.002, 0.012) & ***0.0030***\\
Wk9 PB & 0.227 (0.018, 0.435) & ***0.0333***\\
Wk10 MBC & 0.034 (-0.009, 0.076) & 0.1239\\
Wk16 MBC & 0.039 (0.017, 0.061) & ***0.0006***\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begin{table}[!h]

\caption{\label{tab:ratio-tab-vacc-supp}Table S11}
\centering
\fontsize{10}{12}\selectfont
\begin{tabular}[t]{lllll}
\toprule
\multicolumn{1}{c}{Frequency} & \multicolumn{1}{c}{Group} & \multicolumn{1}{c}{Ratio} & \multicolumn{1}{c}{95\% CI} & \multicolumn{1}{c}{P-value} \\
\cmidrule(l{3pt}r{3pt}){1-1} \cmidrule(l{3pt}r{3pt}){2-2} \cmidrule(l{3pt}r{3pt}){3-3} \cmidrule(l{3pt}r{3pt}){4-4} \cmidrule(l{3pt}r{3pt}){5-5}
mRNA & Homozygote & 3.9 & 3.0 to 5.3 & <0.0001\\
mRNA & Heterozygote & 4.2 & 3.3 to 5.1 & 0.0001\\
Unique HCDR3 & Homozygote & 3.8 & 3.1 to 4.9 & <0.0001\\
Unique HCDR3 & Heterozygote & 3.7 & 3.0 to 4.5 & <0.0001\\
\bottomrule
\end{tabular}
\end{table}

\clearpage

\begingroup\fontsize{10}{12}\selectfont

\begin{longtable}[t]{llrrr}
\caption{\label{tab:bcr-usage-tab-comb-supp}Table S12}\\
\toprule
dose & ID & *02 & *04 & Ratio\\
\midrule
\endfirsthead
\caption[]{Table S12 \textit{(continued)}}\\
\toprule
dose & ID & *02 & *04 & Ratio\\
\midrule
\endhead

\endfoot
\bottomrule
\endlastfoot
20µg & 046 & 40.5 & 5.5 & 7.364\\
20µg & 077 & 38.0 & 13.0 & 2.923\\
20µg & 100 & 140.0 & 18.0 & 7.778\\
20µg & 187 & 31.0 & 15.0 & 2.067\\
100µg & 062 & 88.0 & 21.0 & 4.190\\
100µg & 064 & 138.0 & 19.0 & 7.263\\
100µg & 112 & 68.0 & 4.0 & 17.000\\
100µg & 193 & 221.5 & 12.5 & 17.720\\
\midrule
 & Median &  &  & 7.313\\*
\end{longtable}
\endgroup{}

\clearpage

\begingroup\fontsize{10}{12}\selectfont

\begin{longtable}[t]{llrrr}
\caption{\label{tab:bcr-usage-tab-timepoint-supp}Table S13}\\
\toprule
dose & ID & *02 & *04 & Ratio\\
\midrule
\endfirsthead
\caption[]{Table S13 \textit{(continued)}}\\
\toprule
dose & ID & *02 & *04 & Ratio\\
\midrule
\endhead

\endfoot
\bottomrule
\endlastfoot
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk4 MBC}}\\
\hspace{1em}20µg & 046 & 6.0 & 1.0 & 6.000\\
\hspace{1em}20µg & 077 & 5.5 & 1.5 & 3.667\\
\hspace{1em}20µg & 100 & 30.0 & 4.0 & 7.500\\
\hspace{1em}20µg & 187 & 2.0 & 5.0 & 0.400\\
\hspace{1em}100µg & 062 & 1.0 & 2.0 & 0.500\\
\hspace{1em}100µg & 064 & 27.0 & 5.0 & 5.400\\
\hspace{1em}100µg & 112 & 8.0 & 2.0 & 4.000\\
\hspace{1em}100µg & 193 & 37.0 & 3.0 & 12.333\\
\midrule
\hspace{1em} & Median &  &  & 4.700\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk8 MBC}}\\
\hspace{1em}20µg & 046 & 1.0 & 0.0 & Inf\\
\hspace{1em}20µg & 077 & 7.5 & 0.5 & 15.000\\
\hspace{1em}20µg & 100 & 24.0 & 2.0 & 12.000\\
\hspace{1em}20µg & 187 & 2.0 & 2.0 & 1.000\\
\hspace{1em}100µg & 062 & 3.0 & 0.0 & Inf\\
\hspace{1em}100µg & 064 & 22.0 & 1.0 & 22.000\\
\hspace{1em}100µg & 112 & 17.0 & 1.0 & 17.000\\
\hspace{1em}100µg & 193 & 15.0 & 2.0 & 7.500\\
\midrule
\hspace{1em} & Median &  &  & 16.000\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk10 MBC}}\\
\hspace{1em}20µg & 046 & 27.0 & 4.0 & 6.750\\
\hspace{1em}20µg & 077 & 1.0 & 2.0 & 0.500\\
\hspace{1em}20µg & 100 & 16.0 & 7.0 & 2.286\\
\hspace{1em}20µg & 187 & 18.0 & 3.0 & 6.000\\
\hspace{1em}100µg & 062 & 11.0 & 7.0 & 1.571\\
\hspace{1em}100µg & 064 & 18.0 & 4.0 & 4.500\\
\hspace{1em}100µg & 112 & 11.0 & 0.0 & Inf\\
\hspace{1em}100µg & 193 & 34.5 & 2.5 & 13.800\\
\midrule
\hspace{1em} & Median &  &  & 5.250\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk16 MBC}}\\
\hspace{1em}20µg & 046 & 6.5 & 0.5 & 13.000\\
\hspace{1em}20µg & 077 & 4.0 & 1.0 & 4.000\\
\hspace{1em}20µg & 100 & 28.0 & 5.0 & 5.600\\
\hspace{1em}20µg & 187 & 9.0 & 5.0 & 1.800\\
\hspace{1em}100µg & 062 & 8.0 & 5.0 & 1.600\\
\hspace{1em}100µg & 064 & 34.0 & 2.0 & 17.000\\
\hspace{1em}100µg & 112 & 8.0 & 0.0 & Inf\\
\hspace{1em}100µg & 193 & 23.0 & 3.0 & 7.667\\
\midrule
\hspace{1em} & Median &  &  & 6.633\\
 \hline \pagebreak
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk3 GC}}\\
\hspace{1em}20µg & 046 &  &  \vphantom{2} & \\
\hspace{1em}20µg & 077 & 19.0 & 8.0 & 2.375\\
\hspace{1em}20µg & 100 & 32.0 & 0.0 & Inf\\
\hspace{1em}20µg & 187 &  &  \vphantom{2} & \\
\hspace{1em}100µg & 062 & 49.0 & 7.0 & 7.000\\
\hspace{1em}100µg & 064 &  &  & \\
\hspace{1em}100µg & 112 & 2.0 & 0.0 & Inf\\
\hspace{1em}100µg & 193 & 31.0 & 0.0 & Inf\\
\midrule
\hspace{1em} & Median &  &  & \vphantom{1} Inf\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk11 GC}}\\
\hspace{1em}20µg & 046 &  &  \vphantom{1} & \\
\hspace{1em}20µg & 077 &  &  & \\
\hspace{1em}20µg & 100 & 8.0 & 0.0 & Inf\\
\hspace{1em}20µg & 187 &  &  \vphantom{1} & \\
\hspace{1em}100µg & 062 & 16.0 & 0.0 & Inf\\
\hspace{1em}100µg & 064 & 1.0 & 0.0 & Inf\\
\hspace{1em}100µg & 112 & 22.0 & 0.0 & Inf\\
\hspace{1em}100µg & 193 & 51.0 & 0.0 & Inf\\
\midrule
\hspace{1em} & Median &  &  & Inf\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Wk9 PB}}\\
\hspace{1em}20µg & 046 &  &  & \\
\hspace{1em}20µg & 077 & 1.0 & 0.0 & Inf\\
\hspace{1em}20µg & 100 & 2.0 & 0.0 & Inf\\
\hspace{1em}20µg & 187 &  &  & \\
\hspace{1em}100µg & 062 &  &  & \\
\hspace{1em}100µg & 064 & 36.0 & 7.0 & 5.143\\
\hspace{1em}100µg & 112 & 0.0 & 1.0 & 0.000\\
\hspace{1em}100µg & 193 & 30.0 & 2.0 & 15.000\\
\midrule
\hspace{1em} & Median &  &  & 15.000\\*
\end{longtable}
\endgroup{}





