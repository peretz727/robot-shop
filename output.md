SET INSTANA_AGENT_KEY="chen"
docker-compose build
docker-compose push
docker-compose pull
docker-compose up


# 14 It is bad working on master branch because many people working on the same files without something to manage it is not secured.
# also, in big scale, we want the master to be bug-free and stable, and also when someone pushes code, it is better to review it using PullRequest
