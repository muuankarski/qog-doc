# From markdown source to latex pdf

pandoc --number-section --toc source.md -o output.pdf

# From markdown source to html with custom css

pandoc -s -S --number-section --toc --from=markdown+yaml_metadata_block --css bootstrap.min.css source.md -o output.html

# From markdown source to MS Word
pandoc --number-section --toc source.md -o output.docx
