docker build --force-rm=true \
--no-cache=true --build-arg DB_EDITION=se2 \
-t oracle/database:12.2.0.1-se2 -f Dockerfile .