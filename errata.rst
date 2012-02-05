Subtree merge for RbST
**********************

- use subtree merge to add RST parsing to blog::

    git clone git@github.com:faircloth-lab/blog-theme.git faircloth-lab-blog
    git remote add jekyll-rst-remote https://github.com/xdissent/jekyll-rst.git
    git checkout -b jekyll-rst-branch jekyll-rst-remote/master
    git checkout master
    git read-tree --prefix=_plugins/jekyll-rst -u jekyll-rst-branch


