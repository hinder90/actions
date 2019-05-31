FROM golang:1.11

LABEL version="1.0.1"
LABEL maintainer="Apex (forked by hinder90)"
LABEL repository="http://github.com/hinder90/actions"
LABEL homepage="http://github.com/hinder90/actions/slack"
LABEL "com.github.actions.name"="Slack"
LABEL "com.github.actions.description"="Send a Slack message"
LABEL "com.github.actions.icon"="message-circle"
LABEL "com.github.actions.color"="white"

RUN go get github.com/hinder90/actions/slack/cmd/slack

ENTRYPOINT ["slack"]
