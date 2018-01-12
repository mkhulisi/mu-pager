# mupdf-pager
Shell script to easily open a PDF file via MuPDF to a specific chapter if the PDF has no links.

Usage:
./mupdf-pager <path_to_pdf>/<filename> <chapter>
    
NB: 'filename' without extension

The script assumes the following directory structure:

    /path_to_pdf/..
             /filename.pdf
             /filename.txt

where 'filename.txt' contains a simple text file with two columns of text per line (first column is the chapter number, and second column is the page number) as shown in the sample file attached. One has to prepare this file ahead of time.

Miscellaneous:
The script is a quick hack for my Nokia N900 in order to quickly open songs from the songbook found on the following page on JW.org, https://www.jw.org/ss/tincwadzi-letitfolakalako/umculo-tingoma/Sing-Out-Joyfully-to-Jehovah-ngemagama-lamakhulu/. I will not attach it here due to copyright reasons, but it is freely downloadable.
