Running org-mode html export in docker container
================================================

installation
------------

Download `docker-org-export` script and add it to your PATH.

running
-------

You can transform your org-file to html like this:

    docker-org-export index.org


seqdiag
-------
There is `seqdiag` support, so you can use this in your source code:

    #+begin_src seqdiag :file wap_success_seqdiag.png
    seqdiag {
    A -> B [label="Test edge"];
    }
    #+end_src
   

