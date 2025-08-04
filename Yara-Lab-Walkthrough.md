# Report: Creating Yara rules for threat detection
Objective: Learn how to create Yara signatures for detecting malware.

Key steps:
1. Analyzed the provided samples of malicious files to find unique strings and byte sequences (hex).
2.  Used the `strings` utility in the Linux terminal to extract text fragments.
3.  Formed the `meta` section in the rule, specifying the author and date.
4.  Wrote the `strings` section, defining several unique string indicators (`$a`, `$b`, ...).
5.  Formulated the `condition` section (for example, `uint16(0) == 0x5A4D and all of them`) so that the rule would only trigger when all conditions were met.
6.  Tested the rule on a collection of files, making sure that it correctly finds malicious samples and does not produce false positives.

Conclusions: Mastered the basic syntax of Yara, which allows you to create simple but effective signatures for Threat Hunting and Malware Analysis tasks.

Translated with DeepL.com (free version)
