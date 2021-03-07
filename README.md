# NGS_coverage_report
The find_genes.py Python script extends the coverage report produced by the sambamaba tool pipeline by outputting a list of genes that have less than 100% at 30x coverage.
The sambamba output file in the current working directory is the input of the find_genes.py script. The output file of the script is named Genes_with_less_than_100%_30x_coverage.csv. Below are instructions to run the script in a mac terminal.

To run...
# install libraries in your terminal
pip3 install pandas

# clone the GitHub repositiory 
git clone https://github.com/hasmitapatel18/coverage_test.git
# change directories to the coverage_test folder
cd coverage_test
# run the find_genes.py script
python3 find_genes.py

