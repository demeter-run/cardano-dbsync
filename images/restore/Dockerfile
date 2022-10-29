FROM inputoutput/cardano-db-sync:13.0.5-extra-args

RUN curl https://update-cardano-mainnet.iohk.io/cardano-db-sync/13/db-sync-snapshot-schema-13-block-7939028-x86_64.tgz --output snapshot.tgz

RUN tar - xvzf snapshot.tgz

RUN rm snapshot.tgz