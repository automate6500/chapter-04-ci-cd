FROM python:3.6

LABEL "com.github.actions.name"="Check"
LABEL "com.github.actions.description"="Check application code"

ADD entrypoint.sh /usr/local/bin/entrypoint.sh

ENTRYPOINT ["entrypoint.sh"]
