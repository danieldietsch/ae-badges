# Badges for the artifact evaluation of the VMCAI conference.
You may put these on your paper if you were awarded by the VMCAI committee.
For more information see [Call for Artifacts][1].

The badges also work when printed in grayscale.

![All badges in color, and black and white](https://raw.githubusercontent.com/schaetzc/vmcai-badges/master/preview.png)

The badges are licensed under CC0. No attribution is required.

  [1]: https://popl20.sigplan.org/home/VMCAI-2020#Call-for-Artifacts

## Placement

Because LNCS does not provide a standard placement for the badges, you need to experiment a little to find a good place for them. 

They should be on the first page and not inside the margins (because the margins will be cut by Springer before publication).

You can start with the following Latex snippet: 

```tex
\documentclass{lncs}
\usepackage{graphicx}

\usepackage[firstpage]{draftwatermark}
\SetWatermarkText{\raisebox{14cm}{%
  \includegraphics{vmcai-badges/1-available} \hspace{8cm} \includegraphics{vmcai-badges/2-functional}%
}}
\SetWatermarkAngle{0}
```

The exact positioning depends on your author list, your title size, and the number of lines you use for your affiliations. 

