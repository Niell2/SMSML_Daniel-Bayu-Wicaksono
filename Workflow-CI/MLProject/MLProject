name: Workflow-CI-MLProject 

conda_env: conda.yaml       

entry_points:
  main:      
    parameters:
      n_clusters: {type: int, default: 3}
    command: "python modelling.py --n_clusters {n_clusters}"