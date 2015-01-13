# TwitterSocialGenomeProject

# Run Categorizer
Step 1: Open "setup-env.sh" and change the paths to your Java installation, and the location of your solr index.

Step 2: Open a terminal in this directory and type:

sh categorizer.sh

Note: If the line ". ./setup-env.sh" for some reason doesn't run on your machine, then you can copy and paste the contents of the entire file setup-env.sh in place of that line. However, it's more convenient to have a separate script for the environment setup so that you can easily write many different categorizers that use the same tools and environment settings uniformly.

#SOLR Database instructions
Some instructions for configuring the DB located here: https://github.com/ddrichman/solr-wikipedia-conf
