# lemontree

This java implementation can be used to run network analysis for gene expresssion data.
0. before start,  replace the expr_matrix.txt file with your data and tar to lemontree.tar.gz

* hint:  for expr_matrix.txt  there is a blank in the first line before sample name
* hint2: for all genes , remove the first unused name
0.  get the correct formatted expr_matrix.txt in the lemonontree.tar.gz(unzip to folder first);
    ./extractAllGene to update the gene in that folder;
    tar the folder back to lemontree.tar.gz again

1. upload all files to chtc
2. run the dagman file  by  condor_submit_dag lemontree.dag
3. select returned  go_output.txt and tight_clusterings.txt  file
