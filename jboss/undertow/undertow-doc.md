git clone https://github.com/undertow-io/undertow-io-site
cd undertow-io-site
cp -R documentation/* <target-dir>
cp _config/documentation.yml <target-dir>

# include XNIO document
Document URL: https://docs.jboss.org/author/display/XNIO/Developer's+Guide
Wiki page, Tools->Export to epub->Unzip epub file (include all html and toc.ncx)
