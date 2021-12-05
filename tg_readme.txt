sudo dnf in npm python-lxml
sudo dnf in npm install -g typescript google-closure-compiler
basex from zip file + update path
tsc from nodejs-typescript
xmltodict from python3-xmltodict


ONCE! make download-dblp
ONCE! make only-clean-dblp
ONCE! cp dblp.xml dblp-cleaned.xml

adapt playfiler
make tg-shrink-dblp

adapt csrankings.ts  (two places)
adapt util/csrankings.py
adapt util/make-collaboration-graph.py
make (conda deactivated)

adapt index.html <tr> ... </tr>
python3 -m http.server
