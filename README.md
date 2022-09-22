# neuromancer
Neuromancer is a script for static analysis of files, looking for complete or approximate malware signatures. Signatures included here are proof of concept at this time, not representing actual sample signatures. However, new actual signatures will be added as samples are indexed.

Neuromancer works by comparing not only the signatures as a whole, but also the position of the bytes, ensuring greater coverage for samples from the same family. You can change the tolerance value in the main class to refine your scans.
