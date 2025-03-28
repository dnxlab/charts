# plex-chart

helm upgrade --install plex --namespace plex --create-namespace ./plex-chart --set env.claimToken="claim-..."