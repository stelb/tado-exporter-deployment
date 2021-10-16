# tado-exporter for kubernetes

yaml files to run [eko/tado-exporter](https://github.com/eko/tado-exporter) in kubernetes

## Install

Start pods and define service

    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml

Configure prometheus scraping with prometheus-operator

    kubectl apply -f svcmon.yaml

I run these in tado namespace

