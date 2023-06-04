fly -t tutorial set-pipeline -p tutorial-pipeline -c pipeline.yml -n
fly -t tutorial unpause-pipeline -p tutorial-pipeline
fly -t tutorial trigger-job -w -j tutorial-pipeline/job-hello-world