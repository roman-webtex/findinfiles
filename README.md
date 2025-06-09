# findinfiles
find text in files (doc(x), xls(x), xlsm, pdf, images, odt, ods)

uses gs, tesseract, pdftotext

fif "*.*" test - search test in all files
fif "*.*" file1 dir1 dir3 - search patterns from file1 (one pattern per line) in all files except dir1 and dir3

