SingMatch Web App - Beta

Windows local run:
1. Unzip this folder.
2. Open a terminal/PowerShell in this folder.
3. Run: python -m http.server 8000
4. On this PC open http://localhost:8000

Microphone access in modern browsers requires HTTPS or localhost. For iPhone install/use, host this folder on a HTTPS site (e.g. GitHub Pages) then open it in Safari, Share > Add to Home Screen.

Important limitation: pitch extraction from a full mixed song is a simple autocorrelation estimate and may detect accompaniment/harmony instead of the lead vocal. Accuracy score is a rough practice aid, not professional scoring. Headphones strongly recommended.
