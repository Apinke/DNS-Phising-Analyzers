 A standalone DNS Phishing Analyzer built on Gemma 3 Pro that runs entirely in your browser without any backend required.
To achieve this without a backend server (like Python or Cloud Run), this application leverages DNS-over-HTTPS
It uses Google's public DNS API to query A, MX, and TXT records directly from the client-side JavaScript. It also includes the standalone heuristic engine and the simulated Gemma 3 Pro threat appraisal.
