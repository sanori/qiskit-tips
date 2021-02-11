FROM sanori/qiskit-notebook:latest

COPY --chown=${NB_UID}:${NB_GID} *.ipynb ./

USER $NB_UID