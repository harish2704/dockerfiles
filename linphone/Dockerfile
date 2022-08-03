FROM debian:testing

RUN apt-get update && apt-get install --no-install-recommends -y linphone-cli rlwrap

CMD [ "rlwrap", "linphonec"]
