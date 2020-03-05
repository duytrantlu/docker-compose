FROM mongo:4.1.13-bionic
ADD ./replicate.js /replicate.js
ADD ./seed.js /seed.js
ADD ./setup.sh /setup.sh
RUN chmod +x setup.sh
CMD ["/setup.sh"]