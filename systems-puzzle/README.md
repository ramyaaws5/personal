# Insight DevOps Engineering Systems Puzzle

#### Below changes are made to the original confirguration file to make it work ###

1) Need to change "nginx port" from 80:8080 to 8080:80 in docker-compose.yml file -- After that I got 502 response as port was missing in app.py
2) Need to add "port=5001" in "app.py" file to get rid of 502 error
3) After making all the above changes http://localhost:8080 started to work
