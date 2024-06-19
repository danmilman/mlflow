Postgresql deployment command:
helm install postgresql oci://registry-1.docker.io/bitnamicharts/postgresql --set persistence.existingClaim=data-postgresql-0 --set volumePermissions.enabled=true
