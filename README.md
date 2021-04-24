KDB and Q Play
==============

Using https://github.com/KxSystems/jupyterq to run q.

To run notebook server first time: docker run -it --name myjupyterq -p 8888:8888 -v $(pwd)/notebooks:/jqnotebooks kxsys/jupyterq

Subsequent run: docker start -ai myjupyterq

