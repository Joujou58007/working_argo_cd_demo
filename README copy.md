# Run a Pod from yaml
`sudo kubectl apply -f deployement.yaml`


# To confirm it's runnning
`sudo kubectl get pods -o wide`
`sudo kubectl logs -l app=apollo`