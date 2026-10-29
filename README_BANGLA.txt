NetConnect + MotoSeva V13 — IndexedDB PIN Import

1. ZIP extract করে index.html, netconnect.jpg, motoseva.jpg GitHub repository root-এ upload/replace করুন।
2. GitHub Settings > Pages > Deploy from a branch > main > /(root) > Save।
3. Live website reload করুন। CSV file Choose File > Import / Update PIN CSV।
4. Import progress দেখাবে। Import শেষ হলে 6-digit PIN দিয়ে Post Office select করুন।
5. পুরোনো V12 bill এবং item localStorage keys অপরিবর্তিত রাখা হয়েছে। Browser data clear করবেন না। Backup JSON রাখুন।
6. PIN database browser IndexedDB-তে থাকে, অন্য ফোনে নিজে থেকে sync হয় না।
7. CSV must contain pincode, officename, district, statename columns।
8. This release has not been tested on your exact mobile browser.
